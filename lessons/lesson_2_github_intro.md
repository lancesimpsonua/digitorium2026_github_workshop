# DRAFT Lesson 2: Intro to GitHub

## About This Lesson

In this lesson, we will introduce GitHub. We will take a look at a few of its features, how it integrates with Git, and why it is useful for managing projects, especially in collaborative environments.

## Lesson Outline

### What is GitHub?

GitHub is a web-based platform that builds on Git, providing a reasonably user-friendly interface for version control and collaboration. It's one of many platforms like this, such as GitLab and Bitbucket.
  
It allows multiple contributors to work on the same project, track changes, and manage project history efficiently.
GitHub also offers additional features such as issue tracking, pull requests, and project management tools that facilitate collaborative development.

You can even use GitHub to host small websites using GitHub Pages, which allows you to publish static websites directly from a GitHub repository.

Especially for projects that are Open Source, It's also a great way to publicly share your projects, code, and research with a wider audience, making it easier for others to collaborate, provide feedback, and contribute.

### Why use GitHub?

GitHub builds on the already robust version control capabilities of Git, adding tools that make collaboration and project management on exceedingly large and complex projects more manageable and efficient.

Whether you create a public or private repository for your project, platforms like Github create central storage locations for your code, documentation, and project history.

While I don't currently collaborate with many others on my own projects, I use Github as the source of truth for my code, ensuring that I have a reliable backup and a clear history of all changes made.  This allows me to clone my projects onto multiple computers, where I can make changes, and the commit those changes locally, and sync them with the cloud version of my repository as needed.

In collaborative projects, GitHub becomes even more valuable, as it helps coordinate work among multiple contributors and manage code reviews. For publicly available projects, GitHub also has robust features for the community report issues, or if invited, to suggest code contributions, or request features.

### Reviewing the Public GitHub for this Workshop

Let's take a moment to review some of the features of GitHub by exploring the public repository for this workshop.

If you're currently at this presentation, I'll drop the link for the repository in the chat.

I built out this presentation in GitHub and by pushing file changes from my computer to show you a few things. You can see how the repository updates in real-time, how commits are tracked, and how changes are reflected in the project history. I've used the commit comments to provide context for each change, making it easier to understand the evolution of the project over time.

We'll take some time to look around here. A couple of things we'll cover during this live review:
- **Commits**: We'll look at how commits are made, how they are tracked, and how commit messages provide context for changes. We'll take a look at how the commits review the difference between the files in each commit, and how this helps in understanding the evolution of the project over time.
- **README**: We'll examine the README file, which typically provides an overview of the project, instructions for setup, and other relevant information for contributors and users.
- **License**: We'll take a look at the repository's license file, which specifies the terms under which the project's code can be used, modified, and distributed.


#### What else can be done to this repository using GitHub?

When thinking about this as a potential community collaboration standpoint:
- **Forking:** Forking allows you to create a personal copy of someone else's repository. This is useful for experimenting with changes without affecting the original project. Once changes are made,you can propose these changes back to the original repository via a pull request.
- **Pull Request:** A pull request is a way to propose changes to a repository. It allows repository maintainers to review the changes, discuss potential modifications, and merge them into the main project if approved.
    -  What if you looked at my lesson plan, and were way more knowledgeable about GitHub and wanted to contribute some additions? You could fork the repository, make improvements or add new content, and then submit a pull request to contribute back to the original project.
- **Issues:** Issues are used to track tasks, enhancements, and bugs for your projects. They provide a way for contributors to discuss and collaborate on specific topics related to the repository. 
    - For example, if you notice a typo in the lesson plan or have a suggestion for improvement, you can create an issue to bring it to the attention of the repository maintainers.
    - An issue differs from a pull request in that it is used to discuss and track problems or enhancements, rather than proposing specific changes to the codebase or files.

## References
