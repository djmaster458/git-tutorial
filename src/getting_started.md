# Getting Started
## What is Git?
"Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

Git is easy to learn and has a tiny footprint with lightning fast performance. It outclasses SCM tools like Subversion, CVS, Perforce, and ClearCase with features like cheap local branching, convenient staging areas, and multiple workflows." - [Git's Official Documentation](https://git-scm.com/)

Let's break it down:
- Free
  - Everyone likes free!!!
- Open-Source
  - Community support
- Distributed Version Control
  - Everyone has a copy of the code
  - No one is restricted from shared editing (some caveat we'll see later)

## Why use Git?
Everyone has likely done version control this way
```
./myMidtermReportDraft
./myMidtermReportDraftRev1
./myMidtermReportDraftRev2
./myReportRev3
... so on
```

This is super unsustainable for a couple reasons
- Lots of disk space utilized for each file
- Naming conventions gets easily confusion
- Accidental changes to the wrong file are difficult or manual to undo

Git is better because
- Uses mechanisms to store only file changes to be lightweight on disk space
- Maintains a history of file states and changes for easy undo/redo
- Distributed system so multiple people can work on the same file without stepping on each other without warrant

## Who uses Git?
- Software developers and people who work closely
- Script writers for team or personal use
- Teams that work together to edit files
- Anyone who wants to track changes in their files
