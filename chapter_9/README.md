When you try to rmdir and the directory is not empty and error is triggered.  I suspect that this is sice there is not a "confirm delete" check in unix so to prevent accidental data loss you need to remove everything from the directory.
Unlike GUI interfaces, when something is deleted in unix it is gone and there is no way to recover it like opening the "trash" folder.

Can you touch blah.txt? yes
Let's create foo.txt. done 

What happens when you touch an existing file?  I used the command ls -lR that we learned earlier to show when the file was last modified.  Touching and existing file updates the last modified date.

