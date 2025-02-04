# Unexpected Behavior from Directly Accessing Instance Variables in Ruby

This repository demonstrates a common Ruby bug related to directly manipulating instance variables using `instance_variable_set` and `instance_variable_get`. While functional, this approach violates good object-oriented principles and can lead to maintainability issues.  The example shows how this direct access can bypass normal method behavior leading to unexpected results in larger or more complex applications.

**Recommended Solution:** Use accessor methods (`attr_accessor`, `attr_reader`, `attr_writer`) to interact with instance variables for better encapsulation and maintainability.