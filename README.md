# GitHub tips <a name="init"></a>

##How to collaborate on a project using GitHub in an easy way

| index |
| --- |
| [How to collaborate on a project](#colab) |
| [How to open an issue](#issue) |
| [Pull Requests](#pull) |
| [Pull Request. Repo is ahead to Master](#pull1) |
| [Pull Request. Master is ahead to Repo](#pull2) |
| [How to select from where and to where make the Pull Request](#fromto) |
| [Editing sources files](#edit) |
| [How to create a branch](#branch) |

[Go Top](#Top) [Init](#init)




---
## **`How to collaborate on a project`**<a name="colab"></a>

[Go Init](#init)

* Create an account on GitHub
* Go to the main GitHub page of the project.
* Click on button **Fork**
* In your GitHub Page you'll see the fork.
* Make a **branch** on your **Fork** [How to create a branch](#branch)
* Clone that **fork** on your local computer and start working on it.
* Editing the text files locally, and commit your changes using `Desktop GitHub`.
* Finally, you push those changes back into the branch of your colleague's repository.

Changes are in your **branch** but you want to send those changes to your colleague's repo. Then, send a **Pull Request** with the changes to your colleague's repo.

[Go Init](#init)




---
## **`How to open an issue`**<a name="issue"></a>

[Go Init](#init)

What to do when you want to report a bug or issue

---
### [1- Go to **Tab Issues -> New Issue**](https://github.com/asistex/ighoo/issues/new/choose)

[![image](https://github.com/asistex/github_tips/raw/main/btn_issue.jpg)](https://github.com/asistex/ighoo/issues/new/choose)

[Go Init](#init)

---
You have two options to make an issue - report in github or in the forum

### [2- click on **Get Started or Open**](https://github.com/asistex/ighoo/issues/new?assignees=&labels=&template=bug_report.md&title=)

[![image](https://github.com/asistex/github_tips/raw/main/get_started.jpg)](https://github.com/asistex/ighoo/issues/new?assignees=&labels=&template=bug_report.md&title=)

[Go Init](#init)

---
### [3- **Fill form**](https://github.com/asistex/ighoo/issues/new?assignees=&labels=&template=bug_report.md&title=)

Use the GitHub issue search — check if the issue has already been reported.

Check if the issue has been fixed — try to reproduce it using the latest master or development branch in the repository.

Add title (mandatory) and fill the form. **`Submit new issue`**

Isolate the problem — create a reduced test case and a live example.

A good bug report shouldn't leave others needing to chase you up for more information.

* Please try to be as detailed as possible in your report.
* What is your environment and OS?
* What steps will reproduce the issue?
* What would you expect to be the outcome?

All these details will help people to fix any potential bugs.

Short and descriptive example bug report title.

A summary of the issue and the OS environment in which it occurs. If suitable, include the steps required to reproduce the bug.

* This is the first step
* This is the second step
* Further steps, etc.
* a link to the reduced sample test
* Any other information you want to share that is relevant to the issue being reported. This might include the lines of code that you have identified as causing the bug, and potential solutions (and your opinions on their merits).

[![image](https://github.com/asistex/github_tips/raw/main/fill_form.jpg)](https://github.com/asistex/ighoo/issues/new?assignees=&labels=&template=bug_report.md&title=)

[Go Init](#init)




---

## **`Pull Requests`** <a name="pull"></a>

[Go Init](#init)

**Pull Request**, patches, improvements, new features are a fantastic help.

Please ask first on the forum before embarking on any significant pull request.

Your pull requests are welcome; however, they may not be accepted for various reasons.

All **Pull Requests** need to be attached to a **issue** on GitHub. For **Pull Requests** regarding enhancements and questions, the issue must first be approved by one of project's administrators before being merged into the project. An approved issue will have the label **`Accepted`**. For issues that have not been accepted, you may request to be assigned to that issue.

`Opening a issue beforehand allows the administrators and the community to discuss bugs and enhancements before work begins, preventing wasted effort.`

### Guidelines for pull requests

1. Respect coding style.
2. Create a new branch for each **Pull Request**. [How to create a branch](#branch)
3. Single feature or bug-fix per **Pull Request**.
4. Make single commit per **Pull Request**.
5. Make your modification compact - don't reformat source code in your request. It makes code review more difficult.
6. Warn to the group if the **Pull Request** broke `backward compatibility`

In short: The easier the code review is, the better the chance your pull request will get accepted.


**IMPORTANT: By submitting a patch, you agree to allow the project owner to license your work under the same license as that used by the project.**


[Go Init](#init)




---

## **`Pull Request. Your Repo is ahead to Master`**<a name="pull1"></a>

[Go Top](#Top) [Init](#init)

What to do when you made changes in your fork and you want to add them to the master.

[![image](https://github.com/asistex/github_tips/raw/main/pr1.jpg)](https://github.com/asistex/ighoo/issues/new?assignees=&labels=&template=bug_report.md&title=)

[**How to select from where and to where make the pull request**](#fromto)

[Go Init](#init)




---

## **` Pull Request. Your Repo is behind to Master`**<a name="pull2"></a>

[Go Init](#init)

What to do when you want to add to your fork the changes in the master.

[![image](https://github.com/asistex/github_tips/raw/main/pr2.jpg)](https://github.com/asistex/ighoo/issues/new?assignees=&labels=&template=bug_report.md&title=)

[**How to select from where and to where make the pull request**](#fromto)

[Go Init](#init)




---

## **`Editing sources files`**<a name="edit"></a>

[Go Init](#init)

    Make sure to use the same coding / formatting style as you find in the files you're modifying. The easiest way to achieve this is to use these commands to format the sources (use this with care - most existing sources are well-formatted, so make sure to only apply it to newly added or modified code sections)

      $ uncrustify -c <hmg-dir>/bin/hmg.ucf <source{.c|.h}>
      $ <hmg-dir>/bin/hbformat <source{.prg|.hb|.ch}>

    Text editor setting for sources files
        Encoding is either 7-bit ASCII or UTF-8, without BOM.
        Use spaces, never tabs.
        Remove trailing spaces from lines.
        Keep one (not zero or multiple) newline at the end of file.
        Use return newline CRLF.

[Go Init](#init)




---

## **`How to create a branch`**<a name="branch"></a>

### Click on **button master**

From this window you can select the branch to work or create a new one.

Type on `Find or create a branch..` the name of a new branch.

**`Make sure your branch name wasn't used before`** - you can add date (for example `branch_20201120`) to ensure its uniqueness.

[![image](https://github.com/asistex/github_tips/raw/main/btn_branch.jpg)]())


[Go Init](#init)





## **`How to select from where and to where make the **pull request**`**<a name="fromto"></a>

[Go Init](#init)

To make a **Pull Request** click on button `Pull Request`

[![image](https://github.com/asistex/github_tips/raw/main/btn_pr.jpg)]()

Now you'll see something like this:

[![image](https://github.com/asistex/github_tips/raw/main/compare3.jpg)]()

And with the link **`Compare across forks`** you can select from and where to make the **Pull Request**.

Take a look at the arrow. So in this case:

[![image](https://github.com/asistex/github_tips/raw/main/compare4.jpg)]()

You'll gonna
```
   update fork

   `asistex/hmg` branch `master`

   from

   HMG-Official/HMG` branch `master`
```

Click on **`Compare across forks`** to change

    **base repository**:  and  **base**:branch
    **head repository**:  and  **compare**:branch

After you are sure about what to do, you'll see a list of files changed with the diff in red and green. Check it and then click on **Create a Pull Request**

After that:

Fill the title and the form with info about pull request and click on **Create a Pull Request**

If you are making a pull request to another fork then all was done.

If you are updating your fork from another fork then click on **Merge pull request** and
**Confirm merge**

[Go Init](#init)




---
This document Copyright &copy;&nbsp;2020&ndash;present [asistex](https://github.com/asistex/)<br>
[![Creative Commons Attribution-ShareAlike 4.0](https://mirrors.creativecommons.org/presskit/buttons/80x15/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)






















