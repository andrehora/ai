# Software Testing Quiz Question

## Question 1: Unit Testing Best Practices

**Question:** Which of the following is the most important principle when writing unit tests?

A) Tests should cover all possible edge cases, including extremely unlikely scenarios  
B) Tests should be independent and not rely on the execution order or state from other tests  
C) Tests should always use real databases and external services for maximum accuracy  
D) Tests should be as complex as the code they are testing to ensure thorough coverage

**Correct Answer:** B

**Explanation:**  
The most important principle when writing unit tests is that they should be independent and not rely on the execution order or state from other tests. This ensures that:
- Tests can be run in any order
- A failing test doesn't cause other tests to fail
- Tests are easier to debug and maintain
- The test suite is reliable and reproducible

While edge cases are important (option A), tests should focus on realistic scenarios. Option C is incorrect because unit tests should use mocks and stubs instead of real external dependencies. Option D is incorrect because tests should be simple and straightforward, not complex.

**Topic:** Unit Testing  
**Difficulty:** Intermediate  
**Learning Objective:** Understand the FIRST principles of unit testing (Fast, Independent, Repeatable, Self-validating, Timely)
