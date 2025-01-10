# Ruby Encapsulation Bug
This example demonstrates a common error in Ruby where direct manipulation of instance variables using `instance_variable_set` can compromise encapsulation.  This can lead to unexpected behavior and make code harder to maintain and debug.

The `bug.rb` file shows the problematic code. The `bugSolution.rb` file offers a better approach that respects encapsulation and utilizes accessor methods.