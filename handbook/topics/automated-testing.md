# Automated Testing


Automated testing is a software testing technique that **automates the process of validating the functionality of software and ensures it meets requirements before being released into production.**  
This is well-suited for projects that are **large** or **require testing to be repeated multiple times**. It also could be applied to **projects that already have been through an initial manual testing process.**

---

### Best Practices / When To Use

- <ins>Plan your testing carefully.</ins> Make sure your test cases are clearly defined and well written. Test cases should be self-contained and easy to understand  

<br>

- <ins>Test as early and as often as possible during development.</ins> The earlier you identify a bug, the easier it is to fix. Conversely, bugs found late on require much more effort to fix  

<br>

- <ins>Plan the order in which tests run.</ins> Often, you can use one test to create the state you need for a second test. For instance, creating a user before you then test the account page  

<br>

- If possible, <ins>use tools that can schedule testing automatically,</ins> either when new code is pushed or according to a schedule. This makes sure your code is always well tested  

<br>

- <ins>Set up alerts so you are told as soon as a test fails.</ins> Then decide if you should abort the current test run or let it complete. For instance, if it is a serious bug it is probably best to abort and fix the bug  

<br>

- Remember that <ins>you need to constantly reassess your test plans as your app develops and changes.</ins> There is no point testing legacy features that are no longer part of the applications  

---

## Common Bad Practices / When Not To Use

- There is no point testing legacy features that are no longer part of the applications  

<br>

- Running tests without reassessing them as the application changes  

<br>

- Not setting up alerts for failures, which can delay bug fixes  

<br>

- Running tests in the wrong order, causing dependencies to fail  

<br>

- Only relying on manual testing when automation would be more efficient  

---



### Types of Automated Testing

- ***Unit Testing***  
- ***Integration Testing***  
- ***API Testing***  
- ***UI Testing***  

---

### Why should automated testing be used?

*Put simply, automating your testing allows you to do more testing, faster, and more efficiently. More specifically, it brings these benefits:*

1. **Increased efficiency**  
2. **Improved accuracy**  
3. **Enhanced test coverage**  
4. **Faster time-to-market**  
5. **Facilitates continuous integration and delivery (CI/CD)**  
6. **Scalability**  
7. **Reusability**  

---
### When to Use Automated Testing

Not everything should be automated, however, test cases with complex manual scenarios and extensive data requirements are prime candidates for automation. A test case can and should be automated if the test is:

- **Repeatable.** The test must be one that can (and will) be repeated regularly. For instance, there is no point automating a test for a feature that is about to be deprecated  

<br>

- **Determinant.** There has to be a clear right and wrong outcome for the test. In other words, it must be easy for a computer to decide whether the test failed or not  

<br>

- **Repetitive or tedious.** As a rule, humans are very poor at repetitive tasks. Our minds wander or we get distracted. Automated testing is particularly advantageous for any test that involves repeatedly doing the same action, as it ensures consistent and accurate execution  

<br>

- **Business-Critical.** If a test is absolutely critical, you should try your best to automate it and schedule it to run regularly. That way, you can be certain this test is always being carried out  

---

### Automated Testing vs Manual Testing

A common misconception among those new to CI/CD is that automated testing negates the need for manual testing and for professional QA engineers.

While CI/CD automation frees up some time for QA team members, it does not make them redundant. Instead of spending time on repetitive tasks, QA engineers can focus on defining test cases, writing automated tests, and applying their creativity and ingenuity to exploratory testing.

There are a few types of tests that are hard to automate and are best to be done manually. These include tests that are constantly changing, once-off, or that are for features that are still evolving.

Below is a table summarizing the fundamental differences between both approaches to help determine the most suitable one for your specific requirements:
## References

- https://www.jetbrains.com/teamcity/ci-cd-guide/automated-testing/#where-does-testing-fit-into-the-ci-cd-process
- [Tech Target - A comprehensive test automation guide for IT teams](https://www.techtarget.com/searchsoftwarequality/definition/automated-software-testing)  
- [Test Dev Lab - What Is Automated Testing and How Does It Work? (with Example)](https://www.testdevlab.com/blog/automated-testing)  
- [Functionize - Automated testing](https://www.functionize.com/automated-testing)  
- [Smartbear - Automation Testing Guide](https://smartbear.com/learn/automated-testing/what-is-automated-testing/)  