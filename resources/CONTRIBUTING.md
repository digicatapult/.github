# Contributing to {project_module_name}

Firstly, we would like to thank you for taking the time to contribute!

The following is a set of guidelines for contributing to {project_name} and its packages, which are hosted on the [digicatapult](https://github.com/digicatapult) organisation on GitHub. These are mostly guidelines, not rules. Use your best judgement, and feel free to propose changes to this document in a pull request.

#### Table Of Contents

[Code of Conduct](#code-of-conduct)

[FAQs](#FAQs)

[How Can I Contribute?](#how-can-i-contribute)

- [Reporting Bugs](#reporting-bugs)
- [Suggesting Enhancements](#suggesting-enhancements)
- [Your First Code Contribution](#your-first-code-contribution)
- [Pull Requests](#pull-requests)

[Styleguides](#styleguides)

- [Git Commit Messages](#git-commit-messages)

[Additional Notes](#additional-notes)

- [Issue and Pull Request Labels](#issue-and-pull-request-labels)

## Code of Conduct

This project and all those participating in it are governed by the [Digital Catapult's Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behaviour to [opensource@digicatapult.org.uk](mailto:opensource@digicatapult.org.uk?subject={project_name}).

## FAQs

We don't have any frequently asked questions yet.

## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report for {project_module_name}. Following these guidelines helps maintainers and the community understand your report :pencil:, reproduce the behaviour :computer: :computer:, and find related reports :mag_right:.

Before creating bug reports, please check [this list](#before-submitting-a-bug-report) as you might find out that you don't need to create one. When you are creating a bug report, please [include as many details as possible](#how-do-i-submit-a-good-bug-report). Fill out [the required template](https://github.com/digicatapult/{project_module_name}/blob/master/.github/ISSUE_TEMPLATE/bug_report.md), the information it asks for helps us resolve issues faster.

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

#### Before Submitting A Bug Report

- **Perform a [cursory search](https://github.com/search?q=+is%3Aissue+user%3A{project_module_name})** to see if the problem has already been reported. If it has **and the issue is still open**, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Bug Report?

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). Create an issue on that repository and provide the following information by filling in [the template](https://github.com/digicatapult/{project_module_name}/.github/blob/master/.github/ISSUE_TEMPLATE/bug_report.md).

Explain the problem and include additional details to help maintainers reproduce the problem:

- **Use a clear and descriptive title** for the issue to identify the problem.
- **Describe the exact steps which reproduce the problem** in as many details as possible.
- **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
- **Describe the behaviour you observed after following the steps** and point out what exactly is the problem with that behaviour.
- **Explain which behaviour you expected to see instead and why.**
- **Include screenshots and animated GIFs** which show you following the described steps and clearly demonstrate the problem. If you use the keyboard while following the steps, \*\*record the GIF with the [this tool](https://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/Xaviju/byzanzUI) on Linux.
- **If you're reporting that {project_module_name} crashed**, include a crash report with a stack trace from the operating system. On macOS, the crash report will be available in `Console.app` under "Diagnostic and usage information" > "User diagnostic reports". Include the crash report in the issue in a [code block](https://help.github.com/articles/markdown-basics/#multiple-lines), a [file attachment](https://help.github.com/articles/file-attachments-on-issues-and-pull-requests/), or put it in a [gist](https://gist.github.com/) and provide link to that gist.
- **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem happened and share more information using the guidelines below.

Provide more context by answering these questions:

- **Did the problem start happening recently** (e.g. after updating to a new version of {project_module_name}) or was this always a problem?
- If the problem started happening recently, **can you reproduce the problem in an older version of {project_module_name}?** What's the most recent version in which the problem doesn't happen? You can checkout older versions of {project_module_name} from [the releases page](https://github.com/digicatapult/{project_module_name}/releases).
- **Can you reliably reproduce the issue?** If not, provide details about how often the problem happens and under which conditions it normally happens.

Include details about your configuration and environment:

- **Which version of {project_module_name} are you using?** You can get the exact version from the version attribute within package.json.
- **What's the name and version of the OS you've deployed {project_module_name} to**?
- **Are you running {project_module_name} in a virtual machine?** If so, which VM software are you using and which operating systems and versions are used for the host and the guest?

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for {project_module_name}, including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion :pencil: and find related suggestions :mag_right:.

Before creating enhancement suggestions, please check [this list](#before-submitting-an-enhancement-suggestion) as you might find out that you don't need to create one. When you are creating an enhancement suggestion, please [include as many details as possible](#how-do-i-submit-a-good-enhancement-suggestion). Fill in [the template](https://github.com/digicatapult/{project_module_name}/blob/master/.github/ISSUE_TEMPLATE/feature_request.md), including the steps that you imagine you would take if the feature you're requesting existed.

#### Before Submitting An Enhancement Suggestion

- **Perform a [cursory search](https://github.com/search?q=+is%3Aissue+user%3A{project_module_name})** to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues](https://guides.github.com/features/issues/). Create an issue on that repository and provide the following information:

- **Use a clear and descriptive title** for the issue to identify the suggestion.
- **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
- **Provide specific examples to demonstrate the steps**. Include copy/pasteable snippets which you use in those examples, as [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
- **Describe the current behaviour** and **explain which behaviour you expected to see instead** and why.
- **Include screenshots and animated GIFs** which help you demonstrate the steps or point out the part of {project_module_name} which the suggestion is related to. You can use [this tool](https://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux.
- **Explain why this enhancement would be useful** to most {project_module_name} users.
- **List some other text editors or applications where this enhancement exists.**
- **Specify which version of {project_module_name} you're using.** You can get the exact version from the version attribute within package.json.
- **What's the name and version of the OS you've deployed {project_module_name} to**?

### Your First Code Contribution

Unsure where to begin contributing to {project_module_name}? You can start by looking through these `beginner` and `help-wanted` issues:

- [Beginner issues][beginner] - issues which should only require a few lines of code, and a test or two.
- [Help wanted issues][help-wanted] - issues which should be a bit more involved than `beginner` issues.

Both issue lists are sorted by total number of comments. While not perfect, number of comments is a reasonable proxy for impact a given change will have.

### Pull Requests

The process described here has several goals:

- Maintain {project_module_name}'s quality
- Fix problems that are important to users
- Enable a sustainable system for {project_module_name}'s maintainers to review contributions

Please follow these steps to have your contribution considered by the maintainers:

1. Follow all instructions in [the template](.github/PULL_REQUEST_TEMPLATE.md)
2. Follow the [styleguides](#styleguides)
3. After you submit your pull request, verify that all [status checks](https://help.github.com/articles/about-status-checks/) are passing <details><summary>What if the status checks are failing?</summary>If a status check is failing, and you believe that the failure is unrelated to your change, please leave a comment on the pull request explaining why you believe the failure is unrelated. A maintainer will re-run the status check for you. If we conclude that the failure was a false positive, then we will open an issue to track that problem with our status check suite.</details>

While the prerequisites above must be satisfied prior to having your pull request reviewed, the reviewer(s) may ask you to complete additional design work, tests, or other changes before your pull request can be ultimately accepted.

## Styleguides

### Git Commit Messages

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line
- When only changing documentation, include `[ci skip]` in the commit title
- Consider starting the commit message with an applicable emoji:
  - :art: `:art:` when improving the format/structure of the code
  - :racehorse: `:racehorse:` when improving performance
  - :non-potable_water: `:non-potable_water:` when plugging memory leaks
  - :memo: `:memo:` when writing docs
  - :penguin: `:penguin:` when fixing something on Linux
  - :apple: `:apple:` when fixing something on macOS
  - :checkered_flag: `:checkered_flag:` when fixing something on Windows
  - :bug: `:bug:` when fixing a bug
  - :fire: `:fire:` when removing code or files
  - :green_heart: `:green_heart:` when fixing the CI build
  - :white_check_mark: `:white_check_mark:` when adding tests
  - :lock: `:lock:` when dealing with security
  - :arrow_up: `:arrow_up:` when upgrading dependencies
  - :arrow_down: `:arrow_down:` when downgrading dependencies
  - :shirt: `:shirt:` when removing linter warnings

## Additional Notes

### Issue and Pull Request Labels

This section lists the labels we use to help us track and manage issues and pull requests. Most labels are used across all {project_name} repositories, but some are specific to `{project_module_name}`.

[GitHub search](https://help.github.com/articles/searching-issues/) makes it easy to use labels for finding groups of issues or pull requests you're interested in. For example, you might be interested in open issues across `{project_module_name}`. We encourage you to read about [other search filters](https://help.github.com/articles/searching-issues/) which will help you write more focused queries.

The labels are loosely grouped by their purpose, but it's not required that every issue have a label from every group or that an issue can't have more than one label from the same group.

Please open an issue on `{project_module_name}` if you have suggestions for new labels, and if you notice some labels are missing on some repositories, then please open an issue on that repository.

#### Type of Issue and Issue State

| Label name                | `{project_module_name}` :mag_right:                                  | `{project_name}` :mag_right:                                  | Description                                                                                                                                           |
| ------------------------- | -------------------------------------------------------------------- | ------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| `enhancement`             | [search][search-{project_module_name}-label-enhancement]             | [search][search-{project_name}-label-enhancement]             | Feature requests.                                                                                                                                     |
| `bug`                     | [search][search-{project_module_name}-label-bug]                     | [search][search-{project_name}-label-bug]                     | Confirmed bugs or reports that are very likely to be bugs.                                                                                            |
| `question`                | [search][search-{project_module_name}-label-question]                | [search][search-{project_name}-label-question]                | Questions more than bug reports or feature requests (e.g. how do I do X).                                                                             |
| `feedback`                | [search][search-{project_module_name}-label-feedback]                | [search][search-{project_name}-label-feedback]                | General feedback more than bug reports or feature requests.                                                                                           |
| `more-information-needed` | [search][search-{project_module_name}-label-more-information-needed] | [search][search-{project_name}-label-more-information-needed] | More information needs to be collected about these problems or feature requests (e.g. steps to reproduce).                                            |
| `needs-reproduction`      | [search][search-{project_module_name}-label-needs-reproduction]      | [search][search-{project_name}-label-needs-reproduction]      | Likely bugs, but haven't been reliably reproduced.                                                                                                    |
| `blocked`                 | [search][search-{project_module_name}-label-blocked]                 | [search][search-{project_name}-label-blocked]                 | Issues blocked on other issues.                                                                                                                       |
| `duplicate`               | [search][search-{project_module_name}-label-duplicate]               | [search][search-{project_name}-label-duplicate]               | Issues which are duplicates of other issues, i.e. they have been reported before.                                                                     |
| `wontfix`                 | [search][search-{project_module_name}-label-wontfix]                 | [search][search-{project_name}-label-wontfix]                 | The {project_module_name} core team has decided not to fix these issues for now, either because they're working as intended or for some other reason. |
| `invalid`                 | [search][search-{project_module_name}-label-invalid]                 | [search][search-{project_name}-label-invalid]                 | Issues which aren't valid (e.g. user errors).                                                                                                         |

#### Topic Categories

| Label name           | `{project_module_name}` :mag_right:                             | `{project_name}` :mag_right:                             | Description                                                                                                |
| -------------------- | --------------------------------------------------------------- | -------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| `windows`            | [search][search-{project_module_name}-label-windows]            | [search][search-{project_name}-label-windows]            | Related to {project_module_name} running on Windows.                                                       |
| `linux`              | [search][search-{project_module_name}-label-linux]              | [search][search-{project_name}-label-linux]              | Related to {project_module_name} running on Linux.                                                         |
| `mac`                | [search][search-{project_module_name}-label-mac]                | [search][search-{project_name}-label-mac]                | Related to {project_module_name} running on macOS.                                                         |
| `documentation`      | [search][search-{project_module_name}-label-documentation]      | [search][search-{project_name}-label-documentation]      | Related to any type of documentation                                                                       |
| `performance`        | [search][search-{project_module_name}-label-performance]        | [search][search-{project_name}-label-performance]        | Related to performance.                                                                                    |
| `security`           | [search][search-{project_module_name}-label-security]           | [search][search-{project_name}-label-security]           | Related to security.                                                                                       |
| `ui`                 | [search][search-{project_module_name}-label-ui]                 | [search][search-{project_name}-label-ui]                 | Related to visual design.                                                                                  |
| `api`                | [search][search-{project_module_name}-label-api]                | [search][search-{project_name}-label-api]                | Related to {project_module_name}'s public APIs.                                                            |
| `uncaught-exception` | [search][search-{project_module_name}-label-uncaught-exception] | [search][search-{project_name}-label-uncaught-exception] | Issues about uncaught exceptions                                                                           |
| `crash`              | [search][search-{project_module_name}-label-crash]              | [search][search-{project_name}-label-crash]              | Reports of {project_module_name} completely crashing.                                                      |
| `git`                | [search][search-{project_module_name}-label-git]                | [search][search-{project_name}-label-git]                | Related to Git functionality (e.g. problems with gitignore files or with showing the correct file status). |

#### `{project_module_name}` Topic Categories

| Label name      | `{project_module_name}` :mag_right:                        | `PROJECT_NAME` :mag_right:                          | Description                                               |
| --------------- | ---------------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------------- |
| `build-error`   | [search][search-{project_module_name}-label-build-error]   | [search][search-{project_name}-label-build-error]   | Related to problems with building {project_module_name}.  |
| `start-error`   | [search][search-{project_module_name}-label-start-error]   | [search][search-{project_name}-label-start-error]   | Related to problems with starting {project_module_name}.  |
| `runtime-error` | [search][search-{project_module_name}-label-runtime-error] | [search][search-{project_name}-label-runtime-error] | Related to problems whilst running {project_module_name}. |

#### Pull Request Labels

| Label name         | `PROJECT_MODULE_NAME` :mag_right:                             | `PROJECT_NAME` :mag_right:                             | Description                                                                                             |
| ------------------ | ------------------------------------------------------------- | ------------------------------------------------------ | ------------------------------------------------------------------------------------------------------- |
| `work-in-progress` | [search][search-{project_module_name}-label-work-in-progress] | [search][search-{project_name}-label-work-in-progress] | Pull requests which are still being worked on, more changes will follow.                                |
| `needs-review`     | [search][search-{project_module_name}-label-needs-review]     | [search][search-{project_name}-label-needs-review]     | Pull requests which need code review, and approval from maintainers or {project_module_name} core team. |
| `under-review`     | [search][search-{project_module_name}-label-under-review]     | [search][search-{project_name}-label-under-review]     | Pull requests being reviewed by maintainers or {project_module_name} core team.                         |
| `requires-changes` | [search][search-{project_module_name}-label-requires-changes] | [search][search-{project_name}-label-requires-changes] | Pull requests which need to be updated based on review comments and then reviewed again.                |
| `needs-testing`    | [search][search-{project_module_name}-label-needs-testing]    | [search][search-{project_name}-label-needs-testing]    | Pull requests which need manual testing.                                                                |

[search-{project_module_name}-label-enhancement]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Aenhancement
[search-{project_name}-label-enhancement]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Aenhancement
[search-{project_module_name}-label-bug]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Abug
[search-{project_name}-label-bug]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Abug
[search-{project_module_name}-label-question]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Aquestion
[search-{project_name}-label-question]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Aquestion
[search-{project_module_name}-label-feedback]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Afeedback
[search-{project_name}-label-feedback]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Afeedback
[search-{project_module_name}-label-help-wanted]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Ahelp-wanted
[search-{project_name}-label-help-wanted]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Ahelp-wanted
[search-{project_module_name}-label-beginner]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Abeginner
[search-{project_name}-label-beginner]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Abeginner
[search-{project_module_name}-label-more-information-needed]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Amore-information-needed
[search-{project_name}-label-more-information-needed]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Amore-information-needed
[search-{project_module_name}-label-needs-reproduction]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Aneeds-reproduction
[search-{project_name}-label-needs-reproduction]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Aneeds-reproduction
[search-{project_module_name}-label-triage-help-needed]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Atriage-help-needed
[search-{project_name}-label-triage-help-needed]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Atriage-help-needed
[search-{project_module_name}-label-windows]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Awindows
[search-{project_name}-label-windows]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Awindows
[search-{project_module_name}-label-linux]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Alinux
[search-{project_name}-label-linux]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Alinux
[search-{project_module_name}-label-mac]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Amac
[search-{project_name}-label-mac]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Amac
[search-{project_module_name}-label-documentation]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Adocumentation
[search-{project_name}-label-documentation]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Adocumentation
[search-{project_module_name}-label-performance]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Aperformance
[search-{project_name}-label-performance]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Aperformance
[search-{project_module_name}-label-security]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Asecurity
[search-{project_name}-label-security]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Asecurity
[search-{project_module_name}-label-ui]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Aui
[search-{project_name}-label-ui]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Aui
[search-{project_module_name}-label-api]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Aapi
[search-{project_name}-label-api]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Aapi
[search-{project_module_name}-label-crash]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Acrash
[search-{project_name}-label-crash]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Acrash
[search-{project_module_name}-label-auto-indent]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Aauto-indent
[search-{project_name}-label-auto-indent]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Aauto-indent
[search-{project_module_name}-label-encoding]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Aencoding
[search-{project_name}-label-encoding]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Aencoding
[search-{project_module_name}-label-network]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Anetwork
[search-{project_name}-label-network]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Anetwork
[search-{project_module_name}-label-uncaught-exception]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Auncaught-exception
[search-{project_name}-label-uncaught-exception]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Auncaught-exception
[search-{project_module_name}-label-git]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Agit
[search-{project_name}-label-git]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Agit
[search-{project_module_name}-label-blocked]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Ablocked
[search-{project_name}-label-blocked]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Ablocked
[search-{project_module_name}-label-duplicate]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Aduplicate
[search-{project_name}-label-duplicate]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Aduplicate
[search-{project_module_name}-label-wontfix]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Awontfix
[search-{project_name}-label-wontfix]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Awontfix
[search-{project_module_name}-label-invalid]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Ainvalid
[search-{project_name}-label-invalid]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Ainvalid
[search-{project_module_name}-label-package-idea]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Apackage-idea
[search-{project_name}-label-package-idea]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Apackage-idea
[search-{project_module_name}-label-wrong-repo]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Awrong-repo
[search-{project_name}-label-wrong-repo]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Awrong-repo
[search-{project_module_name}-label-editor-rendering]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Aeditor-rendering
[search-{project_name}-label-editor-rendering]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Aeditor-rendering
[search-{project_module_name}-label-build-error]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Abuild-error
[search-{project_name}-label-build-error]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Abuild-error
[search-{project_module_name}-label-error-from-pathwatcher]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Aerror-from-pathwatcher
[search-{project_name}-label-error-from-pathwatcher]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Aerror-from-pathwatcher
[search-{project_module_name}-label-error-from-save]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Aerror-from-save
[search-{project_name}-label-error-from-save]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Aerror-from-save
[search-{project_module_name}-label-error-from-open]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Aerror-from-open
[search-{project_name}-label-error-from-open]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Aerror-from-open
[search-{project_module_name}-label-installer]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Ainstaller
[search-{project_name}-label-installer]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Ainstaller
[search-{project_module_name}-label-auto-updater]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Aauto-updater
[search-{project_name}-label-auto-updater]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Aauto-updater
[search-{project_module_name}-label-deprecation-help]: https://github.com/search?q=is%3Aopen+is%3Aissue+repo%3A{project_module_name}+label%3Adeprecation-help
[search-{project_name}-label-deprecation-help]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Adeprecation-help
[search-{project_module_name}-label-electron]: https://github.com/search?q=is%3Aissue+repo%3A{project_module_name}+is%3Aopen+label%3Aelectron
[search-{project_name}-label-electron]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3A{project_name}+label%3Aelectron
[search-{project_module_name}-label-work-in-progress]: https://github.com/search?q=is%3Aopen+is%3Apr+repo%3A{project_module_name}+label%3Awork-in-progress
[search-{project_name}-label-work-in-progress]: https://github.com/search?q=is%3Aopen+is%3Apr+user%3A{project_name}+label%3Awork-in-progress
[search-{project_module_name}-label-needs-review]: https://github.com/search?q=is%3Aopen+is%3Apr+repo%3A{project_module_name}+label%3Aneeds-review
[search-{project_name}-label-needs-review]: https://github.com/search?q=is%3Aopen+is%3Apr+user%3A{project_name}+label%3Aneeds-review
[search-{project_module_name}-label-under-review]: https://github.com/search?q=is%3Aopen+is%3Apr+repo%3A{project_module_name}+label%3Aunder-review
[search-{project_name}-label-under-review]: https://github.com/search?q=is%3Aopen+is%3Apr+user%3A{project_name}+label%3Aunder-review
[search-{project_module_name}-label-requires-changes]: https://github.com/search?q=is%3Aopen+is%3Apr+repo%3A{project_module_name}+label%3Arequires-changes
[search-{project_name}-label-requires-changes]: https://github.com/search?q=is%3Aopen+is%3Apr+user%3A{project_name}+label%3Arequires-changes
[search-{project_module_name}-label-needs-testing]: https://github.com/search?q=is%3Aopen+is%3Apr+repo%3A{project_module_name}+label%3Aneeds-testing
[search-{project_name}-label-needs-testing]: https://github.com/search?q=is%3Aopen+is%3Apr+user%3A{project_name}+label%3Aneeds-testing
[beginner]: https://github.com/search?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+label%3Abeginner+label%3Ahelp-wanted+user%3A{project_name}+sort%3Acomments-desc
[help-wanted]: https://github.com/search?q=is%3Aopen+is%3Aissue+label%3Ahelp-wanted+user%3A{project_name}+sort%3Acomments-desc+-label%3Abeginner
