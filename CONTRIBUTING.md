# Contributing to {PROJECT_NAME}

Firstly, we would like to thank you for taking the time to contribute!

The following is a set of guidelines for contributing to {PROJECT_NAME} and its packages, which are hosted on the [{PROJECT_NAME}](https://github.com/{PROJECT_NAME}) on GitHub. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

#### Table Of Contents

[Code of Conduct](#code-of-conduct)

[FAQs](#FAQs)

[What should I know before I get started?](#what-should-i-know-before-i-get-started)
  * [{PROJECT_NAME}](#{PROJECT_NAME})
  * [{PROJECT_NAME} Architecture](#architecture-decisions)

[How Can I Contribute?](#how-can-i-contribute)
  * [Reporting Bugs](#reporting-bugs)
  * [Suggesting Enhancements](#suggesting-enhancements)
  * [Your First Code Contribution](#your-first-code-contribution)
  * [Pull Requests](#pull-requests)

[Styleguides](#styleguides)
  * [Git Commit Messages](#git-commit-messages)

[Additional Notes](#additional-notes)
  * [Issue and Pull Request Labels](#issue-and-pull-request-labels)

## Code of Conduct

This project and everyone participating in it is governed by the [Digital Catapult Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [{PROJECT_NAME}@github.com](mailto:{PROJECT_NAME}@github.com).

## FAQs
We don't have any frequently asked questions yet.

## I don't want to read this whole thing I just have a question!!!

## What should I know before I get started?

### {PROJECT_NAME}

{PROJECT_NAME} is a small open source project &mdash; [{PROJECT_NAME}](https://github.com/{PROJECT_NAME}). When you initially consider contributing to {PROJECT_NAME}, this section should help you with doing so.

## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report for {PROJECT_NAME}. Following these guidelines helps maintainers and the community understand your report :pencil:, reproduce the behavior :computer: :computer:, and find related reports :mag_right:.

Before creating bug reports, please check [this list](#before-submitting-a-bug-report) as you might find out that you don't need to create one. When you are creating a bug report, please [include as many details as possible](#how-do-i-submit-a-good-bug-report). Fill out [the required template](https://github.com/{PROJECT_NAME}/.github/blob/master/.github/ISSUE_TEMPLATE/bug_report.md), the information it asks for helps us resolve issues faster.

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

#### Before Submitting A Bug Report

* **Perform a [cursory search](https://github.com/search?q=+is%3Aissue+user%3{PROJECT_NAME})** to see if the problem has already been reported. If it has **and the issue is still open**, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Bug Report?

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). Create an issue on that repository and provide the following information by filling in [the template](https://github.com/{PROJECT_NAME}/.github/blob/master/.github/ISSUE_TEMPLATE/bug_report.md).

Explain the problem and include additional details to help maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the exact steps which reproduce the problem** in as many details as possible. 
* **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
* **Explain which behavior you expected to see instead and why.**
* **Include screenshots and animated GIFs** which show you following the described steps and clearly demonstrate the problem. If you use the keyboard while following the steps, **record the GIF with the [this tool](https://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/Xaviju/byzanzUI) on Linux.
* **If you're reporting that {PROJECT_NAME} crashed**, include a crash report with a stack trace from the operating system. On macOS, the crash report will be available in `Console.app` under "Diagnostic and usage information" > "User diagnostic reports". Include the crash report in the issue in a [code block](https://help.github.com/articles/markdown-basics/#multiple-lines), a [file attachment](https://help.github.com/articles/file-attachments-on-issues-and-pull-requests/), or put it in a [gist](https://gist.github.com/) and provide link to that gist.
* **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem happened and share more information using the guidelines below.

Provide more context by answering these questions:

* **Did the problem start happening recently** (e.g. after updating to a new version of {PROJECT_NAME}) or was this always a problem?
* If the problem started happening recently, **can you reproduce the problem in an older version of {PROJECT_NAME}?** What's the most recent version in which the problem doesn't happen? You can checkout older versions of {PROJECT_NAME} from [the releases page](https://github.com/{PROJECT_NAME}/{PROJECT_NAME}/releases).
* **Can you reliably reproduce the issue?** If not, provide details about how often the problem happens and under which conditions it normally happens.

Include details about your configuration and environment:

* **Which version of {PROJECT_NAME} are you using?** You can get the exact version from the version attribute within package.json.
* **What's the name and version of the OS you've deployed {PROJECT_NAME} to**?
* **Are you running {PROJECT_NAME} in a virtual machine?** If so, which VM software are you using and which operating systems and versions are used for the host and the guest?

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for {PROJECT_NAME}, including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion :pencil: and find related suggestions :mag_right:.

Before creating enhancement suggestions, please check [this list](#before-submitting-an-enhancement-suggestion) as you might find out that you don't need to create one. When you are creating an enhancement suggestion, please [include as many details as possible](#how-do-i-submit-a-good-enhancement-suggestion). Fill in [the template](https://github.com/{PROJECT_NAME}/.github/blob/master/.github/ISSUE_TEMPLATE/feature_request.md), including the steps that you imagine you would take if the feature you're requesting existed.

#### Before Submitting An Enhancement Suggestion

* **Perform a [cursory search](https://github.com/search?q=+is%3Aissue+user%3A{PROJECT_NAME})** to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues](https://guides.github.com/features/issues/). Create an issue on that repository and provide the following information:

* **Use a clear and descriptive title** for the issue to identify the suggestion.
* **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
* **Provide specific examples to demonstrate the steps**. Include copy/pasteable snippets which you use in those examples, as [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
* **Include screenshots and animated GIFs** which help you demonstrate the steps or point out the part of {PROJECT_NAME} which the suggestion is related to. You can use [this tool](https://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux.
* **Explain why this enhancement would be useful** to most {PROJECT_NAME} users.
* **List some other text editors or applications where this enhancement exists.**
* **Specify which version of {PROJECT_NAME} you're using.** You can get the exact version from the version attribute within package.json.
* **What's the name and version of the OS you've deployed {PROJECT_NAME} to**?


### Your First Code Contribution

Unsure where to begin contributing to {PROJECT_NAME}? You can start by looking through these `beginner` and `help-wanted` issues:

* [Beginner issues][beginner] - issues which should only require a few lines of code, and a test or two.
* [Help wanted issues][help-wanted] - issues which should be a bit more involved than `beginner` issues.

Both issue lists are sorted by total number of comments. While not perfect, number of comments is a reasonable proxy for impact a given change will have.

### Pull Requests

The process described here has several goals:

- Maintain {PROJECT_NAME}'s quality
- Fix problems that are important to users
- Enable a sustainable system for {PROJECT_NAME}'s maintainers to review contributions

Please follow these steps to have your contribution considered by the maintainers:

1. Follow all instructions in [the template](PULL_REQUEST_TEMPLATE.md)
2. Follow the [styleguides](#styleguides)
3. After you submit your pull request, verify that all [status checks](https://help.github.com/articles/about-status-checks/) are passing <details><summary>What if the status checks are failing?</summary>If a status check is failing, and you believe that the failure is unrelated to your change, please leave a comment on the pull request explaining why you believe the failure is unrelated. A maintainer will re-run the status check for you. If we conclude that the failure was a false positive, then we will open an issue to track that problem with our status check suite.</details>

While the prerequisites above must be satisfied prior to having your pull request reviewed, the reviewer(s) may ask you to complete additional design work, tests, or other changes before your pull request can be ultimately accepted.

## Styleguides

### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line
* When only changing documentation, include `[ci skip]` in the commit title
* Consider starting the commit message with an applicable emoji:
    * :art: `:art:` when improving the format/structure of the code
    * :racehorse: `:racehorse:` when improving performance
    * :non-potable_water: `:non-potable_water:` when plugging memory leaks
    * :memo: `:memo:` when writing docs
    * :penguin: `:penguin:` when fixing something on Linux
    * :apple: `:apple:` when fixing something on macOS
    * :checkered_flag: `:checkered_flag:` when fixing something on Windows
    * :bug: `:bug:` when fixing a bug
    * :fire: `:fire:` when removing code or files
    * :green_heart: `:green_heart:` when fixing the CI build
    * :white_check_mark: `:white_check_mark:` when adding tests
    * :lock: `:lock:` when dealing with security
    * :arrow_up: `:arrow_up:` when upgrading dependencies
    * :arrow_down: `:arrow_down:` when downgrading dependencies
    * :shirt: `:shirt:` when removing linter warnings

## Additional Notes

### Issue and Pull Request Labels

This section lists the labels we use to help us track and manage issues and pull requests. Most labels are used across all {PROJECT_NAME} repositories, but some are specific to `{PROJECT_NAME}/{PROJECT_NAME_REPO}`.

[GitHub search](https://help.github.com/articles/searching-issues/) makes it easy to use labels for finding groups of issues or pull requests you're interested in. For example, you might be interested in [open issues across `{PROJECT_NAME}/{PROJECT_NAME_REPO}`. We  encourage you to read about [other search filters](https://help.github.com/articles/searching-issues/) which will help you write more focused queries.

The labels are loosely grouped by their purpose, but it's not required that every issue have a label from every group or that an issue can't have more than one label from the same group.

Please open an issue on `{PROJECT_NAME}/{PROJECT_NAME_REPO}` if you have suggestions for new labels, and if you notice some labels are missing on some repositories, then please open an issue on that repository.

#### Type of Issue and Issue State

| Label name | `{PROJECT_NAME}/{PROJECT_NAME_REPO}` :mag_right: | `{PROJECT_NAME}`‑org :mag_right: | Description |
| --- | --- | --- | --- |
| `enhancement` | [search][search-{PROJECT_NAME}-repo-label-enhancement] | [search][search-{PROJECT_NAME}-org-label-enhancement] | Feature requests. |
| `bug` | [search][search-{PROJECT_NAME}-repo-label-bug] | [search][search-{PROJECT_NAME}-org-label-bug] | Confirmed bugs or reports that are very likely to be bugs. |
| `question` | [search][search-{PROJECT_NAME}-repo-label-question] | [search][search-{PROJECT_NAME}-org-label-question] | Questions more than bug reports or feature requests (e.g. how do I do X). |
| `feedback` | [search][search-{PROJECT_NAME}-repo-label-feedback] | [search][search-{PROJECT_NAME}-org-label-feedback] | General feedback more than bug reports or feature requests. |
| `more-information-needed` | [search][search-{PROJECT_NAME}-repo-label-more-information-needed] | [search][search-{PROJECT_NAME}-org-label-more-information-needed] | More information needs to be collected about these problems or feature requests (e.g. steps to reproduce). |
| `needs-reproduction` | [search][search-{PROJECT_NAME}-repo-label-needs-reproduction] | [search][search-{PROJECT_NAME}-org-label-needs-reproduction] | Likely bugs, but haven't been reliably reproduced. |
| `blocked` | [search][search-{PROJECT_NAME}-repo-label-blocked] | [search][search-{PROJECT_NAME}-org-label-blocked] | Issues blocked on other issues. |
| `duplicate` | [search][search-{PROJECT_NAME}-repo-label-duplicate] | [search][search-{PROJECT_NAME}-org-label-duplicate] | Issues which are duplicates of other issues, i.e. they have been reported before. |
| `wontfix` | [search][search-{PROJECT_NAME}-repo-label-wontfix] | [search][search-{PROJECT_NAME}-org-label-wontfix] | The {PROJECT_NAME} core team has decided not to fix these issues for now, either because they're working as intended or for some other reason. |
| `invalid` | [search][search-{PROJECT_NAME}-repo-label-invalid] | [search][search-{PROJECT_NAME}-org-label-invalid] | Issues which aren't valid (e.g. user errors). |

#### Topic Categories

| Label name | `{PROJECT_NAME}/{PROJECT_NAME_REPO}` :mag_right: | `{PROJECT_NAME}`‑org :mag_right: | Description |
| --- | --- | --- | --- |
| `windows` | [search][search-{PROJECT_NAME}-repo-label-windows] | [search][search-{PROJECT_NAME}-org-label-windows] | Related to {PROJECT_NAME} running on Windows. |
| `linux` | [search][search-{PROJECT_NAME}-repo-label-linux] | [search][search-{PROJECT_NAME}-org-label-linux] | Related to {PROJECT_NAME} running on Linux. |
| `mac` | [search][search-{PROJECT_NAME}-repo-label-mac] | [search][search-{PROJECT_NAME}-org-label-mac] | Related to {PROJECT_NAME} running on macOS. |
| `documentation` | [search][search-{PROJECT_NAME}-repo-label-documentation] | [search][search-{PROJECT_NAME}-org-label-documentation] | Related to any type of documentation |
| `performance` | [search][search-{PROJECT_NAME}-repo-label-performance] | [search][search-{PROJECT_NAME}-org-label-performance] | Related to performance. |
| `security` | [search][search-{PROJECT_NAME}-repo-label-security] | [search][search-{PROJECT_NAME}-org-label-security] | Related to security. |
| `ui` | [search][search-{PROJECT_NAME}-repo-label-ui] | [search][search-{PROJECT_NAME}-org-label-ui] | Related to visual design. |
| `api` | [search][search-{PROJECT_NAME}-repo-label-api] | [search][search-{PROJECT_NAME}-org-label-api] | Related to {PROJECT_NAME}'s public APIs. |
| `uncaught-exception` | [search][search-{PROJECT_NAME}-repo-label-uncaught-exception] | [search][search-{PROJECT_NAME}-org-label-uncaught-exception] | Issues about uncaught exceptions |
| `crash` | [search][search-{PROJECT_NAME}-repo-label-crash] | [search][search-{PROJECT_NAME}-org-label-crash] | Reports of {PROJECT_NAME} completely crashing. |
| `auto-indent` | [search][search-{PROJECT_NAME}-repo-label-auto-indent] | [search][search-{PROJECT_NAME}-org-label-auto-indent] | Related to auto-indenting text. |
| `git` | [search][search-{PROJECT_NAME}-repo-label-git] | [search][search-{PROJECT_NAME}-org-label-git] | Related to Git functionality (e.g. problems with gitignore files or with showing the correct file status). |

#### `{PROJECT_NAME}/{PROJECT_NAME_REPO}` Topic Categories

| Label name | `{PROJECT_NAME}/{PROJECT_NAME_REPO}` :mag_right: | `{PROJECT_NAME}`‑org :mag_right: | Description |
| --- | --- | --- | --- |
| `build-error` | [search][search-{PROJECT_NAME}-repo-label-build-error] | [search][search-{PROJECT_NAME}-org-label-build-error] | Related to problems with building {PROJECT_NAME}. |
| `error-from-open` | [search][search-{PROJECT_NAME}-repo-label-error-from-open] | [search][search-{PROJECT_NAME}-org-label-error-from-open] | Related to errors thrown when opening files. |
| `deprecation-help` | [search][search-{PROJECT_NAME}-repo-label-deprecation-help] | [search][search-{PROJECT_NAME}-org-label-deprecation-help] | Issues for helping package authors remove usage of deprecated APIs in packages. |

#### Pull Request Labels

| Label name | `{PROJECT_NAME}/{PROJECT_NAME_REPO}` :mag_right: | `{PROJECT_NAME}`‑org :mag_right: | Description
| --- | --- | --- | --- |
| `work-in-progress` | [search][search-{PROJECT_NAME}-repo-label-work-in-progress] | [search][search-{PROJECT_NAME}-org-label-work-in-progress] | Pull requests which are still being worked on, more changes will follow. |
| `needs-review` | [search][search-{PROJECT_NAME}-repo-label-needs-review] | [search][search-{PROJECT_NAME}-org-label-needs-review] | Pull requests which need code review, and approval from maintainers or {PROJECT_NAME} core team. |
| `under-review` | [search][search-{PROJECT_NAME}-repo-label-under-review] | [search][search-{PROJECT_NAME}-org-label-under-review] | Pull requests being reviewed by maintainers or {PROJECT_NAME} core team. |
| `requires-changes` | [search][search-{PROJECT_NAME}-repo-label-requires-changes] | [search][search-{PROJECT_NAME}-org-label-requires-changes] | Pull requests which need to be updated based on review comments and then reviewed again. |
| `needs-testing` | [search][search-{PROJECT_NAME}-repo-label-needs-testing] | [search][search-{PROJECT_NAME}-org-label-needs-testing] | Pull requests which need manual testing. |

[search-{PROJECT_NAME}-repo-label-enhancement]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Aenhancement
[search-{PROJECT_NAME}-org-label-enhancement]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Aenhancement
[search-{PROJECT_NAME}-repo-label-bug]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Abug
[search-{PROJECT_NAME}-org-label-bug]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Abug
[search-{PROJECT_NAME}-repo-label-question]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Aquestion
[search-{PROJECT_NAME}-org-label-question]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Aquestion
[search-{PROJECT_NAME}-repo-label-feedback]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Afeedback
[search-{PROJECT_NAME}-org-label-feedback]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Afeedback
[search-{PROJECT_NAME}-repo-label-help-wanted]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Ahelp-wanted
[search-{PROJECT_NAME}-org-label-help-wanted]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Ahelp-wanted
[search-{PROJECT_NAME}-repo-label-beginner]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Abeginner
[search-{PROJECT_NAME}-org-label-beginner]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Abeginner
[search-{PROJECT_NAME}-repo-label-more-information-needed]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Amore-information-needed
[search-{PROJECT_NAME}-org-label-more-information-needed]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Amore-information-needed
[search-{PROJECT_NAME}-repo-label-needs-reproduction]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Aneeds-reproduction
[search-{PROJECT_NAME}-org-label-needs-reproduction]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Aneeds-reproduction
[search-{PROJECT_NAME}-repo-label-triage-help-needed]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Atriage-help-needed
[search-{PROJECT_NAME}-org-label-triage-help-needed]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Atriage-help-needed
[search-{PROJECT_NAME}-repo-label-windows]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Awindows
[search-{PROJECT_NAME}-org-label-windows]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Awindows
[search-{PROJECT_NAME}-repo-label-linux]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Alinux
[search-{PROJECT_NAME}-org-label-linux]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Alinux
[search-{PROJECT_NAME}-repo-label-mac]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Amac
[search-{PROJECT_NAME}-org-label-mac]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Amac
[search-{PROJECT_NAME}-repo-label-documentation]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Adocumentation
[search-{PROJECT_NAME}-org-label-documentation]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Adocumentation
[search-{PROJECT_NAME}-repo-label-performance]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Aperformance
[search-{PROJECT_NAME}-org-label-performance]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Aperformance
[search-{PROJECT_NAME}-repo-label-security]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Asecurity
[search-{PROJECT_NAME}-org-label-security]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Asecurity
[search-{PROJECT_NAME}-repo-label-ui]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Aui
[search-{PROJECT_NAME}-org-label-ui]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Aui
[search-{PROJECT_NAME}-repo-label-api]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Aapi
[search-{PROJECT_NAME}-org-label-api]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Aapi
[search-{PROJECT_NAME}-repo-label-crash]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Acrash
[search-{PROJECT_NAME}-org-label-crash]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Acrash
[search-{PROJECT_NAME}-repo-label-auto-indent]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Aauto-indent
[search-{PROJECT_NAME}-org-label-auto-indent]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Aauto-indent
[search-{PROJECT_NAME}-repo-label-encoding]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Aencoding
[search-{PROJECT_NAME}-org-label-encoding]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Aencoding
[search-{PROJECT_NAME}-repo-label-network]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Anetwork
[search-{PROJECT_NAME}-org-label-network]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Anetwork
[search-{PROJECT_NAME}-repo-label-uncaught-exception]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Auncaught-exception
[search-{PROJECT_NAME}-org-label-uncaught-exception]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Auncaught-exception
[search-{PROJECT_NAME}-repo-label-git]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Agit
[search-{PROJECT_NAME}-org-label-git]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Agit
[search-{PROJECT_NAME}-repo-label-blocked]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Ablocked
[search-{PROJECT_NAME}-org-label-blocked]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Ablocked
[search-{PROJECT_NAME}-repo-label-duplicate]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Aduplicate
[search-{PROJECT_NAME}-org-label-duplicate]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Aduplicate
[search-{PROJECT_NAME}-repo-label-wontfix]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Awontfix
[search-{PROJECT_NAME}-org-label-wontfix]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Awontfix
[search-{PROJECT_NAME}-repo-label-invalid]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Ainvalid
[search-{PROJECT_NAME}-org-label-invalid]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Ainvalid
[search-{PROJECT_NAME}-repo-label-package-idea]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Apackage-idea
[search-{PROJECT_NAME}-org-label-package-idea]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Apackage-idea
[search-{PROJECT_NAME}-repo-label-wrong-repo]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Awrong-repo
[search-{PROJECT_NAME}-org-label-wrong-repo]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Awrong-repo
[search-{PROJECT_NAME}-repo-label-editor-rendering]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Aeditor-rendering
[search-{PROJECT_NAME}-org-label-editor-rendering]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Aeditor-rendering
[search-{PROJECT_NAME}-repo-label-build-error]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Abuild-error
[search-{PROJECT_NAME}-org-label-build-error]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Abuild-error
[search-{PROJECT_NAME}-repo-label-error-from-pathwatcher]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Aerror-from-pathwatcher
[search-{PROJECT_NAME}-org-label-error-from-pathwatcher]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Aerror-from-pathwatcher
[search-{PROJECT_NAME}-repo-label-error-from-save]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Aerror-from-save
[search-{PROJECT_NAME}-org-label-error-from-save]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Aerror-from-save
[search-{PROJECT_NAME}-repo-label-error-from-open]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Aerror-from-open
[search-{PROJECT_NAME}-org-label-error-from-open]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Aerror-from-open
[search-{PROJECT_NAME}-repo-label-installer]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Ainstaller
[search-{PROJECT_NAME}-org-label-installer]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Ainstaller
[search-{PROJECT_NAME}-repo-label-auto-updater]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Aauto-updater
[search-{PROJECT_NAME}-org-label-auto-updater]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Aauto-updater
[search-{PROJECT_NAME}-repo-label-deprecation-help]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Adeprecation-help
[search-{PROJECT_NAME}-org-label-deprecation-help]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Adeprecation-help
[search-{PROJECT_NAME}-repo-label-electron]: https://github.com/search?q=is%3Aissue+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+is%3Aopen+label%3Aelectron
[search-{PROJECT_NAME}-org-label-electron]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{PROJECT_NAME}+label%3Aelectron
[search-{PROJECT_NAME}-repo-label-work-in-progress]: https://github.com/search?q=is%3Aopen+is%3Apr+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Awork-in-progress
[search-{PROJECT_NAME}-org-label-work-in-progress]: https://github.com/search?q=is%3Aopen+is%3Apr+user%3A{PROJECT_NAME}+label%3Awork-in-progress
[search-{PROJECT_NAME}-repo-label-needs-review]: https://github.com/search?q=is%3Aopen+is%3Apr+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Aneeds-review
[search-{PROJECT_NAME}-org-label-needs-review]: https://github.com/search?q=is%3Aopen+is%3Apr+user%3A{PROJECT_NAME}+label%3Aneeds-review
[search-{PROJECT_NAME}-repo-label-under-review]: https://github.com/search?q=is%3Aopen+is%3Apr+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Aunder-review
[search-{PROJECT_NAME}-org-label-under-review]: https://github.com/search?q=is%3Aopen+is%3Apr+user%3A{PROJECT_NAME}+label%3Aunder-review
[search-{PROJECT_NAME}-repo-label-requires-changes]: https://github.com/search?q=is%3Aopen+is%3Apr+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Arequires-changes
[search-{PROJECT_NAME}-org-label-requires-changes]: https://github.com/search?q=is%3Aopen+is%3Apr+user%3A{PROJECT_NAME}+label%3Arequires-changes
[search-{PROJECT_NAME}-repo-label-needs-testing]: https://github.com/search?q=is%3Aopen+is%3Apr+repo%3A{PROJECT_NAME}%2F{PROJECT_NAME}+label%3Aneeds-testing
[search-{PROJECT_NAME}-org-label-needs-testing]: https://github.com/search?q=is%3Aopen+is%3Apr+user%3A{PROJECT_NAME}+label%3Aneeds-testing

[beginner]:https://github.com/search?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+label%3Abeginner+label%3Ahelp-wanted+user%3A{PROJECT_NAME}+sort%3Acomments-desc
[help-wanted]:https://github.com/search?q=is%3Aopen+is%3Aissue+label%3Ahelp-wanted+user%3A{PROJECT_NAME}+sort%3Acomments-desc+-label%3Abeginner
