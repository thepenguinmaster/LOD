::::::::::::::::::::::::::::::::::::::::::::
!exercise: 
name="First Exercise" 
scenario= "In this exercise, you will do things" 
completionMessage= "All Done!"


`````````````````````````````````````
!task: 
name="Markdown Introduction" 
alert="Markdown is great!"
idea="Use Markdown in all the things"
screenShotUrl= "www.google.com"
... Text for the task can go here. You can type what you need and it will show as the normal task text. 
... You can also use standard markdown syntax here such as:
... - number lists
... 	1. One
... 	2. Two
... 	3. Three
... - Bullet points
... 	* Start a line with a star
... 	* Profit!
... - Unoredered lists
... 	* Item 1
... 	* Item 2
... 	  * Item 2a
... 	  * Item 2b
... *This text will be italic*
... **This text will be bold**
... __This will also be bold__
... 
... _You **can** combine them_
`````````````````````````````````````
`````````````````````
!task: 
name="Markdown Introduction 2" 
alert="Markdown is easy!"
idea="Learn more markdown"

...In this task, you will notice that it is another task!
...
...#We have code blocks
...
...##Pythjon code? Sure!
...~~~python
...import time
...# Quick, count to ten!
...for i in range(10):
...    # (but not *too* quick)
...    time.sleep(0.5)
...    print i
...~~~
...
...##Powershell? Yeah we have that too!
...
...~~~powershell
...# This is an example code block
...$Path = "C:\Program Files\"
...Get-ChildItem  $Path -recurse -force | ForEach {
...    If ($_.extension -eq ".txt") {
...        Write-Host $_.fullname 
...    }
...}
...~~~
`````````````````````


::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::::::::::
!exercise: 
name="Preparing to update Skype for Business Servers" 
scenario= "In this exercise, you will do more things" 
completionMessage= "All Done!"

`````````````````````
!task: 
name="Markdown Introduction 3" 
alert=""
idea=""

...Here we have links and images
...
...[This is a link example](https://www.google.com)
...
...Inline-style: 
...(https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")
...
...Image wiht link:
...[![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)](https://www.google.com)
...
...And more!
`````````````````````
::::::::::::::::::::::::::::::::::::::::::::
