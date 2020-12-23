# Read: 19 - Readings: Automation

*Today Topic will be a about Readings: Automation*
- Automation

##  Readings: Automation

> What Is Automation?

![Ceasar](images/maxresdefault.jpg)


**Regular Expression**
*A Regular Expression (RegEx) is a sequence of characters that defines a search pattern. For example,*

```
^a...s$
```
*The pattern is: any five letter string starting with a and ending with s.*

*Python has a module named re to work with RegEx. Here's an example:*

```
import re

pattern = '^a...s$'
test_string = 'abyss'
result = re.match(pattern, test_string)

if result:
  print("Search successful.")
else:
  print("Search unsuccessful.")
```

*Here, we used re.match() function to search pattern within the test_string. The method returns a match object if the search is successful. If not, it returns None.*

**Specify Pattern Using RegEx**

*To specify regular expressions, metacharacters are used. In the above example, ^ and $ are metacharacters.*

**MetaCharacters**
*Metacharacters are characters that are interpreted in a special way by a RegEx engine. Here's a list of metacharacters:*

`[] . ^ $ * + ? {} () \ |`

**[] - Square brackets**

*Square brackets specifies a set of characters you wish to match.*


[For More Info](https://www.programiz.com/python-programming/regex)


**shutil — High-level File Operations**
*A number of functions for hgh level operations on files and directories have been defined in shutil module of Python’s standard library.*  

* copy()
*This function copies a file to a specified file in same or other directory.*
```
import shutil
shutil.copy("hello.py","newdir/")

'newdir/hello.py'
```

* copy2()
*This function retains metadata of source file*
```
shutil.copy2('person.py', 'newdir/')
'newdir/person.py'
```

* copytree()
*This function recursively copies file and subdirectories in one directory to another directory.*

```
shutil.copytree('dir1','dir2')
```



## Contact Info : 
**Please Feel Free To Contact Me When You Need help ^_^**
* [www.facebook.com/aghyadalbalkhi](www.facebook.com/aghyadalbalkhi)
* Email : aghyadalbalkhi@gmail.com