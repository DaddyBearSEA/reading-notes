## Markdown Notes - [Markdown Basic Writing / Syntax](https://help.github.com/en/articles/basic-writing-and-formatting-syntax)

[Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)


> hyperlink is a Square Bracket followed w/o spaces in a normal bracket
`[` hyperlink text `]``(`webaddress`)`

### Lists numbered and bulleted
Numbered lists are `1.` `2.` `3.`
1. Item 1
2. Item 2
3. Item 3

 or `1.` `1.` `1.`
 
1. Item 1
1. Item 2
1. Item 3

The "`1`" multiple times is easier because long lists you don't have to worry about the numbering of the list


**`*` or `-` are used for bullets and spacing after would indent and make the bullet different**

Here is a bullet list done with `*`
* Bullet one
* Bullet two
  * first indent item one
    * second indent item one
    * second indent item two
  * first indent item two
  * first indent item three


Here is a bullet list done with `-`
- Bullet one
- Bullet two
  -  first indent item one
     - second indent item one
     - second indent item two
  - first indent item two
  - first indent item three

Advance Formatting

Creating a table
You can create tables with pipes | and hyphens -. Hyphens are used to create each column's header, while pipes separate each column. You must include a blank line before your table in order for it to correctly render.


| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
Rendered table

The pipes on either end of the table are optional.

Cells can vary in width and do not need to be perfectly aligned within columns. There must be at least three hyphens in each column of the header row.

| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |
Rendered table with varied cell width


[go back](README.md)