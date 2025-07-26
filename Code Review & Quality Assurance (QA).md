# Lesson Plan: Code Review & Quality Assurance (QA)

---

## 1. Vocabulary & Terms

| Word/Phrase              | Meaning                                                  | Detailed Example Sentences                                                                                              |
| ------------------------ | -------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| **Pull request (PR)**    | A request to merge code changes into the main branch     | *I created a pull request for the new feature.* <br>*The pull request needs at least two approvals before merging.*     |
| **Merge conflict**       | When two code changes are incompatible                   | *There’s a merge conflict in the authentication module.* <br>*We need to resolve merge conflicts before deployment.*    |
| **Code smell**           | A sign that code might need refactoring                  | *This long function is a code smell that should be refactored.* <br>*Code smells indicate potential design issues.*     |
| **Static analysis**      | Automated code checking for style & errors               | *Static analysis tools caught unused variables.* <br>*We use ESLint for static analysis before committing code.*        |
| **Linting**              | Checking code style and formatting                       | *Linting errors need to be fixed before merging the branch.* <br>*Our CI pipeline fails if linting rules are violated.* |
| **Test coverage**        | Percentage of code tested by automated tests             | *Our test coverage improved to 85% this sprint.* <br>*High test coverage reduces the risk of bugs in production.*       |
| **Regression**           | A bug that reappears after a fix or new change           | *The latest update caused a regression in the login flow.* <br>*Regression testing ensures old features still work.*    |
| **Unit test**            | A test for a small part of the code                      | *We wrote unit tests for the utility functions.* <br>*Unit tests help detect small issues early.*                       |
| **Integration test**     | A test for how different modules work together           | *Integration tests check if frontend and backend communicate correctly.*                                                |
| **QA environment**       | A separate environment for testing before production     | *The new release is deployed to the QA environment for testing.* <br>*QA environments help catch issues early.*         |
| **Code review comments** | Feedback given during code review                        | *I left a few code review comments about naming conventions.* <br>*Clear comments make code reviews more effective.*    |
| **Approval**             | Permission to merge a PR after review                    | *The PR is waiting for final approval.* <br>*Once it’s approved, we can deploy the changes.*                            |
| **CI pipeline**          | Continuous Integration process for building/testing code | *The CI pipeline failed due to a missing dependency.* <br>*A green CI pipeline means all tests passed successfully.*    |
| **Bug report**           | A document explaining a found bug                        | *Please create a detailed bug report for the QA team.* <br>*Bug reports should include steps to reproduce the issue.*   |
| **Refactoring**          | Improving code without changing functionality            | *We need to refactor this messy function for better readability.* <br>*Refactoring helps reduce technical debt.*        |

---

## 2. Vocabulary Fill-in-the-Blank

1. I just created a **\_\_\_\_\_\_\_\_\_\_** for the new authentication feature.
2. We can’t merge this branch because there’s a **\_\_\_\_\_\_\_\_\_\_** in the database module.
3. The overly long function is a **\_\_\_\_\_\_\_\_\_\_** that should be improved.
4. **\_\_\_\_\_\_\_\_\_\_** tools like ESLint help maintain consistent code style.
5. After adding new features, we must do **\_\_\_\_\_\_\_\_\_\_ testing** to ensure old bugs don’t return.
6. Our **\_\_\_\_\_\_\_\_\_\_ coverage** increased from 70% to 85% after adding more tests.
7. Before production, all new builds are deployed to the **\_\_\_\_\_\_\_\_\_\_ environment**.
8. The CI **\_\_\_\_\_\_\_\_\_\_** failed because a test didn’t pass.
9. I left some **\_\_\_\_\_\_\_\_\_\_ comments** to suggest better variable names.
10. This task requires **\_\_\_\_\_\_\_\_\_\_**, as the code is hard to read but still works.

---

## 3. Grammar Focus

### a) Passive Voice (common in code review & QA reports)

* *The pull request was approved by the senior developer.*
* *The code is being reviewed right now.*
* *The bug was found during regression testing.*

**Practice:**

1. The PR (approve) by the team lead yesterday.
2. Linting errors (catch) by the CI pipeline.
3. The QA tests (run) in the staging environment.
4. Merge conflicts (resolve) before deployment.
5. The code (refactor) to improve readability.

---

### b) Modal Verbs for Suggestions

* *You **should** split this function into smaller parts.*
* *We **could** add more integration tests for better coverage.*
* *You **might want to** rename this variable for clarity.*

**Practice:**

1. You \_\_\_\_\_\_\_\_\_\_ improve test coverage for critical functions.
2. We \_\_\_\_\_\_\_\_\_\_ consider using a static analysis tool.
3. You \_\_\_\_\_\_\_\_\_\_ refactor this class to make it cleaner.
4. Maybe we \_\_\_\_\_\_\_\_\_\_ add a unit test for this function.
5. You \_\_\_\_\_\_\_\_\_\_ avoid pushing directly to the main branch.

---

## 4. Role Play: Code Review Meeting

### Teacher (Reviewer):

Hi Fikret, I reviewed your pull request. Could you explain why you used such a large function for the API response?

### You (Fikret):

Yes, I understand it’s quite long. I prioritized functionality first. But I agree it’s a **code smell**, so I plan to **refactor** it into smaller functions.

---

### Teacher:

Good idea. Also, I noticed there’s a **merge conflict** in the routes file. Have you resolved it?

### You:

Not yet. I’ll **resolve the merge conflict** after pulling the latest changes from the main branch.

---

### Teacher:

Great. And about testing, I saw only a few **unit tests**. Could we improve the **test coverage**?

### You:

Absolutely. I’ll add more **integration tests** to cover the edge cases. I’ll also run **regression tests** to ensure no existing features break.

---

### Teacher:

Perfect. Once you finish these changes, let me know. After that, we can give the **approval** to merge.

### You:

Will do! I’ll also double-check the **linting** errors before pushing again.

---

## 5. Scenario Questions

1. How do you handle a **merge conflict** in your branch?
2. When would you suggest **refactoring** code?
3. What’s the difference between **unit tests** and **integration tests**?
4. How do you ensure no **regressions** after adding new features?
5. Why is **static analysis** useful in a CI pipeline?
6. What’s your process when a **CI pipeline** fails?
7. How do you write effective **code review comments**?
8. What’s the purpose of a **QA environment** before production?

---

## 6. Homework & Practice

* Write 5 sentences describing a recent **code review** you participated in.
* Create a short **bug report** (real or imaginary) explaining the issue, steps to reproduce, and expected behavior.
* Record a **2-minute explanation** of why **test coverage** is important in software development.

---

## 7. Additional Resources

* [Google Code Review Best Practices](https://google.github.io/eng-practices/review/)
* [QA Testing Types Explained](https://www.guru99.com/types-of-software-testing.html)
* [Static Analysis Tools for Developers](https://eslint.org/)
