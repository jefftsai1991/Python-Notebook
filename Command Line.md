

[Iterate all files in a directory using a 'for' loop
](https://stackoverflow.com/questions/138497/iterate-all-files-in-a-directory-using-a-for-loop)



### Iterate through...
* files in current dir: `for %f in (.\*) do @echo %f`
* ubdirs in current dir: `for /D %s in (.\*) do @echo %s`
* files in current and all subdirs: `for /R %f in (.\*) do @echo %f`
掃過當下路徑內所有資料夾裡面的檔案
```
# Example
for /R %i in (*.json); do python code.py %i -d FolderName -m
```
* subdirs in current and all subdirs: `for /R /D %s in (.\*) do @echo %s`