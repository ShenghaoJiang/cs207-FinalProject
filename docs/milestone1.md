## Milestone1 Document
You must clearly outline your software design for the project.  Here are some possible sections to
include in your document along with some prompts that you may want to address.

### Introduction
Describe problem the software solves and why it's important to solve that problem

### Background
Describe (briefly) the mathematical background and concepts as you see fit.  You **do not** need to
give a treatise on automatic differentation or dual numbers.  Just give the essential ideas (e.g.
the chain rule, the graph structure of calculations, elementary functions, etc).

### How to Use *PackageName*
How do you envision that a user will interact with your package?  What should they import?  How can
they instantiate AD objects?

**Note: This section should be a mix of pseudo code and text.  It should not include any actual
operations yet.**

### Software Organization
Discuss how you plan on organizing your software package.
* What will the directory structure look like?  
* What modules do you plan on including?  What is their basic functionality?
* Where will your test suite live?  Will you use `TravisCI`? `Coveralls`?
* How will you distribute your package (e.g. `PyPI`)?

### Implementation
Discuss how you plan on implementing the forward mode of automatic differentiation.
* What are the core data structures?
* What classes will you implement?
* What method and name attributes will your classes have?
* What external dependencies will you rely on?
* How will you deal with elementary functions like `sin` and `exp`?

Be sure to consider a variety of use cases.  For example, don't limit your design to scalar
functions of scalar values.  Make sure you can handle the situations of vector functions of vectors and
scalar functions of vectors.  Don't forget that people will want to use your library in algorithms
like Newton's method (among others).

Try to keep your report to a reasonable length.  It will form the core of your documentation, so you
want it to be a length that someone will actually want to read.

## Additional Comments
There is no need to have an implementation started for this Milestone.  You are now in the planning
phase.  This means that you should feel free to have a `project_planning` repo in your project
organization for scratch work and code.  The actual implementation will start after Milestone 1.
