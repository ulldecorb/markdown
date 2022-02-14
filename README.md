# Markdown
Markdown style cheatsheet

## Table of content
* [Heading](#heading)
* [Text style](#text-style)
    * [Italic](#italic)
    * [bold](#bold)
    * [Strike Through](#strike-through)
    * [Coded](#coded)
* [Paragraph style](#paragraph-style)   
   * [Ordered List](#ordered-list)
   * [Unordered List](#unordered-list)
   * [Horizontal Line](#horizontal-line)
   * [Block Quote](#block-quote)
   * [Task List](#task-list)
* [Links](#links)   
      * [External Links](#external-links)   
      * [Internal Links](#internal-links)   
* [Images](#images)
* [Tools](#tools)
   * [Special characters](#special-characters)
   * [Escape specials characters](#escape-specials-characters)
   * [Comments](#comments)
   * [VSC Markdown Preview](#vsc-markdown-preview)
* [Sources](#sources)

## Heading

>\# heading 1   
# heading 1
>\#\# heading 2
## heading 2
>\#\#\# heading 3
### heading 3
>\#\#\#\# heading 4
#### heading 4
>\#\#\#\#\# heading 5
##### heading 5
---
## Text style
<!-- Italics -->
### Italic
>\*this text is italics\*  
*this text is italics*

>\_italic\_  
_italic_

 ### Bold
<!-- Bold -->
>\*\*bold\*\*  
**bold**

### Strike through
<!-- Strike Through-->
>\~\~strike\~\~      
~~strike~~

### Coded
On GitHub .md files can create blocks for text code. Copy text click function is added by default.

Basic inline code block
>\`<p></p>`   
>`<p></p>`

Bash script block
>\```bash  
npm install  
\```
```bash
    npm install
```

JS Block
>\```javascript   
function add(num1, num2){  
}   
\```
```javascript
function add(num1, num2){
}
```

Python block
>\```python  
print("Hello World")  
\```
```python
print("Hello World")
```

## Paragraph Style
### Unordered List
* item1
    * item2

### Ordered List
1. first item
2. second item   

### Horizontal Line
>\---   
--- 

>\___   
___

### Block quote
\> this is a block
> this is a block

### Task List
>\* \[x] done   
\* \[ ] not done   
* [x] done
* [ ] not done   

## Links
### External Links
>\[This is a link to React]\(https://reactjs.org/docs/getting-started.html)   

[This is a link to React](https://reactjs.org/docs/getting-started.html)

>\[This is the same link with tooltip]\(https://reactjs.org/docs/getting-started.html "Click to go reactjs.org")   

[This is the same link with tooltip](https://reactjs.org/docs/getting-started.html "Click to go reactjs.org")

### Internal Links 
You can browse for the headings of your document from a [Table of Content](#table-of-content)   
>\[Go to Table of Content]\(#table-of-content)
[Go to List of Content](#table-of-content)

## Tools
### Special Characters
See how write special characters like "\&#60;" [here](https://www.whatsmyip.org/html-characters/).   
### Escape Special Characters
Escape specials characters in markdown using backlash \( \ )
>\&#60;  
&#60;   

>\\\&#60;  
\&#60;   

### Comments
#### Comments on .md files are like .html files:   
>\<!-- text \-->

#### VSC Comments Shortcut:   
Windows OS spanish qwerty keyboard
> Ctrl + ç

### VSC Markdown Preview
#### Shortcut:    
Windows / Linux OS
> Ctrl+K V

Mac OS
> ⌘+K V

#### VSC Extension to markdown files preview:
>[Auto-Open Markdown Preview](https://marketplace.visualstudio.com/items?itemName=hnw.vscode-auto-open-markdown-preview)   




## Images
Add images on markdown is like create a link, but with a "!" before.
>\!\[H. P. Lovecraft]\(https://upload.wikimedia.org/wikipedia/commons/1/10/H._P._Lovecraft%2C_June_1934.jpg?20171011092735 "H. P. Lovecraft")   
   
![H. P. Lovecraft](https://upload.wikimedia.org/wikipedia/commons/1/10/H._P._Lovecraft%2C_June_1934.jpg?20171011092735 "H. P. Lovecraft")

