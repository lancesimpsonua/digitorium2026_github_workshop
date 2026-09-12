# DRAFT Lesson 3: Trying it Out

## About This Lesson

In this lesson, we will initialize a repository on GitHub, make a README and license file, and we'll upload an existing project.


## Lesson Outline

### Getting Ready

The first thing that we'll need to do is to choose the file we'll use as the starting point for our repository. This could be an existing project folder on your computer or a new folder that you'll create specifically for this repository.

For us, I recommend using the existing Jupyter Notebook from the Chronicling America API project you all did in the workshop with Dr. Dubose on Friday.

If you don't still have ready access to the file, I've dropped a copy in the chat for you to download. I'm also adding the License file for the notebook into the chat. Go ahead and download both files before proceeding.

### Initializing a Repository

To initialize a repository on GitHub, follow these steps:

1. Go to GitHub and log in to your account.
2. Click on the "+" icon in the top right corner and select "New repository".
3. Fill in the repository name, description (optional, but helpful!), and choose the visibility (public or private).
4. Let's hold off on adding a README or License for now. We'll come back to these manually, later.
5. Click "Create repository" to initialize your new repository.


### Uploading an Existing Project File

Let's now upload the Jupyter Notebook to your repository.

To upload an existing project file to your repository, follow these steps (assuming that you are still currently in the repository's main page on GitHub):

1. Click on "Add file" and select "Upload files".
2. Drag and drop the Jupyter Notebook into the upload area or click "choose your files" to select them from your computer.
3. Add a commit message describing the changes you are making (e.g., "Add Jupyter Notebook").
4. Click "Commit changes" to upload the files to your repository.


### Make a License File

After initializing your repository, you can add a README and license file:

1. Navigate to your newly created repository on GitHub.
2. Click on "Add file" and select "Create new file".
3. Name the file `LICENSE.md` and add some initial content describing your project.
4. Review the License from Dr. Dubose's Jupyter Notebook to ensure it is correctly applied to your project. You'll notice that the project has its own MIT license, which should be reflected in your `LICENSE.md` file.
5. GitHub also provides options for open source license language that you can add automatically. Choose the appropriate license (in this case, MIT), and update the Copyright info to your name.
6. Click "Commit new file", and add your commit message describing the addition of the license file (e.g., "Add LICENSE.md").


### Make a README file.

1. Navigate back to the main page of your repository on GitHub.
2. Click on "Add file" and select "Create new file".
3. Name the file `README.md` and add some initial content describing your project.
4. Click "Commit new file", and add your commit message describing the addition of the README file (e.g., "Add README.md").


### Fork this Lesson Repository

Let's try out forking a repository on GitHub. To do that, we'll use the lesson repository we're in right now.

To fork this lesson repository, follow these steps:

1. Navigate to the main page of the lesson repository on GitHub.
2. Click the "Fork" button in the top right corner of the page.
3. Select your GitHub account as the destination for the fork.
4. GitHub will create a copy of the repository under your account, which you can now modify independently of the original repository.


### Make changes to the Forked Repository

To make changes to the forked repository, follow these steps:

1. Navigate to your forked repository on GitHub.
2. Click on the file you want to edit, or add a new file by clicking "Add file" and selecting "Create new file".
3. Make the desired changes to the file.
4. Create a branch for your changes by clicking on the branch dropdown and selecting "Create new branch".
5. Add a commit message describing the changes you made.
6. Click "Commit changes" to save your changes to the forked repository.


### Open a Pull Request to the Original Repository for the Changes You Made

To open a pull request to the original repository for the changes you made, follow these steps:

1. Navigate to your forked repository on GitHub.
2. Click on the "Pull requests" tab.
3. Click the "New pull request" button.
4. Ensure that the base repository is the original lesson repository and the base branch is the branch you want to merge into.
5. Ensure that the head repository is your forked repository and the compare branch is the branch containing your changes.
6. Review the changes and add a title and description for your pull request.
7. Click "Create pull request" to submit your changes for review.    

## References

1. [GitHub Quickstart for Repositories](https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories)
2. [GitHub Fork Documentation](https://docs.github.com/en/get-started/quickstart/fork-a-repo)
3. [GitHub Pull Request Documentation](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests)
