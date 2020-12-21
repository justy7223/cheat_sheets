# Markdown Cheat Sheet

# Table of Contents
* [Markdown Cheat Sheet](#Markdown-Cheat-Sheet)
* [Table of Contents](#Table-of-Contents)
* [Headings](#Headings)
* [Text Styling](#Text-Styling)
* [Lists](#Lists)
* [Links](#Links)
* [Images](#Images)
* [Coding & Syntax](#Coding=&-Syntax)
* [Tables](#Tables)
* [Blockquotes](#Blockquotes)
* [Lines](#Lines)
* [Misc Formatting](#Misc-Formatting)


***
***
# Headings
Headings are marked using a # followed by a space at the beginning of the line like shown below:  
# Heading 1 = `#`
## Heading 2 = `##`
### Heading 3...6 = `###...######`

***
***
# Text Styling
Text Styling can be in-line and is marked with a *, **, _, __, ~~ surrounding the text to be styled like shown below:  
**Bold Text** = `**Text** or __Text__`  
*Italic Text* = `*Text* or _Text_`  
**_Bold & Italic Text_** = `**_Text_** or __*Text*__`  
~~Strike Through Text~~ = `~~Text~~`  
New Line/Line Break = `  `(two spaces at end of line)  

***
***
# Lists
Lists are marked by a _number_., +, -, or * at the beginning of the line like shown below:  
1. Ordered = `1. First Item`
2. List = `2. Second Item`
3. Here = `3. Third Item`

* Unordered = `* Item` or `- Item` or `+ Item`
* List = `* Item`
* Here = `* Item`  
   Non-bulleted, Non-numbered indented by 3 spaces. 

***
***
# Links
Links can be in-line and are marked using a combination of [ ] ( ) " " : like shown below:  
[I am a link](https://www.github.com) = `[Display Text](link-url)`  
[I am a link with hover tag](https://www.github.com "Checkout GitHub") = `[Display Text](link-url "Hover Text")`  
[I am a link to heading in this document](#Markdown-Cheat-Sheet) = `[Display Text](#Heading-Replacing-Any-Spaces-With-Dashes)`  
https://www.github.com or <https://www.github.com> = `https://plain-url.com` or `<https://plain-url-in-angle-brackets.com>`  
[I am a link using variable as target][my target link] = `[Display Text][case InsEnsitiVe variable]`  
Then later in file you would define variable like = `[case Insensitive variable]: target-url "Hover Text"` (with empty line before)  

[my target link]: https://www.github.com "GitHub Again"

***
***
# Images
Images/Gifs can be in-line and are similar to Links except they are preceeded with an !, like shown below:  
![USS Logo](./assets/images/Logo.png "USS Logo") = `![Text if unable to load image](image-url "Hover Text")`  
Can use variable links as shown in [Link Section Above](#Links).

***
***
# Coding & Syntax
Code blocks can be small in-line or longer block type areas.  
In-line is code is surrounded by 1 back-tick to start and end block like shown below:  
In-line `Code block area` = `` Outside code block area `Code block area` `` 

Multi-line language specific code block (using 3 back-ticks to start then programming language and end with 3 back-ticks)  
> \```java
> language code goes here
> \```
```java

String myString = "code block area";
boolean stillInCodeBlock = true;
if(stillInCodeBlock){
    System.out.println(myString);
}

```
```javascript

var myJavaScript = "code block here";
if (myJavaScript !== null){
    console.log(myJavaScript);
}
```

***
***
# Tables
Tables headings are marked with | Heading 1 | Col 2 | ... | at the start of the row.    
Heading rows are followed by a row with |---|:---|:---:|---:| to with : specifying the alignment (default, left, center, right).  
Each entry row is marked with | Col 1 Item 1 | Col 2 Item 2 | ... |.  
In-line styling can be used in tables.
Result should be like shown below:  
`| ID | Name | Percent | Status |`  
`|---|:---|:---:|---:|`  
`| 1 | *John Doe* | 100% | Active |`  
`| 2 | **Jane Doe** | 94% | Active |`  
`| 3 | ~~Jack~~ | 3% | Deactivated |`  
The above will render:  
| ID | Name | Percent | Status |
|---|:---|:---:|---:|
| 1 | *John Doe* | 100% | Active |
| 2 | **Jane Doe** | 94% | Active |
| 3 | ~~Jack~~ | 3% | Deactivated |

***
***
# Blockquotes
Blockquotes are marked with a > at the start of the line like shown below:
> This is a blockquote = `> Content of blockquote`  

***
***
# Lines
Horrizontal lines are marked with 3 ***, or ___ on alone on a line like shown below:  
***  
= `***`  (astricks line above)  
___  
= `___`  (underscore line above)  

***
***
# Misc Formatting
Text followed by no spaces & 1 new line.
Text followed by 2 spaces & 1 new line.  
Text followed by no spaces & 2 new lines.

Text followed by 2 spaces & 2 new lines.  

Text followed by no spaces & 3 new lines.


Text followed by \ & 1 new line.\
Last Line
