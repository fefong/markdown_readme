Getting started with Markdown
=============================


# Titles 

### Title 1
### Title 2

	Title 1
	========================
	Title 2 
	------------------------

# Title 1
## Title 2
### Title 3
#### Title 4
##### Title 5
###### Title 6

    # Title 1
    ## Title 2
    ### Title 3    
    #### Title 4
    ##### Title 5
    ###### Title 6    

# Paragraph
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed dictum, nibh eu commodo posuere, ligula ante dictum neque, vitae pharetra mauris mi a velit. Phasellus eleifend egestas diam, id tincidunt arcu dictum quis. Pellentesque eu dui tempus, tempus massa sed, eleifend tortor. Donec in sem in erat iaculis tincidunt. Fusce condimentum hendrerit turpis nec vehicula. Aliquam finibus nisi vel eros lobortis dictum. Etiam congue tortor libero, quis faucibus ligula gravida a. Suspendisse non pulvinar nisl. Sed malesuada, felis vitae consequat gravida, dui ligula suscipit ligula, nec elementum nulla sem vel dolor. Vivamus augue elit, venenatis non lorem in, volutpat placerat turpis. Nullam et libero at eros vulputate auctor. Duis sed pharetra lacus. Sed egestas ligula vitae libero aliquet, ac imperdiet est ullamcorper. Sed dapibus sem tempus eros dignissim, ac suscipit lectus dapibus. Proin sagittis diam vel urna volutpat, vel ullamcorper urna lobortis. Suspendisse potenti.

Nulla varius risus sapien, nec fringilla massa facilisis sed. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nunc vel ornare erat, eget rhoncus lectus. Suspendisse interdum scelerisque molestie. Aliquam convallis consectetur lorem ut consectetur. Nullam massa libero, cursus et porta ac, consequat eget nibh. Sed faucibus nisl augue, non viverra justo sagittis venenatis.

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed dictum, nibh eu commodo posuere, ligula ante dictum neque, vitae pharetra mauris mi a velit. 
    
    Phasellus eleifend egestas diam, id tincidunt arcu dictum quis.

# List 
* Item 1;
	* Item 1.1;
* Item 2;
	* Item 2.1;
	* Item 2.2;
* Item 3
	* Item 3.1;
		* Item 3.1.1;
    
>      * Item 1;
>	      * Item 1.1;
>	    * Item 2;
>	     * Item 2.1;
>	     * Item 2.2;
>	    * Item 3
>		   * Item 3.1;
>			  * Item 3.1.1;

## List CheckBox

 - [ ] Item A
 - [x] Item B
 - [x] Item C
 
>     - [ ] Item A
>     - [x] Item B
>     - [x] Item C


# Link
[Google](https://www.google.com) - _Google | Youtube | Gmail | Maps | PlayStore | GoogleDrive_

[Youtube](https://www.youtube.com) - _Enjoy videos and music you love, upload original content, and share it with friends, family, and the world on YouTube._

[GitHub](https://github.com/fefong/markdown_readme#getting-started-with-markdown) - _Project_

		[Google](https://www.google.com) - _Google | Youtube | Gmail | Maps | PlayStore | GoogleDrive_

## Anchor links
[Markdown - Titles](#Titles)

[Markdown - Paragraph](#Paragraph)

[Markdown - Link](#Link)

[Markdown - List](#List)

[Markdown - Image](#Image--GIF)

[Markdown - StyleText](#Style-Text)

[Markdown - Code](#Code)

[Markdown - Email](#Email)

[Markdown - Table](#Table)

[Markdown - Escape Characters](#Escape-Characters)

[Markdown - Markdown Editor](#Markdown-Editor)

		[Markdown - Link](#Link)

# Blockquote
> Lebenslangerschicksalsschatz: Lifelong Treasure of Destiny

    > Lebenslangerschicksalsschatz: Lifelong Treasure of Destiny 

# Image | GIF
![myImage](https://media.giphy.com/media/XRB1uf2F9bGOA/giphy.gif)
    
    ![myImage](https://media.giphy.com/media/XRB1uf2F9bGOA/giphy.gif)

# Style Text
### Italic

*Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed dictum, nibh eu commodo posuere, ligula ante dictum neque, vitae pharetra mauris mi a velit.*

     *Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed dictum, nibh eu commodo posuere, ligula ante dictum neque, vitae pharetra mauris mi a velit.*

### Bold
**Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed dictum, nibh eu commodo posuere, ligula ante dictum neque, vitae pharetra mauris mi a velit.**

    **Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed dictum, nibh eu commodo posuere, ligula ante dictum neque, vitae pharetra mauris mi a velit.**
    
### Strikethrough
~~strikethrough text~~

    ~~strikethrough text~~
    
# Code

```java
public static void main(String[] args) {
	//TODO
}
```

>   \`\`\`java <br>
>   public static void main(String[] args) {<br>
>	    //TODO<br>
>	}<br>
>   \`\`\`<br>

# Email
<email@email.com>

    <email@email.com>

# Table

|Column 1|Column 2|Column 3|
|---|---|---|
|Row 1 Column1| Row 1 Column 2| Row 1 Column 3|
|Row 2 Column1| Row 2 Column 2| Row 2 Column 3|

>\|Column 1|Column 2|Column 3|<br>
>\|---|---|---|<br>
>\|Row 1 Column1| Row 1 Column 2| Row 1 Column 3|<br>
>\|Row 2 Column1| Row 2 Column 2| Row 2 Column 3|<br>

## Table Align

## Align Center

|Column 1|Column 2|Column 3|
|:---:|:---:|:---:|
|Row 1 Column1| Row 1 Column 2| Row 1 Column 3|
|Row 2 Column1| Row 2 Column 2| Row 2 Column 3|

>\|Column 1|Column 2|Column 3|<br>
>\|:---:|:---:|:---:|<br>
>\|Row 1 Column1| Row 1 Column 2| Row 1 Column 3|<br>
>\|Row 2 Column1| Row 2 Column 2| Row 2 Column 3|<br>

## Align Right

|Column 1|Column 2|Column 3|
|:---|:---|:---|
|Row 1 Column1| Row 1 Column 2| Row 1 Column 3|
|Row 2 Column1| Row 2 Column 2| Row 2 Column 3|

>\|Column 1|Column 2|Column 3|<br>
>\|:---|:---|:---|<br>
>\|Row 1 Column1| Row 1 Column 2| Row 1 Column 3|<br>
>\|Row 2 Column1| Row 2 Column 2| Row 2 Column 3|<br>

## Align Left

|Column 1|Column 2|Column 3|
|---:|---:|---:|
|Row 1 Column1| Row 1 Column 2| Row 1 Column 3|
|Row 2 Column1| Row 2 Column 2| Row 2 Column 3|

>\|Column 1|Column 2|Column 3|<br>
>\|---:|---:|---:|<br>
>\|Row 1 Column1| Row 1 Column 2| Row 1 Column 3|<br>
>\|Row 2 Column1| Row 2 Column 2| Row 2 Column 3|<br>


# Escape Characters

```
\   backslash
`   backtick
*   asterisk
_   underscore
{}  curly braces
[]  square brackets
()  parentheses
#   hash mark
+   plus sign
-   minus sign (hyphen)
.   dot
!   exclamation mark
```

# Markdown Editor

[StackEdit](https://stackedit.io) - _StackEdit’s Markdown syntax highlighting is unique. The refined text formatting of the editor helps you visualize the final rendering of your files._
