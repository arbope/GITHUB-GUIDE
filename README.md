
# GITHUB
## AUTORES
_Aron Bou Pelillo_

## Introduction
>Git is a version control system that intelligently tracks changes in files. Git is particularly useful when you and a group of people are all making changes to the same files at the same time.
>GitHub is a cloud-based platform where you can store, share, and work together with others to write code.

## How do Git and GitHub work together?
>When you upload files to GitHub, you'll store them in a "Git repository." This means that when you make changes (or "commits") to your files in GitHub, Git will automatically start to track and manage
>your changes. There are plenty of Git-related actions that you can complete on GitHub directly in your browser, such as creating a Git repository, creating branches, and uploading and editing files.

## Guide
![quickstart guide](https://imgur.com/CjWo0kS.jpg)

In this quickstart guide, you will:

* [Create a repository](#Step-1:-Create-a-repository)
* [Create a branch](#step-2-create-a-branch)
* [Make and commit changes](#step-3-make-and-commit-changes)
* [Open a pull request](#step-4-open-a-pull-request)
* [Merge your pull request](#step-5-merge-your-pull-request)

## Step 1: Create a repository
The first thing we'll do is create a repository. You can think of a repository as a folder that contains related items, such as files, images, videos, or even other folders. A repository usually groups together items that belong to the same "project" or thing you're working on.

Often, repositories include a README file, a file with information about your project. README files are written in Markdown, which is an easy-to-read, easy-to-write language for formatting plain text. We'll learn more about Markdown in the next tutorial, "[Setting up your profile](https://docs.github.com/en/get-started/start-your-journey/setting-up-your-profile)."

GitHub lets you add a README file at the same time you create your new repository. GitHub also offers other common options such as a license file, but you do not have to select any of them now.

Your _hello-world_ repository can be a place where you store ideas, resources, or even share and discuss things with others.
1. In the upper-right corner of any page, select , then click New repository.
 ![](https://docs.github.com/assets/cb-29762/mw-1440/images/help/repository/repo-create-global-nav-update.webp)
2. In the "Repository name" box, type _hello-world_.
3. In the "Description" box, type a short description. For example, type "This repository is for practicing the GitHub Flow."
4. Select whether your repository will be **Public** or **Private**.
5. Select **Add a README file**
6. Click **Create repository**.


## Step 2: Create a branch
Branching lets you have different versions of a repository at one time.

By default, your repository has one branch named _main_ that is considered to be the definitive branch. You can create additional branches off of _main_ in your repository.

Branching is helpful when you want to add new features to a project without changing the main source of code. The work done on different branches will not show up on the main branch until you merge it, which we will cover later in this guide. You can use branches to experiment and make edits before committing them to _main_.

When you create a branch off the _main_ branch, you're making a copy, or snapshot, of _main_ as it was at that point in time. If someone else made changes to the _main_ branch while you were working on your branch, you could pull in those updates.

This diagram shows:
 * The _main_ branch
 * A new branch called _feature_
 * The journey that _feature_ takes before it's merged into _main_

![](https://docs.github.com/assets/cb-23923/mw-1440/images/help/repository/branching.webp)

### Creating a branch
1. Click the **Code** tab of your _hello-world_ repository.
2. Above the file list, click the dropdown menu that says **main**.
![](https://docs.github.com/assets/cb-16584/mw-1440/images/help/branches/branch-selection-dropdown-global-nav-update.webp)
3. Type a branch name, _readme-edits_, into the text box.
4. Click **Create branch: readme-edits from main**.

Now you have two branches, _main_ and _readme-edits_. Right now, they look exactly the same. Next you'll add changes to the new _readme-edits_ branch.

## Step 3: Make and commit changes

When you created a new branch in the previous step, GitHub brought you to the code page for your new _readme-edits_ branch, which is a copy of _main_.

You can make and save changes to the files in your repository. On GitHub, saved changes are called commits. Each commit has an associated commit message, which is a description explaining why a particular change was made. Commit messages capture the history of your changes so that other contributors can understand what you’ve done and why.

1. Under the _readme-edits_ branch you created, click the _README.md_ file.
2. To edit the file, click.
3. In the editor, write a bit about yourself.
4. Click **Commit changes**.
5. In the "Commit changes" box, write a commit message that describes your changes.
6. Click **Commit changes**.

These changes will be made only to the README file on your readme-edits branch, so now this branch contains content that's different from main.


## Step 4: Open a pull request
Now that you have changes in a branch off of _main_, you can open a pull request.

Pull requests are the heart of collaboration on GitHub. When you open a pull request, you're proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch. Pull requests show diffs, or differences, of the content from both branches. The changes, additions, and subtractions are shown in different colors.

As soon as you make a commit, you can open a pull request and start a discussion, even before the code is finished.

In this step, you'll open a pull request in your own repository and then merge it yourself. It's a great way to practise the GitHub flow before working on larger projects.

1. Click the **Pull requests** tab of your _hello-world_ repository.
2. Click **New pull request**.
3. In the **Example Comparisons** box, select the branch you made, _readme-edits_, to compare with _main_ (the original).
4. Look over your changes in the diffs on the Compare page, make sure they're what you want to submit.
  ![Screenshot of a diff for the README.md file. 3 red lines list the text that's being removed, and 3 green lines list the text being added.](https://docs.github.com/assets/cb-32937/mw-1440/images/help/repository/diffs.webp)
5. Click **Create pull request**.
6. Give your pull request a title and write a brief description of your changes. You can include emojis and drag and drop images and gifs.
7. Click **Create pull request**.

### Reviewing a pull request

When you start collaborating with others, this is the time you'd ask for their review. This allows your collaborators to comment on, or propose changes to, your pull request before you merge the changes into the _main_ branch.

We won't cover reviewing pull requests in this tutorial, but if you're interested in learning more, see "[About pull request reviews](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/about-pull-request-reviews)." Alternatively, try the GitHub Skills "[Reviewing pull requests](https://skills.github.com/)" course.


## Step 5: Merge your pull request

In this final step, you will merge your _readme-edits_ branch into the _main_ branch. After you merge your pull request, the changes on your _readme-edits_ branch will be incorporated into _main_.

Sometimes, a pull request may introduce changes to code that conflict with the existing code on _main_. If there are any conflicts, GitHub will alert you about the conflicting code and prevent merging until the conflicts are resolved. You can make a commit that resolves the conflicts or use comments in the pull request to discuss the conflicts with your team members.

In this walk-through, you should not have any conflicts, so you are ready to merge your branch into the main branch.

1. At the bottom of the pull request, click **Merge pull request** to merge the changes into _main_.
2. Click **Confirm merge**. You will receive a message that the request was successfully merged and the request was closed.
3. Click **Delete branch**. Now that your pull request is merged and your changes are on _main_, you can safely delete the _readme-edits_ branch. If you want to make more changes to your project, you can always create a new branch and repeat this process.
4. Click back to the **Code** tab of your _hello-world_ repository to see your published changes on _main_.



## Bibliography
https://docs.github.com/en

## Conclusions
