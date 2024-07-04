---
title: 'How-to Markdown-01'
date: 2024-04-10
permalink: /posts/2024/04/learning-markdown-01/
tags:
  - markdown
---

Notes for Markdown learning. 

[Markdown Documentation](https://www.markdownguide.org)
## Headings
```
# Heading Level 1 | <h1>Heading Level 1</h1>

## Heading Level 2 | <h2>Heading Level 2</h2>
```
## Paragraph
```
<p>This is a paragraph with one;<br>
two; and <br>
three lines.</p>
```
## Enphasis 
### Bold
```
I just love **bold text**.

HTML:
I just love <strong>bold text</strong>.
```
### Italic
```
Italicized text is the *cat's meow*.

HMTL:
Italicized text is the <em>cat's meow</em>.
```
### Italic + Bold
```
This text is ***really import***.

HMTL:
This text is <em><strong>really important</strong></em>.
```
## Blockquotes
```
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
> *Everything* is going according to **plan**.
>
> Dorothy followed her through many of the beautiful rooms in her castle.
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
>
```
## Ordered Lists
```
1. First
2. Second
3. Third
	1. Indented 
	2. Indented
4. Fourth

HMTL:
<ol>
	<li>First</li>
	<li>Second</li>
	<li>Third
		<ol>
			<li>Indented</li>
			<li>Indented</li>
		</ol>
	</li>
	<li>Fourth</li>
</ol>
```
## Unordered Lists
```
- First
- Second
- Third
	- Idented
	- Idented
- Fourth

HTML:
<ul>
	<li>First</li>
	<li>Second</li>
	<li>Third
		<ul>
			<li>Indented</li>
			<li>Indented</li>
		</ul>
	</li>
	<li>Fourth</li>
</ul>
```
## Code
```
At the command prompt, type `nano`.

HTML:
At the command prompt, type <code>nano</code>. or
<code>Use `code` in your Markdown file.</code>
```
## Horizontal Rules
```
Try to put a blank line before...

---

...and after a horizontal rule.
```
## Links
```
My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

or 

My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").
```
## Images
```
![The San Juan Mountains are beautiful!](/assets/images/san-juan-mountains.jpg "San Juan Mountains")
```
## Tables
```
| Syntax | Description |
| --- | ----------- |
| Header | Title |
| Paragraph | Text |

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |
```
## Fenced Code Blocks
````
```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
````
## Footnotes
```
Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.
```
## Heading IDs
```
### My Great Heading {#custom-id}  obs: heading of page
[Heading IDs](#heading-ids)        obs: jump link to heading on page

HMTL VERSION:
<h3 id="custom-id">My Great Heading</h3>
<a href="#heading-ids">Heading IDs</a>
```
## Definition Lists
```
First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

HMTL:
<dl>
  <dt>First Term</dt>
  <dd>This is the definition of the first term.</dd>
  <dt>Second Term</dt>
  <dd>This is one definition of the second term. </dd>
  <dd>This is another definition of the second term.</dd>
</dl>
```
## Strikethrough
```
~~The world is flat.~~ We now know that the world is round.
```
## Task Lists
```
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
```
## Emoji
```
Gone camping! :tent: Be back soon.

That is so funny! :joy:
```
## Highlight
```
I need to highlight these ==very important words==.

HTML:
I need to highlight these <mark>very important words</mark>.
```
## Subscript
```
H~2~O

HTML:
H<sub>2</sub>O
```
## Superscript
```
X^2^

HMTL:
X<sup>2</sup>
```
## Automatic URL Linking
```
http://www.example.com
```
## Disabling Automatic URL Linking
```
`http://www.example.com`
```