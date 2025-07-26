# Lesson Plan: **Version Control & CI/CD**

---

## 1. Vocabulary & Terms

| Word/Phrase                             | Meaning                                                | Detailed Example Sentences                                                                                                        |
| --------------------------------------- | ------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------- |
| **Repository (repo)**                   | A storage location for code and project files          | *Our code is stored in a GitHub repository.* <br>*You can clone the repo to work locally.*                                        |
| **Branch**                              | A separate line of development in version control      | *I created a new branch for the payment feature.* <br>*Always switch to the correct branch before pushing changes.*               |
| **Commit**                              | A snapshot of changes made in code                     | *I made a commit with the latest bug fix.* <br>*Each commit should have a clear message.*                                         |
| **Push / Pull**                         | Sending or retrieving changes from the remote repo     | *I’ll push my changes after code review.* <br>*Don’t forget to pull the latest changes before merging.*                           |
| **Merge**                               | Combining changes from one branch into another         | *We need to merge the feature branch into the main branch.* <br>*The merge introduced some conflicts that need resolution.*       |
| **Tag / Release**                       | A marker for a specific version of the code            | *We tagged the release as v1.2.0.* <br>*Tags help identify stable versions of the software.*                                      |
| **CI (Continuous Integration)**         | Automated building & testing of code after each change | *Our CI pipeline runs tests on every commit.* <br>*If the CI fails, you need to fix the errors before merging.*                   |
| **CD (Continuous Delivery/Deployment)** | Automated process of releasing code to environments    | *We use CD to deploy changes automatically to staging.* <br>*Continuous deployment ensures faster releases.*                      |
| **Pipeline**                            | A sequence of automated steps (build, test, deploy)    | *The pipeline failed due to missing environment variables.* <br>*Our pipeline includes linting and unit tests.*                   |
| **Build failure**                       | When code cannot compile or pass tests                 | *The build failure was caused by a missing dependency.* <br>*Always check build logs to debug the issue.*                         |
| **Rollback**                            | Reverting to a previous stable version                 | *We had to rollback the deployment due to a critical bug.* <br>*Rollback is a quick way to recover from bad releases.*            |
| **Staging environment**                 | A pre-production environment for final testing         | *The new release is deployed to staging for QA testing.* <br>*We catch most issues in the staging environment before production.* |
| **Hotfix**                              | A quick fix for a critical production bug              | *We released a hotfix to patch the login issue in production.*                                                                    |
| **Cherry-pick**                         | Applying a specific commit from one branch to another  | *We cherry-picked the security patch into the main branch.*                                                                       |

---

## 2. Vocabulary Fill-in-the-Blank

1. The project code is hosted in a GitHub **\_\_\_\_\_\_\_\_\_\_**.
2. I created a new **\_\_\_\_\_\_\_\_\_\_** for the notification feature.
3. After making changes, don’t forget to **\_\_\_\_\_\_\_\_\_\_** your commits to the remote repo.
4. Before merging, always **\_\_\_\_\_\_\_\_\_\_** the latest updates from the main branch.
5. The deployment failed due to a **\_\_\_\_\_\_\_\_\_\_ failure** in the pipeline.
6. We tagged the new **\_\_\_\_\_\_\_\_\_\_** as v2.0.1 for production.
7. The **\_\_\_\_\_\_\_\_\_\_ pipeline** includes automated tests and linting.
8. The update caused issues, so we had to **\_\_\_\_\_\_\_\_\_\_** to the previous version.
9. QA is testing the app in the **\_\_\_\_\_\_\_\_\_\_ environment** before the final release.
10. A critical bug appeared in production, so we pushed a **\_\_\_\_\_\_\_\_\_\_** immediately.

---

## 3. Grammar Focus

### a) Present Perfect (common in version control context)

* *I have committed the changes.*
* *We have merged the feature branch.*
* *The CI pipeline has failed twice today.*

**Practice:**

1. I \_\_\_\_\_\_\_\_\_\_ (commit) the bug fix to the repository.
2. We \_\_\_\_\_\_\_\_\_\_ (merge) the feature branch into main.
3. The deployment \_\_\_\_\_\_\_\_\_\_ (fail) due to a missing configuration.
4. They \_\_\_\_\_\_\_\_\_\_ (push) the hotfix to production.
5. Our team \_\_\_\_\_\_\_\_\_\_ (set up) a new staging environment.

---

### b) First Conditional for CI/CD issues

* *If the pipeline fails, we will investigate the logs.*
* *If you forget to pull, there will be merge conflicts.*

**Practice:**

1. If you don’t pull the latest changes, you \_\_\_\_\_\_\_\_\_\_ (get) a merge conflict.
2. We \_\_\_\_\_\_\_\_\_\_ (rollback) the release if the bug appears again.
3. If the CI pipeline \_\_\_\_\_\_\_\_\_\_ (fail), we will stop the deployment.
4. The team will deploy automatically if the tests \_\_\_\_\_\_\_\_\_\_ (pass).
5. If you cherry-pick the wrong commit, it \_\_\_\_\_\_\_\_\_\_ (cause) new issues.

---

## 4. Role Play: CI/CD Deployment Discussion

### Teacher (Team Lead):

Hi Fikret, did you create a **branch** for the new feature?

### You (Fikret):

Yes, I created a feature branch called `feature/payment-integration`.

---

### Teacher:

Great! Did you **commit** and **push** your latest changes?

### You:

Yes, I have **pushed** all my changes. The **CI pipeline** ran successfully after the last commit.

---

### Teacher:

Good. We’re planning to deploy to the **staging environment**. Any risks?

### You:

There might be a risk of **merge conflicts** since another team is also working on related code. I’ll pull the latest changes before merging.

---

### Teacher:

Perfect. What’s the backup plan if the deployment causes issues?

### You:

We’ll monitor logs, and if necessary, we can **rollback** to the previous **tagged release**.

---

### Teacher:

And if there’s a critical bug in production?

### You:

We’ll prepare a **hotfix** branch and deploy it immediately.

---

## 5. Scenario Questions

1. What steps do you take before merging a branch into main?
2. How do you fix a **build failure** in the CI pipeline?
3. Why do we use a **staging environment** before production?
4. How do you handle **merge conflicts**?
5. When do you **rollback** a release?
6. What is the difference between **Continuous Integration** and **Continuous Deployment**?
7. Why is writing clear **commit messages** important?

---

## 6. Homework & Practice

* Write 5 sentences describing your **Git workflow** (branching, committing, merging).
* Record a 1-minute explanation: *What is CI/CD and why is it important?*
* Prepare a short dialogue simulating a **failed deployment discussion** with a teammate.

---

## 7. Additional Resources

* [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials)
* [What is CI/CD? – DevOps Guide](https://www.redhat.com/en/topics/devops/what-is-ci-cd)
* [Learn Git branching (Interactive tool)](https://learngitbranching.js.org/)

---

Bu dersle:
✅ Git ve version control terimlerini öğreneceksin
✅ CI/CD süreçlerinde kullanılan dili pratik edeceksin
✅ Merge, rollback, hotfix gibi senaryoları İngilizce anlatabileceksin
