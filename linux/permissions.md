Use `ls -l` to view current permissions

Permissions look like this rwxrwxrwx
- First 3 are for the file owner
- Next 3 are for the group
- Last 3 are for others (everyone that is not the owner or in the assigned group)

rwx:
- r for read (value of 4)
- w for write (value of 2)
- x for execute (value of 1)

Numbering
- 7 = rwx
- 4 = r
- 2 = w
- 1 = x
- 6 = rw
- etc

chmod
- `chmod 777 file` gives everyone full access
- `chmod 700 file` restricts permissions for everyone but the owner
- `chmod 644 file` translates to rw-r--r--