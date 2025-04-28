# THIS IS A MARKDOWN COURSES NOTES   

=============Heading=================

To create a heading, add number signs (#) in front of a word or phrase. The number of number signs you use should correspond to the heading level.   
You should also put blank lines before and after a heading for compatibility.    

## PARAGRAPHS 

To create paragraphs, use a blank line to separate one or more lines of text.  
Unless the paragraph is in a list, don't indent paragraph with spaces or tabs.  

## LINE BREAKS   

To create a line break, end a line with two or more spaces, and then type return.   

## EMPHASIS  

You can add emphasis by marking text bold or italic.

## BOLD   

To bold text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters.  

**Italic**  

To italicize text, add one asterisk or underscore before and after a word or phrase. To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters.   

**BOLD AND ITALIC**   

To emphasize text with bold and italics at the same time, add three asterisks or underscores before and after a word or phrase.  
Examples:   

***test*** text.   
__test__ text.   

The *cat's meow*.  

## BLOCKQUOTES   

To create a blockquote, add a > in front of a paragraph but if it does not work add blockquote as we do in HTML.  

Example: <blockquote> I love learning Python, JavaScript, React, Java, MySQL, and so on. </blockquote> 

**Blockquotes with Multiple Paragraphs**   

Blockquotes can contain multiple paragraphs. Add a > on the blank line between the paragraphs.   

Examples:   
> Lorem[space][space]
ipsum[space][space]
dolor sit amet    


> this is just a blockquote test  
>   
> this is a multiple blockquote test     


**Nested Blockquotes**   

Blockquotes can be nested. Add a >> in front of the paragraph you want to nest.   

Examples:   
> this is a nested test blockquote   
>   
>> and this is the nested paragraph   

**Blockquotes with other elements**   

Blockquotes can contain other Markdown formatted elements. Not all elements can be used.   
Examples:   
> ##### The quaterly results look great !    
>   
> - Revenue was off the chart.   
> - Profits were higher than ever.   
>   
>  *Everything* is going **well**   


## LISTS   

You can organize items into ordered and unordered lists.   

**Ordered Lists**   

To create an ordered list , add line items with numbers followed by periods. The numbers don't have to be in numerical order, but the list should start with the number one.   

1. this is a list item   
2. this is the second list item   
3. this is the third list item  

**Nesting List Items**   

To nest line items in an ordered list , indent the items fours spaces or one tab.     

1. this is a nested list test   
2. here, we will nest this item   
    1. the first nested item test   
    2. the second nested item test   

**Unordered Lists**   

To create an unordered list, add dashes (-), asterisks(*), or plus signs (+) in front of line items.    

- this is the first unordered list  
- this is a the second unordered list   

* this is the other way to do an unordered list   
* this is the second unordered list test     
+ this is the last way to do an unordered list     

**Nesting List Items**    

To nest line items in an unordered list, indent the items four spaces or one tab.   

- first item   
- second item   
- third item  
   - indented item   
   - indented item   
- fourth item   

**Adding Elements in Lists**     

To add another element in a list while preserving the continuity of the list, indent the element four spaces or one tab.   

###### **Paragraphs**   

*    This is a list with a paragraph.   
*    here is my second list item.    

     I need to add another paragraph below the second list item.     

*    And here is the third list item.      

###### **Blockquotes**       

*    This is the first list item with the blockquote    
*    Here's the second list item.    

     > A blockquote would look great here.       

*    And here's the third list item.      

**Code Blocks**    

Code blocks are normally indented four spaces or one tab. when they're in a list, indent them eight spaces or two tabs. You can create fenced code blocks by placing triple backticks before and after the code block. We recommend placing a blank line before and after code blocks to make the raw formatting easier to read.    

```        
function test(){
    console.log("hello world")
}   
```          

###  Images     

You can add images to Markdown using the [alt text](images_url)     

![Alt text](./image1.jpg "image test")         


### Escaping Tick Marks       

if the word or phrase you want to denote as code includes one or more tick marks, you can escape it by enclosing the word or phrase in double tick marks (").        

``Use `code` in your Markdown file. ``     

## Horizontal Rules      

To create a horizontal rule, use three or more asterisks (***), daskes(---), or underscores(___) on a line by themselves.       

***  

___    

---      

## Links      

To create a link, enclose the link text in brackets(eg. [Duck Duck Go]) and then follow it immediately with the URL in parentheses(eg, (https://duckduckgo.com)).    

A tutorial [Please find Markdown Tutorial Here](https://www.markdownguide.org/)    

**ADDING TITLES**    

You can optionally add a title for a link. This will appear as a tooltip when the user hovers over the link. To add a title, enclose it in parentheses after the URL.   

[Markdown Tutorial here](https://www.markdownguide.org/ "Learn how to write a documentation with Markdown")      


## URLs and Email Addresses     

To quickly turn a URL or email address into a link, enclose it in angle brackets.     

<https://www.markdownguide.org/>     
   

<marthe.ekoule@gmail.com>     


## Formatting Links      

To emphasize links, add asterisks before and after the brackets and parentheses.     

I love learning programming language **[Python](https://docs.python.org/3/tutorial/index.html)**   
This is the *[EFF](https://eff.org)* .    

## Escaping Characters      

To display a literal character that would otherwise be used to format text in a Markdown document, add a backslash (\) in front of the character.      

\* Without the backslash, this would be a bullet in an unordered list.   


## Tables   

To add a table, use three or more hyphens (---) to create each column's header, and use pipes (|) to separate each column. You can optionally add pipes on either end of the table.     

| Syntax    | Description   |   
|-----------|---------------|  
| Header    | Title         |     
|Paragraph  | Text          |       



#  TASK LISTS      

Task list allow you to create a list of item with checkboxes. In Markdown application that support task list, checkboxes will be displayed next to the content. To create a task list, add dashes (-) and brackets with a space ([]) in front of task list items. To select a checkbox, add an x in between the brackets ([x]).      

- [x] write the press release  
- [ ] update the website    
- [ ] contact the media         


[Learn AI with Python](https://www.youtube.com/watch?v=5NgNicANyqM&t=1765s "Learn Artificial Intelligence from Harvard")   

Notice: Markdown does not officially support video embeddings but you can embed raw HTML in it. 






End!!!!!!!!!!!!!





   






























