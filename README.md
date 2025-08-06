# hello-git
Summary of Basic "Edit/Stage/Commit/Push" Cycle
// Edit (Create, Modified, Rename, Delete) files,
//  which produces "unstaged" file changes.
 
// Stage file changes, which produces "Staged" file changes
$ git add <file>                          // for new and modified files
$ git rm <file>                           // for deleted files
$ git mv <old-file-name> <new-file-name>  // for renamed file

// Commit (ALL staged file changes)
$ git commit -m "message"

// Push
$ git push <remote-name> <local-branch-name>
OR,

// Stage ALL files with changes
$ git add -A   // OR, 'git add --all'

$ git commit -m "message"
$ git push
OR,

// Add All and Commit in one command
$ git commit -a -m "message"

$ git push