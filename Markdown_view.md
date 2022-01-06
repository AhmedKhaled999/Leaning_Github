<!--Headings-->
# Created by : Ahmed Khaled 
# Heading 1 
## Heading 2 
### Heading 3 
#### Heading 4 
##### Heading 5 
###### Heading 6 

---

<!--Italics-->

*This text* is italic

\*This text\* is italic


_This text also _ is italic

<!--Strong-->

---

**This text** is bold

__This text also__ is bold


<!--Strikethrough-->
~~This text~~ is strikethrough

<!--Horizontal Rule-->

___

<!--Blockquote-->
> this is a qute

<!--Links-->
[basic-writing-and-formatting-syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
"Github Docs")

[Common Git commands](https://github.com/RahmaYasser/common-git-commands
"Common Git commands as a title")


<!--UL-->   
* Item 1 
* Item 2
* Item 3
  * Nested Item 1
  * Nested Item 2

<!--OL-->
1. Item 1
1. Item 2
1. Item 3

___

<!--Inline Code Block-->
<p>This is a paragraph</p>


<!--Images-->
![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)

<!--Code Blocks-->

--- 

```bash
  npm install 
  
  npm start
```

```javascript
  function add(num1,num2){
   return num1 + num2; 
  }
```

```python
   def add(num1,num2):
     return num1 + num2 
``` 
<!--Tables-->
| Name   |Email     | 
|--------|----------|
| Ahmed  |ak@99.com |
| Khaled |ak@39.com |

<!--Task Lists-->
* [x] Task 1 
* [x] Task 2 
* [ ] Task 3
---
<!--Markdown_details-collapsible-->

# A collapsible section with markdown
<details>
  <summary>Click to expand!</summary>

## Heading
1. A numbered
2. list
  * With some
  * Sub bullets
</details>

# A collapsible section with code
<details>
  <summary>Click to expand!</summary>

```bash
  npm install 
  
  npm start
```

```javascript
  function add(num1,num2){
   return num1 + num2; 
  }
```

```python
   def add(num1,num2):
     return num1 + num2 
``` 
</details>

**NB:** Make sure you have an **empty line** after the closing `</summmary>` tag.

**NB:** Make sure you have an **empty line** after the closing `</details>` tag if you have
multiple collapsible sections.

