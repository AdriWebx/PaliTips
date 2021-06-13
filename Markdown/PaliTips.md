# PaliTips

## Tip #1

For Unordered lists, you can use `*` `+` `-`. that means these two codes have same output:

```markdown
* Lorem ipsum dolor sit amet
* Consectetur adipiscing elit
* Integer molestie lorem at massa
```

```markdown
+ Lorem ipsum dolor sit amet
* Consectetur adipiscing elit
- Integer molestie lorem at massa
```

## Tip #2

These three codes have same output, because Markdown recognizes that you want to create Ordered lists:

```markdown
1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa
4. Facilisis in pretium nisl aliquet
5. Nulla volutpat aliquam velit
```

```markdown
1. Lorem ipsum dolor sit amet
1. Consectetur adipiscing elit
1. Integer molestie lorem at massa
1. Facilisis in pretium nisl aliquet
1. Nulla volutpat aliquam velit
```

```markdown
1. Lorem ipsum dolor sit amet
8. Consectetur adipiscing elit
112. Integer molestie lorem at massa
9. Facilisis in pretium nisl aliquet
3532. Nulla volutpat aliquam velit
```

Pay attention that the first one should be `1.` , and else it can't recognize Ordered list.


## Tip #3

If you want to add inline code like this in `GitHub & Notion`, you have to put the code in back quote (`` ` ``):

In python for print the type of data, we use `` `print(type())` ``

Output:

In python for print the type of data, we use `print(type())`

## Tip #4

If your code is in a line or more, you can use three back quotes (`` ``` ``) at the beginning:

\```
string = 'paliprox'
print(string.islower()) # True

string = 'PaliProx'
print(string.islower()) # False
\```

Output:

```
string = 'paliprox'
print(string.islower()) # True
  
string = 'PaliProx'
print(string.islower()) # False
```

## Tip #4.1

Many Markdown processors support syntax highlighting for fenced code blocks. This feature allows you to add color highlighting for whatever language your code was written in. To add syntax highlighting, specify a language next to the backticks before the fenced code block.

\```json  
{  
  "firstName": "John",  
  "lastName": "Smith",  
  "age": 25  
}  
\```

Output:

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

## Tip #5

You can add a table in Markdown, and it's very easy!

```markdown
| Option | Description |
| ------ | ----------- |
| data   | path to supply the data templates. |
| engine | engine the default. |
| ext    | extension to be used for dest files. |
```

Output:

![https://github.com/PaliProx/PaliTips/blob/main/Markdown/Lessons/Images/Tip%205.png](https://github.com/PaliProx/PaliTips/blob/main/Markdown/Lessons/Images/Tip%205.png)

## Tip #5.1

If you want align your text to the left, right and center, you have to do somthing like this:

```markdown
| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph____  | Text    | And more _____ |
```

Output:

![https://github.com/PaliProx/PaliTips/blob/main/Markdown/Lessons/Images/Tip%205.1.png](https://github.com/PaliProx/PaliTips/blob/main/Markdown/Lessons/Images/Tip%205.1.png)

## Tip #5.2

For generating tables easier, use this site!

[Markdown Tables generator - TablesGenerator.com](https://www.tablesgenerator.com/markdown_tables)

## Tip #6

To bold and italicize at the same time, You can use these ways:

```markdown
***Important*** text.

**_Important_** text.

__*Important*__ text.

