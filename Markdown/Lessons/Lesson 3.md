# Lesson 3

# **Links**

---

We'll now learn how to make links to other web sites on the world wide web.

There are two different link types in Markdown, but both of them render the exact same way. The first link style is called an *inline link*. To create an inline link, you wrap the link text in brackets (`[ ]`), and then you wrap the link in parenthesis (`( )`). For example, to create a hyperlink to www.github.com, with a link text that says, Visit GitHub!, you'd write this in Markdown: `[Visit GitHub!](www.github.com)`.

In the box below, make a link to www.google.com, with link text that says "Search for it."

```markdown
Search for it.()
```

<details>
<summary>Show the answer</summary>

```markdown
[Search for it.](www.google.com)
```
</details>

---

Nice work!

You can add emphasis to link texts if you like. In the box below, make the phrase "really, really" bold, and have the entire sentence link to www.dailykitten.com. You'll want to make sure that the bold phrasing occurs within the link text brackets.

```markdown
You're really, really going to want to see this.
```
<details>
<summary>Show the answer</summary>

```markdown
[You're **really, really** going to want to see this.](www.dailykitten.com)
```
</details>


---

Fantastic!

Although it might make for an awkward experience, you can make links within headings, too.

For this next tutorial, make the text a heading four, and turn the phrase "the BBC" into a link to www.bbc.com/news:

```markdown
The Latest News from the BBC
```
<details>
<summary>Show the answer</summary>

```markdown
#### The Latest News from [the BBC](www.bbc.com/news)
```
</details>

---

That's all there is to writing inline links.

The other link type is called a *reference* link. As the name implies, the link is actually a reference to another place in the document. Here's an example of what we mean:

```markdown
Here's [a link to something else][another place].
Here's [yet another link][another-link].
And now back to [the first link][another place].

[another place]: www.github.com
[another-link]: www.google.com
```

The "references" above are the second set of brackets: `[another place]` and `[another-link]`. At the bottom of a Markdown document, these brackets are defined as proper links to outside websites. An advantage of the reference link style is that multiple links to the same place only need to be updated once. For example, if we decide to make all of the `[another place]` links go somewhere else, we only have to change the single reference link.

Reference links don't appear in the rendered Markdown. You define them by providing the same tag name wrapped in brackets, followed by a colon, followed by the link.

In the box below, we've started writing out some reference links. You'll need to finish them up! Call the first reference tag "a fun place", and make it link to www.zombo.com; make the second link out to www.stumbleupon.com.

```markdown
Do you want to [see something fun][]?

Well, do I have [the website for you][another fun place]!
```
<details>
<summary>Show the answer</summary>

```markdown
Do you want to [see something fun][a fun place]?

Well, do I have [the website for you][another fun place]!

[a fun place]: www.zombo.com
[another fun place]: www.stumbleupon.com
```
</details>

---

You now know how to make links in Markdown!

[On to the next lesson!](Lesson%204.md)

