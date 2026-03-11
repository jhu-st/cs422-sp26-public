0. Refer to the "Readings" assignment of the course website on ci/co & testing on how to create a fully funcional ci/cd workflow. You can also access https://github.com/jhu-st/ci-helloworld/ for the complete project.
1. Adding countOf function to `ArrayUtils.java` and writing tests in `ArrayUtilsTest.java` to achieve full BC should be straightforward.

2. Based on the specs of `cicirello/jacoco-badge-generator@v2.9.0` action, you can use the following directives if statement or branche coverages are less than it was on the previous run.

// Enables failing workflow if coverage is less than it was on previous run.
    fail-on-coverage-decrease: 
// Enables failing workflow if branches coverage is less than it was on previous run.
    fail-on-branches-decrease: