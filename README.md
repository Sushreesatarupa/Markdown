## Markdown

- Markdown is a lightweight markup language. It allows you to style a digital text document using typical formatting techniques: for example, headings, emphasis, lists, images, and links. Markdown files have extensions .md or .markdown. Also, Markdown can also be converted into XHTML or HTML to display nicely in a browser.

- Some of the many uses of Markdown are readme files, writing messages in online discussion forums, creating rich text using a plain text editor, emails, and technical documentation. Popular sites that use Markdown include GitHub, Trello, Reddit, SourceForge, and StackExchange, among many others.

- Writers can have as much control over the presentation of their information without resorting to complete HTML tagging. At the same time, Markdown parsers also support dropping in blocks of HTML code that add to Markdown’s limited syntax if you want to achieve a more complex design. 

### Why use Markdown?
- It makes it easier for non-tech writers to produce documentation that can be collaborative and flexible at the same time.

- You don't even have to be a developer to pick up the basics. The advantage of Markdown is that it's straightforward to write once you know how it works. It's intuitively easy to pick up because it has a base of email formatting conventions that many people are exposed to already.

- You can also easily read Markdown in its raw state, unlike, for example, plain HTML, which is full of tags. The Markdown syntax flows perfectly with the rest of your writing, and it's intuitively clear what the syntax means.

- Markdown is platform-independent, which means you can create Markdown files in any text editor. It's applicable across many different websites and applications.

- It's a reusable skill. Markdown is versatile, so you learn it once, and you can use it for lots of different activities. You can use Markdown to take notes, create content for a website, or produce print-ready documents.

# Basics of Markdown

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6


- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
---


## Headings
All Markdown files should contain headers. You need a level 1 header for the title of your Markdown file, and at least level 2 headers for the subheadings within the body text. Headings make your text more readable and help to break up the topics.

