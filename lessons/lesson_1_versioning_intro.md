# DRAFT Lesson 1: Intro to Versioning and Version Control

## About This Lesson

Versioning can be important for documentation, for reproducibility of workflows, for the fidelity of a project, and (with software) for troubleshooting and tracing errors. We'll see how these ideas apply to documents, datasets, programmatic workflows, and more. While we will not directly use a Command Line Interface `CLI`, we will explore the some basic concepts and functions of the Git software as a tool for versioning.

## Lesson Outline

### What is Versioning and Version Control? <!-- Cite Git Manual and Software Carpentries Here-->

Versioning is the practice of keeping track of changes over time. 

You can version:

- a single document or an entire project.
- most any file, including text-based documents, images, code/software, etc.

You likely already have a versioning practice in place either locally on your machine, or using online repository tools like Google Drive, Box, OneDrive, or DropBox.

Each of these allows for users to add files in ways that track changes between versions. For some, however, this can require you to activate a `Track Changes` feature within a document to get a more full understanding of what's changed within a document between edits. Tools like Box provide the option to continually upload a file by the same name, and to be able to see and revert to previous version of the document.

How you choose to version a project can determine which parts of the process are visible and available to you, collaborators, and other researchers over time. This choice can also determine how easily (and to what extent) you can track changes or possibly revert to previous versions of single files or the entire project.

Some considerations you may have when deciding how to version a project include:
- how often you update your files or project.
- whether you have collaborators.
- the level of need for chronicling detailed changes.
- whether you may need to easily revert a file or project in real time.

Some of these needs require changes and versions to be tracked in specific ways. As we continue through the lesson, we'll focus on automated version control systems that allow for very detailed and expansive tracking of versions. These systems often require a greater degree of upfront setup and maintenance. But they offer an incredible level of granular control over a project and its history of development.

Specifically, we will introduce the software, Git, and a cloud-based storage and project management system that utilizes Git, GitHub.

### What is Git?

Git is a distributed, automated version control system. It functions as a powerful system that can be used to create exact snapshots of specific files, or your project as a whole, at any point you choose.

Git can be used on Windows, MacOS, and the various flavors of Linux operating systems.

You can use git as an individual contributor tracking progress, history, and versions of your work. Git also allows for managing the work of multiple contributors.

Changes are recorded in Git with what's called a `commit`. A `commit` is basically a saved state of your project at that moment. With each `commit`, Git records a `snapshot` of your project at that specific point in time. This allows you to track changes, review the history of your project, and revert to previous versions if necessary.

#### Commits as Reflective Practice

With each `commit`, you choose what of the changes from last `commit` that you want to include. Git allows for your to provide a descriptive comment on what changes are being committed and why, which can serve as a reflective practice for understanding the evolution of your project.

#### Collaborating

It is especially helpful in providing control over the main version of any file or project. This means that when you are working as a group, you can establish ways for collaborators to make changes directly to the main version of a project, or you can have them create what's called a `Branch` of a project.

Branching in Git allows you or collaborators to create a secondary version of the main project where you can make edits and changes with these directly affecting the main version of the project.

Here are a few ways this can be particularly useful:
- You want to try out new additions to your code. With branching you can do this, and decide later whether to commit these changes to the main branch of the project.
- You and your collaborators are working across branches, and you want to select which of these change you all have made to be a part of the main version of the project.
- You and your collaborators have made conflicting edits on your respective branches. Git is designed with a resolution process in mind to ensure these conflicts are resolved before being committed to the main branch.

#### Free and Open Source

Git is Open Source, and licensed under a GNU General Public License. This means the software is free for use, modification, and research.

#### What's in a name? How did it get to be called Git?

From Git's README <!--### Citation needed here -->:

> The name "git" was given by Linus Torvalds when he wrote the very
first version. He described the tool as "the stupid content tracker"
and the name as (depending on your mood):
> - random three-letter combination that is pronounceable, and not
   actually used by any common UNIX command.  The fact that it is a
   mispronunciation of "get" may or may not be relevant.
> - stupid. contemptible and despicable. simple. Take your pick from the
   dictionary of slang.
> - "global information tracker": you're in a good mood, and it actually
   works for you. Angels sing, and a light suddenly fills the room.
> - "goddamn idiotic truckload of sh*t": when it breaks

### Why use version control systems like Git in DH projects?

Version control systems like Git are particularly useful in Digital Humanities (DH) projects for several reasons:    
- They allow multiple collaborators to work on the same project simultaneously without overwriting each other's changes.
- They provide a detailed history of changes, making it easier to track the evolution of the project and understand the contributions of each collaborator.
- They facilitate experimentation through branching, enabling researchers to test new ideas without affecting the main project.
- They help in maintaining backups and recovering previous versions of the project in case of errors or data loss.
- They promote transparency and accountability by clearly showing who made which changes and when.

## References

<!-- Need to format these, but I am adding them as I go. -->

The Software Carpentries. (n.d.). Version control with git: Automated version control. Retrieved September 8, 2026, from https://swcarpentry.github.io/git-novice/01-basics.html

Git. (n.d.). Git—README. Retrieved September 9, 2026, from https://github.com/git/git/blob/master/README.md


