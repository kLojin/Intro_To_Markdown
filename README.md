# INTRODUCTION TO MARKDOWN

<!--HEADING-->
# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

---

<!--Italics-->

_This is a sentence that uses italic styling_, which uses _"underscore"_ as its opening and closing symbol.

*This is a sentence that uses italic styling*, which uses *"asterisk"* as its opening and closing symbol.

---

<!--Strong-->

**This is a sentence that uses strong styling**, which uses **"double asterisk"** as its opening and closing symbol.

__This is a sentence that uses strong styling__, which uses __"double underscore"__ as its opening and closing symbol.

---

<!--Strikethrough-->

~~This is a sentence that uses strikethrough styling~~, which uses ~~"double tilde"~~ as its opening and closing symbol.

---
<!--Horizontal Rule-->

We can add triple hyphens to be able to create a horizontal rule for separating content.

Another way to add __HORIZONTAL RULE__ in our document markdown is by using three underscores
___

<!--Escape Character Rule using Backslash-->

This is an example of a *text with an asterisk*. If we don't want it to be italicized, we have to place a backslash \ before the opening asterisk symbol to escape the rule of using an opening \*asterisk* and closing \*asterisk* enclosing text contents.

---

<!--Blockquote Rule-->

> We use the greater than symbol to display a block of text as a quote with a background and line on the left side.

> *"Action is the Foundational Key to All Success"* --- __Gecko&Fly__

---

<!--Link Rule-->

**NOTE**: We would want to put the link description inside the square brackets and the link to the resource inside the open and close parenthesis.
[kLojin pexels collection profile](https://www.pexels.com/@klo-jin-528825507/)

__NOTE__: We can add a balloon tip description to our link by using double quotes after the link to the resource 
[kLojin pexels collection profile](https://www.pexels.com/@klo-jin-528825507/ "This is kLojin's pexels photo collection")

---

<!--List item rules-->

<!--UNORDERED LISTS-->

* Item 1 - this is going to be our list item 1
  *  This is our list item 1 child item 1
  *  This is our list item 1 child item 2
* Item 2 - this is going to be our list item 2
  *  This is our list item 2 child item 1
  *  This is our list item 2 child item 2
* Item 3 - this is going to be our list item 3
  *  This is our list item 3 child item 1
  *  This is our list item 3 child item 2
* Item 4 - this is going to be our list item 4
  *  This is our list item 4 child item 1
  *  This is our list item 4 child item 2
* Item 5 - this is going to be our list item 5
  *  This is our list item 5 child item 1
  *  This is our list item 5 child item 2

<!--ORDERED LIST-->

1. Item 1 - this is going to be our list item 1
   
    1.1  This is our list item 1 child item 1
  
    1.2  This is our list item 1 child item 2

3. Item 2 - this is going to be our list item 2
   
    2.1  This is our list item 2 child item 1
  
    2.2  This is our list item 2 child item 2

3. Item 3 - this is going to be our list item 3

    3.1  This is our list item 3 child item 1
  
    3.2  This is our list item 3 child item 2

4. Item 4 - this is going to be our list item 4

    4.1  This is our list item 4 child item 1
  
    4.2  This is our list item 4 child item 2

5. Item 5 - this is going to be our list item 5

    5.1  This is our list item 5 child item 1
  
    5.2  This is our list item 5 child item 2

---

<!---Code Block Inline Example Rule-->

**NOTE**: *__Backticks__ will allow us to show the code block or the paragraph tags in this example.*

`<p> This is a paragraph tag with an inline code block example opening and closing tags </p>`

---

<!--IMAGE rule-->

![This is an image](https://images.pexels.com/photos/17925642/pexels-photo-17925642.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1 "Link to a coastal beach image")

---

<!--GITHUB FLAVOR SET OF CODE BLOCK-->

<!--CODE BLOCKS FOR GITHUB DOCUMENTATION-->

```install npm
npm install

npm start
```

**NOTE**: You can specify some syntax code blocks for different languages

```javascript
function jsAdd(num1,num2){
  return num1 + num2;
}
```

```python
def pythonAdd(num1,num2):
  return num1 + num2;
```
```c#
public static int Sum(int num1, int num2)
{
  int total;
  total = num1 + num2;
  return total;
}
```







