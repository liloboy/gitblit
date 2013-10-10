I needed a easy to use and straightforward way to access a git repository and obtain the following:

* Get a list of all commits (or just the last N commits).
* Get the list of files that were present at a specific commit.
* Given a specific commit as well as a filename, get the contents of the file at that commit.
* Given two commits the diff between the two versions of a specific file.
* The diff between two text files.

This can all be done by calling the needed static methods in *JGitUtils.java* and *DiffUtils.java* found in the *git* package.

I forked this project from GitBlit (http://gitblit.com/ the source code can be found at https://github.com/gitblit/gitblit) only keeping and extending the git utilities to solve the problems stated above.

The only dependancy is JGit (http://www.eclipse.org/jgit/), put the JGit jar file in your classpath.