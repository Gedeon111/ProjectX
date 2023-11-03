## Benefits of Commits:

    Es gibt eine gute Übersicht über was man im Verlauf gemacht hat und auf welche Version man ist. Hilft auch gut zu erinnern, was man am Tag davor vielleicht geändert hat.

## Verifying a Commit:

    One way to verify a commit is by checking its unique hash identifier. Each commit is identified by a SHA-1 hash, which is a unique 40-character string. You can view the commit history and their hashes using the git log command.

## Checking if a File is Tracked and Tracking it if Not:

    To check if a file is tracked, you can use the command git ls-files <file-name>. If the file is tracked, it will be listed.
    If the file is not tracked and you want to start tracking it, you can use the command git add <file-name> to stage it for the next commit. After that, you can commit the changes using git commit -m "Commit message".