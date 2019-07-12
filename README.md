## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/antzm/code-test/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).


### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

---

# How to make a simple web page on GitHub

* A web page with text and images
* Fully customizable
* Easy to create and easy to update
* No coding exprerience required
* The only language you will need is called Markown

## Creating your page:
1. Create a GitHub account at www.github.io
2. Let's assume you username on GitHub is: `user-name`
3. So, from now on, wherever it is mentioned `user-name,` you will just replace it your own GitHub username.
4. Create a new repository with this name (exactly this name): `user-name.github.io`
5. Give a description to your repository, choose to be public and choose to create a README file. Leave other options as they are.
6. As soon as your new repository is created, go to the top of the page, and click `settings`
7. Under `GitHub Pages`, select `Master Branch`
8. If you want, under 'Theme Choser', select a theme
9. Now, you've done everything and your web page is being prepared
10. After 10 minutes, your page will be published at `https://user-name.github.io`

## Updating your content:

Visiting your new web page, the only thing you will see is the name of your repository and the description you wrote. To include more content in your web page, you can edit the `README.md` file in your repository using a language called `Markdown`

---

# Creating a Markdown file

Open "Notepad" on Windows, or a similar application on other operating systems.

Start typing the text that you would like to appear on your personal web page.

Save your file as "my-file.md"

(On notepad, just use quotes to write the name of the file and give it the extension .md)

In the following tables, you will find everything you need   
on how to format the text you are writting using Markdown:

(The markdown syntax is shown in the highlighted window and just below is a preview of that Markdown)

---

## Headers

```
# This is a level 1 heading
## This is a level 2 heading
### This is a level 3 heading
#### this is a level 4 heading
##### this is a level 5 heading
###### this is a level 6 heading
```

# This is a level 1 heading
## This is a level 2 heading
### This is a level 3 heading
#### this is a level 4 heading
##### this is a level 5 heading
###### this is a level 6 heading
---

## Font styles

```
**this thext is bold**
_this text is italized_

```
**this thext is bold**    
_this text is italized_  

```
**combination of _italized text_ inside bold text**
_combination of **bold text** inside italized text_
```
**combination of _italized text_ inside bold text**  
_combination of **bold text** inside italized text_

---

## Tables:

```
header one | header two | header three
-----------|------------| ------------
first item in #1 | first item in #2 | first item in # 3
second item in # 1 | second item in # 2 | second item in # 3
third item in # 1 | third item in # 2 | third itemm in # 3
```

header one | header two | header three
-----------|------------| ------------
first item in #1 | first item in #2 | first item in # 3
second item in # 1 | second item in # 2 | second item in # 3
third item in # 1 | third item in # 2 | third itemm in # 3

```
items align left | items align center | items align right
:---   |   :---:   |   ---:
item 1a | item 2a | item 3a
item 1b | item 2b | item 3b
item 1c | item 2c | item 3c
```

items align left | items align center | items align right
:---   |   :---:   |   ---:
item 1a | item 2a | item 3a
item 1b | item 2b | item 3b
item 1c | item 2c | item 3c

---

## Unordered Lists:

```
* first item
* second item
* third item
```

* first item
* second item
* third item

```
* first item
* second item
   * second item a
   * second item b
   * second item c
* third item
   * third item a
   * third item b
   * third item c
```

* first item
* second item
   * second item a
   * second item b
   * second item c
* third item
   * third item a
   * third item b
   * third item c

---

## Ordered Lists:

```
1. first item
2. second item
3. third item
```

1. first item
2. second item
3. third item

```
1. first item
2. second item
   1. second item a
   2. second item b
   3. second item c
3. third item
   1. third item a
   2. third item b
   3. third item c
```

1. first item
2. second item
   1. second item a
   2. second item b
   3. second item c
3. third item
   1. third item a
   2. third item b
   3. third item c

---

## Task Lists:

```
* [ ] unchecked item 1
* [x] checked item 2
* [x] checked item 3
```

* [ ] unchecked item 1
* [x] checked item 2
* [x] checked item 3

```
* [ ] unchecked item 1
    * [ ] subitem 1a
    * [ ] subitem 1b
* [x] checked item 2
* [x] checked item 3
    * [x] subitem 3a
```

* [ ] unchecked item 1
    * [ ] subitem 1a
    * [ ] subitem 1b
* [x] checked item 2
* [x] checked item 3
    * [x] subitem 3a

---

## Links:

```
https://www.google.com
```
https://www.google.com

```
[GitHub](http://github.com)
```
[GitHub](http://github.com)

---

## Code:

`` this is an `inline code` example ``

this is an `inline code` example

````
```
This is a longer

code example
```
````

```
This is a longer

code example
```
---

## Code highlighting:

### JavaScript:
````
```javascript
for (i=0; i<10; i++) {
  console.log(i);
}
```
````

```javascript
for (i=0; i<10; i++) {
  console.log(i);
}
```

### HTML:
````
```html
<section class="intro">
   <h1 class="intro-heading">intro heading</h1>
   <p class="intro-text">intro text</p>
</section>
```
````

```html
<section class="intro">
   <h1 class="intro-heading">intro heading</h1>
   <p class="intro-text">intro text</p>
</section>
```

### CSS:
````
```css
.intro {
   margin: 0;
   padding: 0;
   color: #1f3d7a;
   font: Verdana, Arial, sans-serif;
}
```
````

```css
.intro {
   margin: 0;
   padding: 0;
   color: #1f3d7a;
   font: Verdana, Arial, sans-serif;
}
```
---

## Quote:

```
>“We change the world not by what we say or do, but as a consequence of what we have become.”
— David R. Hawkins
```
>“We change the world not by what we say or do, but as a consequence of what we have become.”
— David R. Hawkins

---

## Images:

```
![a brown and white dog laying on the floor and looking at the camera](imgs/merfys.jpg)
```

![a brown and white dog laying on the floor and looking at the camera](imgs/merfys.jpg)

---

## Clickable Images

First, write the code for the link and the code for the image:

```

Link:
[Merfy's GitHub Page](https://antzm.github.io/)

Image:
![Merfy's the dog looking at the camera](imgs/merfys.jpg)

```

Now, use the code for the link and replace whatever is inside the `[...]` with the full code of the image:

```

Clickable Image:
[![Merfy's the dog looking at the camera](imgs/merfys.jpg)](https://antzm.github.io/)


```

[![Merfy's the dog looking at the camera](imgs/merfys.jpg)](https://antzm.github.io/)