___Important___ text.
```

Output:

***Important*** text.

**_Important_** text.

__*Important*__ text.

___Important___ text.

## Tip #7

Blockquotes can be nested. Add a >> in front of the paragraph you want to nest.

```markdown
> This the first paragraph.
>> And this is the nested paragraph.
>>> And this is another nested paragraph!
```

Output:

![https://github.com/PaliProx/PaliTips/blob/main/Markdown/Lessons/Images/Tip%207.png](https://github.com/PaliProx/PaliTips/blob/main/Markdown/Lessons/Images/Tip%207.png)

## Tip #8

If you want to give an element an id as HTML, you have to act like this:

```markdown
### My Great Heading {#custom-id}
```

## Tip #8.1

If you have an element with an id and you want to link to it, this is how you act:

```markdown
[see the custom ID](#custom-id)
```

## Tip #9

For commenting in Markdown, you can act two ways:

```markdown
<!-- PaliProx -->
[something]: <> (This is a comment, it will not be included)
```

## Tip #10

For creating a horizontal lines, you can use three or more asterisks (***), dashes (---), or
underscores (___) on a line by themselves.

```markdown
a

***
b

---
c
___
```

Output:

a

---

b

---

c

---

## Tip #11

If you want to add a title to the links or images, you have to act like the code below:

```markdown
I'm using [Google](https://google.com "My search engine!")
```

Output:

![https://github.com/PaliProx/PaliTips/blob/main/Markdown/Lessons/Images/Tip%2011.png](https://github.com/PaliProx/PaliTips/blob/main/Markdown/Lessons/Images/Tip%2011.png)

## Tip #12

To quickly turn a URL or email address into a link, enclose it in angle brackets:

```markdown
<https://google.com>
<fake@example.com>
```
Output:
<https://google.com>
<fake@example.com>

## Tip #13

For making a text italic, you have two options:

```markdown
_italic 1_
*italic 2*
```

Output:

*italic 1*

*italic 2*

## Tip #14

If you write a URL alone, it'll link to the page automatically, but if you don't want to happen that, you should put your URL in (`` ` ` ``):

```
www.example.com

`www.example.com`
```

Output:

www.example.com

`www.example.com`

## Tip #15

Markdown supports task lists and you can create one:

```markdown
- [x] Feeding the birds
- [ ] Listening to the songs
- [x] Writing PaliTips
```

Output:

- [x]  Feeding the birds
- [ ]  Listening to the songs
- [x]  Writing PaliTips

## Tip #16

For strikethrough a text, you have to put it between ~~ ~~ :

```markdown
He ~~have to~~ has to learn python.
```

Output:
He ~~have to~~ has to learn python.

## Tip #17

For creating Definition Lists in Markdown, you have to act this way:

```markdown
First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.
```

Output: 

![https://github.com/PaliProx/PaliTips/blob/main/Markdown/Lessons/Images/Tip%2017.png](https://github.com/PaliProx/PaliTips/blob/main/Markdown/Lessons/Images/Tip%2017.png)

## Tip #18

To add footnotes to your paragraphs (such as Wikipedia pages), use this method:

```markdown
Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

Add as many paragraphs as you like.
```

Output:
(The divider is drawn automatically)

![https://github.com/PaliProx/PaliTips/blob/main/Markdown/Lessons/Images/Tip%2018.png](https://github.com/PaliProx/PaliTips/blob/main/Markdown/Lessons/Images/Tip%2018.png)

## Tip #19

To display the special characters (such as *, -, etc.), you can use backslash (`\`) like python:

```markdown
\* Without the backslash, this would be a bullet in an unordered list.
```

Output:
\* Without the backslash, this would be a bullet in an unordered list.

## Tip #19.1

You can use a backslash to escape the following characters:

backslash (`\`), tick mark (`` ` ``), asterisk (`*`), underscore (Underline) (`_`), curly braces (`{}`), brackets (`[]`), parentheses (`()`), pound sign (`#`), plus sign (`+`), minus sign (hyphen) (`-`), dot (`.`), exclamation mark (`!`), pipe (`|`)

## Tip #20

For escaping tick mark, use double tick mark (``` `` ```):

```markdown
``Use `code` in your Markdown file.``
```

Output:
``Use `code` in your Markdown file.``

## Tip #21

There are two ways to add emoji to Markdown files: [copy and paste the emoji into your Markdown-formatted text](https://emojipedia.org/), or type emoji shortcodes.

Some Markdown applications allow you to insert emoji by typing emoji shortcodes. These begin and end with a colon and include the name of an emoji.

```markdown
Gone camping! :tent: Be back soon.

That is so funny! :joy:
```

The rendered output looks like this:

Gone camping! ⛺ Be back soon.

That is so funny! 😂

## Tip #22

You can write and execute any HTML tags in Markdown! as an example:

```markdown
The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.
```

Output: 

![https://github.com/PaliProx/PaliTips/blob/main/Markdown/Lessons/Images/Tip%2022.png](https://github.com/PaliProx/PaliTips/blob/main/Markdown/Lessons/Images/Tip%2022.png)

## Tip #22.1

Using Markdown doesn’t mean that you can’t also use HTML. You can add HTML tags to any Markdown file. This is helpful if you prefer certain HTML tags to Markdown syntax. For example, some people find that it’s easier to use HTML tags for images.
