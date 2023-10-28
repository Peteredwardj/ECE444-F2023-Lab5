# ECE444-F2023-Lab5

This repo is taken from examples in https://github.com/mjhea0/flaskr-tdd

<h2>Test-Driven Development</h2>

__Pros__:

**Improved Code Quality**<br>
TDD requires every part of the code to be tested, expecting developers to write tests for each functionality and ensure that they work properly and as intended.

**Identifying Bugs**<br>TDD helps us test and think about edge cases that we might have missed during development, this reduces problems from happening during production which might be difficult to debug and critical.

**Faster development, useful for continuous delivery**<br>Though it might take time to actually write the tests initially, tests help reduce debugging and reduce errors. With having to spend less time debugging errors, the project’s lifecycle will be much faster. Problems occurring in production will happen less because most edge cases are identified already via the tests.

**Could be used as a source of documentation**<br> Though it might not be actual documentation, test cases could be used as a point of reference for developers to understand and work with the codebase, such as identifying what an implementation does exactly and what kind of cases it should handle. 

__Cons:__

**Time-consuming**<br>Having to create tests might take time and slow down development, not ideal for an upcoming deadline or a fast-paced project like a startup where speed is critical.

**May be difficult to maintain**<br>As time goes by, the codebase may get more involved and complicated for example implementation of something might also affect other implementations causing some previous tests to fail. With this, it might be difficult to maintain the tests as they could get more and more complex.

**Overtesting**<br>Some implementations may not require tests, but developers could easily get carried away and write tests that may not even be necessary reducing their productivity in working on the implementation itself. An example of this would be a writing test for a function that prints something, the printing is something obvious. 

**Requires learning for correct implementation**<br> Developers might have to learn how to implement tests for the stack they are working on which might not be intuitive, and developers will also have to learn what tests are considered useful and not for their codebase which could be a hassle 
