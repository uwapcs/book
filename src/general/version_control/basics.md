Version Control Basics
======================

Version Control is a system to manage a set of changes to documents, programs or other collections of information. Usually each set of changes will have some identifier that make it unique from every other state of the collections. Although version control is usually only ever referred to in the context of tools such as `git`, there are a lot more things that count as version control. Some examples include:

- Undo/Redo in a text editor.
- Copy and pasting a folder every time you make a modification.

So even when you're editing a file using Microsoft Word or Google Docs, you still have some rudimentary version control occurring! (You can actually see the history of your file in Microsoft Word or Google Docs by looking in the menu for "history")


## The benefits of version control

As teams design, build, run and deploy software (a.k.a. every project you'll have to do ever, including on your own), it is common to have multiple concurrent versions of software in different places. For example, while you work on some parts of a project for university, a team member works on their own parts at the same time. Both of you want to edit your code while the other is editing, and both of you want to test your code (or at least you *should* want to test your code) with none of the other's partially completed code interfering. Another example is if you find a bug in your code. It's a good idea to try to find where the bug first appeared. If you're able to determine when the bug first appears, you can look at the difference between the two versions to determine which section of the code is incorrect.

## Terminology

- Master

	The main version of the code.

- Branch

	A version of the code that may develop files at different speeds or in different ways independently to other versions.

- Change/Diff

	A specific modification to a document under version control.

- Change list

	The set of changes in a single "commit"

- Checkout

	To create a local working copy from a repository.

- Clone

	To create a repository containing the revisions from another repository.

- Commit

	To write a set of changes in the working directory back into the repository.

- Conflict

	Occurs when two different branches make changes to the same document and the changes are not able to be automatically reconciled.

- Fetch

	To integrate a number of changes from another repository into your local repository.

- Head

	The most recent commit.

- Merge

	An operation that combines a set of changes to a set of files.

- Pull

	To fetch (see above) and then merge the changes into the working directory.

- Push

	To send the set of changes in your local repository to a remote repository.

- Repository

	Where the files' current and historical data is stored.

- Tag

	A user-friendly name that refers to a version.

- Version

	The state of the repository and working directory after any given set of commits. 
