# Contributing to Outboxer

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

The following is a set of guidelines for contributing to Outboxer and its packages, 
which are hosted on [Github](https://github.com/italolelis) on GitHub.
These are just guidelines, not rules. Use your best judgment, and feel free to propose changes 
to this document in a pull request.

## Code of Conduct

This project adheres to the Contributor Covenant [code of conduct](CODE_OF_CONDUCT.md).
By participating, you are expected to uphold this code.
Please report unacceptable behavior to [italolelis@gmail.com](mailto:me@italovietro.com).

We accept contributions via Pull Requests on [Github](https://github.com/italolelis/outboxer).

## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report for Outboxer. Following these guidelines helps maintainers 
and the community understand your report :pencil: reproduce the behavior :computer: :computer: and find related 
reports :mag_right:.

Before creating bug reports, please check if the bug was already reported before as you might find out that you don't need to create one. When you are creating a bug report, please [include as many details as possible](#how-do-i-submit-a-good-bug-report). 

#### How Do I Submit A (Good) Bug Report?

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). Create an issue providing the following information.

Explain the problem and include additional details to help maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the exact steps which reproduce the problem** in as many details as possible. For example, start by explaining how you started Outboxer, 
e.g. which command exactly you used in the terminal. When listing steps, **don't just say what you did but explain how you did it**.
* **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. 
If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
* **Explain which behavior you expected to see instead and why.**

Include details about your configuration and environment:

* **Which version of Outboxer are you using?**
* **What's the name and version of the OS you're using**?

### Your First Code Contribution

Unsure where to begin contributing to Outboxer? You can start by looking through these `beginner` and `help-wanted` issues:

* [Beginner issues][beginner] - issues which should only require a few lines of code, and a test or two.
* [Help wanted issues][help-wanted] - issues which should be a bit more involved than `beginner` issues.

Both issue lists are sorted by total number of comments. While not perfect, number of comments is a reasonable proxy for impact a given change will have.

### Local Workspace Setup

For local development use the `docker` containers.

Run `docker-compose up -d` from `build` directory to bring up `rabbitmq` and `localstack`.

RabbitMQ management portal will be available at `http://localhost:15672/`.

A local `Kinesis` setup using `localstack` will be available at `http://localhost:4568`.

### Pull Requests

* Include screenshots and animated GIFs in your pull request whenever possible.
* Follow the [Go](https://github.com/golang/go/wiki/CodeReviewComments) styleguides.
* Include thoughtfully-worded, well-structured tests.
* Document new code
* End files with a newline.


Happy Coding!
