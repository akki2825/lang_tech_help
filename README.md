# About
Tech help for Language technology for Linguists with Internet of Things (IoT)

# Table of content
+ <a href="#how-to-open-an-issue">How to open an issue</a> 
  + <a href="#assignees">Assignees</a> 
  + <a href="#labels">Labels</a> 
  + <a href="#styling-options-and-fancy-links">Styling options and fancy links</a> 
+ <a href="#getting-information-on-software-and-hardware">Getting information on software and hardware</a> 
  + <a href="#windows">Windows</a> 
  + <a href="#linux">Linux</a>   
  + <a href="#mac-os">Mac OS</a> 
  + <a href="#package-information-in-python">Package information in Python</a> 
  + <a href="#package-information-in-r">Package information in R</a>     
+ <a href="#contact-a-specific-person">Contact a specific person</a> 


## How to open an issue
---
#### TLDR
1. Go to `Issues`, at the top left.
2. Check if your issue already exists.
3. Click on `New Issue`.
4. Choose a template, fill it out according to the instructions.
5. If applicable, choose labels and assignees.
6. Come back to this README because you need help (Beginner mode).
7. Submit your issue.
---

### Assignees
**Assign issues** to specific people by clicking `Assignees` on the right side and selecting a person. This will notify them by mail.

### Labels
You can create new **labels** by going to `issues` and then `labels`. 

**Secret tip:** [This link](https://color-hex.com) leads to a Hex color picker to make your lables look nice. Just copy the # number to get the color for your tag.

### Styling options and fancy links
Please make use of the styling options in the top right of the comment box. You can do anything from adding links and to do boxes, to code blocks.
If you are feling fancy, you can make your links special by embedding them in text. Simply use the syntax below.

```
[normal text that links to whatever](actual link that wont be visible)
```

## Getting information on software and hardware
### Windows
1. Click the Windows Start button
2. Settings
3. System
4. Scroll down, click About
5. Copy the first box called 'Device specifications'. 
(For issues, you can leave out `device name` and `pen and touch`, unless they are specifically relevant)

### Linux
#### System information
`sudo lshw -short`

(If you are bored, leave out the 'short' and see what happens).
You can also use `uname` To get a shorter version. 

#### Kernel information with `uname`
- Kernel name -> `uname -s
- Kernel release information -> `uname -r`
- Kernel version -> `uname -v`

### Mac OS
1. Apple symbol at the top of your screen
2. About this Mac
3. System Report
4. Choose the relevant information from there. 

## Package information in Python
- All installed packages + versions -> `pip list` or `pip freeze` or `conda list`
- All packages used by a script + versions -> `pip3 install pipreqs` then `pipreqs ./pathtoyourscript` (You get a requirements.txt file with the dependencies)