In Markdown, headings are formatted with hashes (#) in front of the line containing your heading. You can use up to six hashes, with the number of hashes corresponding to a heading level.

```markdown
# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6
```
Your text will look like this:
# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6

---

## Paragraphs
When writing your Markdown body text, you’ll likely want to split your information up into paragraphs (with a noticeable gap between each paragraph). Paragraphs are divided by a blank line (a line containing no characters) between consecutive paragraphs.

Your text will look like this:
Paragraph 1

Paragraph 2
---
## Line breaks

Sometimes, you’ll want to split your information up by inserting a new line, with less space than you’d get from formatting as a paragraph. This is called a line break.

To insert a line break into your Markdown file, finish your line with at least two spaces and press return. This will render a new line for your text.

Your text will look like this:
Line 1
Line 2
---
## Formatting text in Markdown
To format the text, follow these rules:
<br>

```markdown
- The formatted text will look like this:
- For italics, wrap the item with one star on each side: *one star on each side*.
- For bold text, wrap the item with two stars on each side: **two stars on each side**.
- For striking through text in GitHub Markdown, wrap the item in two tildes: ~~strikethrough~~.
- For links, wrap link text in brackets [ ], and then wrap the URL in parentheses ( ): [This text links to WritetheDocs](https://www.writethedocs.org).
```

- The formatted text will look like this:
- For italics, wrap the item with one star on each side: *one star on each side*.
- For bold text, wrap the item with two stars on each side: **two stars on each side**.
- For striking through text in GitHub Markdown, wrap the item in two tildes: ~~strikethrough~~.
- For links, wrap link text in brackets [ ], and then wrap the URL in parentheses ( ): [This text links to WritetheDocs](https://www.writethedocs.org).

---

## Emphasis
When writing your content in Markdown, you might want to place a bit more emphasis on certain words or phrases. The first way you can emphasise your text is in italics.

You can make your text italic by wrapping your text with one asterisk on each side (alternatively, you can use underscores in place of the asterisks). Once your application detects the second asterisk, your formatting for this element is considered “closed”.
Your text will look like this:
  *This text is italic*
  _This text is also italic_

Bold formatting provides a slightly heavier emphasis than italics, but it works in exactly the same way. This time, use two asterisks to wrap the text you want to make bold (alternatively, you can use underscores in place of asterisks).
Your text will look like this:
  **This text is bold**
  __This text is also bold__

If you really want to make a point, you can make your text simultaneously bold and italic to give it even more weight! To make your text bold and italic, use three asterisks (or three underscores) to wrap your word or phrase.
Your text will look like this:
  ***This text is italic and bold.***
  ___This text is also italic and bold___

```markdown
*This text is italic*
_This text is also italic_
**This text is bold**
__This text is also bold__
***This text is italic and bold.***
___This text is also italic and bold___

```
## Links (inline)
Sometimes we want to link to external websites when writing Markdown content. There’s a simple way to do this using two sets of brackets.
To format an inline link in Markdown, you use square brackets to wrap your link text. Place the square-bracket wrapped link text alongside parentheses containing your URL (make sure you don’t include a space between the link text and the link).
Your text will look like this:

[This is link text](This is a link URL)
If you want to add title to your link, insert your alt text next to the link inside quotation marks
Your text will look like this:
[This is link text](This is a link URL “This is a title”)

Note that if you want to link to a local file, within the same server as your other Markdown files, you can format your link with a forward slash followed by the relative URL.
Your text will look like this:
[This is link text](/This is a relative URL “This is a title”)

## Images
A picture is worth a thousand words, as they say. Inserting an image into your Markdown file is similar to the formatting for links.

Begin your image formatting with an exclamation mark. Next, use square brackets to wrap your image alt text, next to parentheses containing the URL for your image. Ensure there are no spaces between the exclamation mark, square brackets, or parentheses.

```markdown
![image](https://user-images.githubusercontent.com/64991656/132938832-0394a87c-fb2d-4d7d-b478-d1b7c474df80.png)

```

The image will look like this:
<br>
![image](https://user-images.githubusercontent.com/64991656/132938832-0394a87c-fb2d-4d7d-b478-d1b7c474df80.png)

<br> When your Markdown file is rendered to HTML, the image will be embedded directly into the body text.

## Lists
### Unordered lists
Sometimes, you may want to format your content in lists to make it easier to read.

The first option is to use an unordered list, where each item on your list is preceded by a bullet point. Markdown allows you to format your lists with a number of different symbols: asterisks (*), hyphens (-) or plus signs (+).

It’s up to you to choose which symbol you prefer. The result you get is the same.

```markdown
- Just add a dash first and then write a text.
- If you add another dash in the following line, you will have another item in the list.
  - If you add four spaces or use a tab key, you will create an indented list.
    - If you need to insert an indented list within an intended one, just press a tab key again.
```


The formatted text will look like this:
- Just add a dash first and then write a text.
- If you add another dash in the following line, you will have another item in the list.
  - If you add four spaces or use a tab key, you will create an indented list.
    - If you need to insert an indented list within an intended one, just press a tab key again.

Just add a dash first and then write a text.
If you add another dash in the following line, you will have another item in the list.
If you add four spaces or use a tab key, you will create an indented list.
If you need to insert an indented list within an intended one, just press a tab key again.

```markdown
Sometimes you want bullet points:

* Start a line with a star
* Profit!
```
The formatted text will look like this:
* Start a line with a star
* Profit!


### Ordered lists

Other times, you may want to present your information sequentially in ordered lists (1, 2, 3, and so on). Format your ordered lists by preceding each list item with a number, followed by a full stop and then a space.

In Markdown, it doesn’t matter which numbers you use to format your list, as the list will always render as 1, 2, 3, and so on.


```markdown
1. Just type a number followed by a dot.
2. If you want to add a second item, just type in another number followed by a dot.
1. If you make a mistake when typing numbers, fear not, Markdown will correct it for you.
    1. If you press a tab key or type four spaces, you will get an indented list and the numbering
    will start from scratch.
        1. If you want to insert an indented numbered list within an existing indented numbered one,
        just press the tab key again.
            - If need be, you can also add an indented unordered list within an indented numbered one, an vice versa,
            by pressing a tab key and typing a dash.
```
The formatted text will look like this:
1. Just type a number followed by a dot.
2. If you want to add a second item, just type in another number followed by a dot.
1. If you make a mistake when typing numbers, fear not, Markdown will correct it for you.
    1. If you press a tab key or type four spaces, you will get an indented list and the numbering
    will start from scratch.
        1. If you want to insert an indented numbered list within an existing indented numbered one,
        just press the tab key again.
            - If need be, you can also add an indented unordered list within an indented numbered one, an vice versa,
            by pressing a tab key and typing a dash.
            
Just type a number followed by a dot.
- If you want to add a second item, just type in another number followed by a dot.
- If you make a mistake when typing numbers, fear not, Markdown will correct it for you.
- If you press a tab key or type four spaces, you will get an indented list and the numbering will start from scratch.
- If you want to insert an indented numbered list within an existing indented numbered one, just press the tab key again.
- If need be, you can also add an indented unordered list within an indented numbered one, an vice versa, by pressing a tab key and typing a dash.

## Blockquotes

Sometimes in Markdown, we will want to reference an external source using quotation marks. This is called a blockquote. You represent any blockquote by preceding the first line of the block quote with a greater-than sign or angle bracket (>). Gruber recommends inserting the angle bracket before every line of your blockquote.

Your text will look like this:
> This is a blockquote
> This is a blockquote
> This is a blockquote


## Horizontal rules
A horizontal rule is a useful little element that you can use to visually split up blocks of text within your Markdown file. A horizontal rule is represented by three or more hyphens (-), asterisks (*), or underscores (_). Whichever symbol you use renders the same output.

Your text will look like this:
—
```markdown

Create a horizontal rule with three or more hyphens, asterisks, or underscores on a line:
---

* * *

___

```

The formatted text will look like this:
---

* * * 

___

## Code blocks and snippets

Code snippets
Often when we’re writing in Markdown, we need to reference snippets of code as examples. This is particularly common in technical documentation. Markdown allows you to format code snippets using backticks \` that wrap your code snippet. The first backtick “opens” the snippet, and the second backtick “closes” it.
```markdown
`This is a code snippet`
```
Your text will look like this:
`This is a code snippet`

### Code blocks
Formatting code blocks is useful when you have a bigger chunk of code to include in your Markdown file. Format your code blocks by indenting every line of your code block using one tab, or four spaces.
This is a code block
This is a code block
This is a code block

There are many different ways to style code with GitHub's markdown. If you have inline code blocks, wrap them in backticks: `var example = true`.  If you've got a longer block of code, you can indent with four spaces:

    if (isAwesome){
      return true
    }

GitHub also supports something called code fencing, which allows for multiple lines without indentation:
<br>
![image](https://user-images.githubusercontent.com/64991656/132943033-79e52948-fe5b-468e-9803-b7804d4cf9ae.png)
<br>
```
if (isAwesome){
  return true
}
```

And if you'd like to use syntax highlighting, include the language:
<br>
![image](https://user-images.githubusercontent.com/64991656/132943045-21b022e4-8723-4957-b536-f3259ac1a60c.png)
<br>
```javascript
if (isAwesome){
  return true
}
```

## Escaping
Often in Markdown, you will need to include characters in your text (for example, and asterisk) that may be part of the Markdown syntax. You need to “escape” these characters so your Markdown application doesn’t read these characters as formatting.
You escape characters in Markdown using a backslash before the character, with no space in between.
Your text should look like this:
\*
You can escape any of these characters:
```
\ backslash
` backtick
* asterisk
_ underscore
{} curly braces
[] square brackets
() parentheses
# hash symbol
+ plus sign
– minus sign (hyphen)
. dot
! exclamation mark
```
Lists within blockquotes
Sometimes, you might want to insert a blockquote into your Markdown that contains another element, such as an unordered list. You need to nest your list formatting inside your blockquote formatting.
Format your blockquote using a greater-than sign (>) followed by a space, including a sign before every line of your block quote. Add your list formatting (*) just after your greater-than signs.
Your text should look like this:
> This is a blockquote
> * This is a list item within a blockquote
> * This is a list item within a blockquote
> * This is a list item within a blockquote

## HTML
You can insert HTML elements directly into your Markdown file. For example, you may want to include a button. Insert your HTML exactly as you would in any other HTML document.
Your text should look like this:
<button>This is a button</button>
This formatting also works for your other Markdown syntax, such as emphasis. Instead of **This element is bold**, you could format it in HTML as <bold>This element is bold</bold>.




### Quotes
Add a quotation with the > character at the beginning of each line:
```markdown
> “I make Jessica Simpson look like a rock scientist.”

> —Tara Reid, actress
The quote will look like this:

“I make Jessica Simpson look like a rock scientist.”
—Tara Reid, actress
```
> “I make Jessica Simpson look like a rock scientist.”

> —Tara Reid, actress
The quote will look like this:

“I make Jessica Simpson look like a rock scientist.”
—Tara Reid, actress
And finally, insert code into your text with one apostrophe on each side when adding code within one line, or with 3 apostrophes opening and closing your code block, like this:

---
# GitHub Flavored Markdown
GitHub.com uses its own version of the Markdown syntax that provides an additional set of useful features, many of which make it easier to work with content on GitHub.com.

Note that some features of GitHub Flavored Markdown are only available in the descriptions and comments of Issues and Pull Requests. These include @mentions as well as references to SHA-1 hashes, Issues, and Pull Requests. Task Lists are also available in Gist comments and in Gist Markdown files.

#### Syntax highlighting
Here’s an example of how you can use syntax highlighting with GitHub Flavored Markdown:

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
You can also simply indent your code by four spaces:

    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
Here’s an example of Python code without syntax highlighting:

def foo():
    if not bar:
        return True
#### Task Lists
```markdown
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
```
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
If you include a task list in the first comment of an Issue, you will get a handy progress indicator in your issue list. It also works in Pull Requests!

#### Tables
You can create tables by assembling a list of words and dividing them with hyphens - (for the first row), and then separating each column with a pipe |:
```markdown
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
```
![image](https://user-images.githubusercontent.com/64991656/132943951-106683e1-60d8-4c18-bb8a-209213e6ed94.png)

#### Username @mentions
Typing an @ symbol, followed by a username, will notify that person to come and view the comment. This is called an “@mention”, because you’re mentioning the individual. You can also @mention teams within an organization.

#### Automatic linking for URLs
Any URL (like http://www.github.com/) will be automatically converted into a clickable link.

#### Emoji
GitHub supports emoji!

To see a list of every image we support, check out the Emoji Cheat Sheet.

![image](https://user-images.githubusercontent.com/64991656/132938448-e83bc0d0-f37e-4c5e-8a45-2f4443f5c169.png)


