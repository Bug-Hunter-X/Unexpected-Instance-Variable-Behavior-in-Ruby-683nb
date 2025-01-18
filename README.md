# Unexpected Instance Variable Behavior in Ruby

This repository demonstrates a subtle bug in Ruby related to instance variable access.  If you attempt to modify an instance variable through its getter method without explicitly defining a setter, the instance variable remains unchanged. This can be a source of unexpected behavior and difficult-to-debug issues.

The `bug.rb` file shows the problematic code. The `bugSolution.rb` demonstrates the solution.  Please read the comments for details.