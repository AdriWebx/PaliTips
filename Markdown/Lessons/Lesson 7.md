# Lesson 7

# Paragraphs

---

Markdown has several ways of formatting paragraphs.

Let's take a few lines of poetry as an example. Suppose you want to write text that looks like this:

Do I contradict myself?Very well then I contradict myself,(I am large, I contain multitudes.)

Now, you might think that simply typing each verse onto its own line would be enough to solve the problem:

```markdown
Do I contradict myself?
Very well then I contradict myself,
(I am large, I contain multitudes.)

```

Unfortunately, you'd be wrong! This Markdown would render simply as a single straight line: Do I contradict myself? Very well then I contradict myself, (I am large, I contain multitudes.).

If you forcefully insert a new line, you end up breaking the togetherness:

```markdown
Do I contradict myself?

Very well then I contradict myself,

(I am large, I contain multitudes.)

```

This is what's known as a *hard break*; what our poetry asks for is a *soft break*. You can accomplish this by inserting two spaces *after* each new line. This is not possible to see, since spaces are invisible, but it'd look something like this:

```markdown
Do I contradict myself?··
Very well then I contradict myself,··
(I am large, I contain multitudes.)

```

Each dot ( `·` ) represents a space on the keyboard.

Let's try this technique out. In the box below, insert the necessary number of spaces to make the poem render correctly:


```markdown
We pictured the meek mild creatures where
They dwelt in their strawy pen,
Nor did it occur to one of us there
To doubt they were kneeling then.
```

<details>
<summary>Show the answer</summary>

```markdown
We pictured the meek mild creatures where  
They dwelt in their strawy pen,  
Nor did it occur to one of us there  
To doubt they were kneeling then.
```
</details>

---

Fantastic work!

Aside from formatting poetry, one of the common uses for these soft breaks is in formatting paragraphs in lists. Recall in the previous lesson that we inserted a new line for multiple paragraphs within a list.

In the box below, instead of using hard breaks, tighten the sub-paragraphs with soft breaks:

```markdown
1. Crack three eggs over a bowl.

Now, you're going to want to crack the eggs in such a way that you don't make a mess.

 If you _do_ make a mess, use a towel to clean it up!

2. Pour a gallon of milk into the bowl.

 Basically, take the same guidance as above: don't be messy, but if you are, clean it up!
```

<details>
<summary>Show the answer</summary>

```markdown
1. Crack three eggs over a bowl.  
Now, you're going to want to crack the eggs in such a way that you don't make a mess.  
If you _do_ make a mess, use a towel to clean it up!

2. Pour a gallon of milk into the bowl.  
Basically, take the same guidance as above: don't be messy, but if you are, clean it up!
```
</details>

---

Et voila! You now know how to make soft breaks in Markdown!

---

# You’ve completed all the lessons!

Believe it or not, we’ve only just begun exploring what can be accomplished with Markdown. There are many “extended” implementations of Markdown that support formats like tables, definition lists, footnotes, and more. Because they’re non-standard, they’re not essential to learning the basics, as we’ve introduced here.

If you’d like to know more about these Markdown implementations, check the [PaliTips](PaliTips.md)!

