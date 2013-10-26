smb2unc
=======

Description
------
UNC/SMB path translator (CLI)

Usage
------
```bash
$ unc2smb '\\foo\bar\path\to\file.txt'
# => smb://foo/bar/path/to/file.txt

$ echo '\\foo\bar\path\to\file.txt' | unc2smb 
# => smb://foo/bar/path/to/file.txt
```

```bash
$ smb2unc 'smb://foo/bar/path/to/file.txt'
# => \\foo\bar\path\to\file.txt
 
$ echo 'smb://foo/bar/path/to/file.txt' | smb2unc 
# => \\foo\bar\path\to\file.txt
```

License
------
MIT
