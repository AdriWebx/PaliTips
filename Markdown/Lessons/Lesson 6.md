# Lesson 6

# **Lists**

---

This tutorial is all about creating lists in Markdown.

There are two types of lists in the known universe: unordered and ordered. That's a fancy way of saying that there are lists with bullet points, and lists with numbers.

To create an unordered list, you'll want to preface each item in the list with an asterisk ( `*` ). Each list item also gets its own line. For example, a grocery list in Markdown might look like this:

```markdown
* Milk
* Eggs
* Salmon
* Butter

```

This Markdown list would render into the following bullet points:

- Milk
- Eggs
- Salmon
- Butter

In the box below, turn the words separated by a comma into a list.

```markdown
Flour, Cheese, Tomatoes
```

<details>
<summary>Show the answer</summary>

```markdown
* Flour
* Cheese
* Tomatoes
```
</details>

---

All right! That's how you write an unordered list. Now, let's talk about ordered ones.

An ordered list is prefaced with numbers, instead of asterisks. Take a look at this recipe:

1. Crack three eggs over a bowl
2. Pour a gallon of milk into the bowl
3. Rub the salmon vigorously with butter
4. Drop the salmon into the egg-milk bowl

To write that in Markdown, you'd do this:

```markdown
1. Crack three eggs over a bowl
2. Pour a gallon of milk into the bowl
3. Rub the salmon vigorously with butter
4. Drop the salmon into the egg-milk bowl

```

Easy, right? It's just like you'd expect a list to look.

In the box below, turn the rest of the recipe into an ordered list.

```markdown
Cut the cheese, Slice the tomatoes, Rub the tomatoes in flour
```
<details>
<summary>Show the answer</summary>

```markdown
1. Cut the cheese
2. Slice the tomatoes
3. Rub the tomatoes in flour
```
</details>

---

Fantastic work!

You can choose to add italics, bold, or links within lists, as you might expect. In the box below, turn the latin names for the plants into italics.

```markdown
* Azalea (Ericaceae Rhododendron)
* Chrysanthemum (Anthemideae Chrysanthemum)
* Dahlia (Coreopsideae Dahlia)
```

<details>
<summary>Show the answer</summary>

```markdown
* Azalea (_Ericaceae Rhododendron_)
* Chrysanthemum (_Anthemideae Chrysanthemum_)
* Dahlia (_Coreopsideae Dahlia_)
```
</details>

---

Magnificent!

Occasionally, you might find the need to make a list with more depth, or, to *nest* one list within another. Have no fear, because the Markdown syntax is exactly the same. All you have to do is to remember to indent each asterisk *one space more* than the preceding item.

For example, in the following list, we're going to add some sub-lists to each "main" list item, describing the people in detail:

```markdown
* Tintin
 * A reporter
 * Has poofy orange hair
 * Friends with the world's most awesome dog
* Haddock
 * A sea captain
 * Has a fantastic beard
 * Loves whiskey
   * Possibly also scotch?

```

When rendered, this list turns into the following grouping:

- Tintin
    - A reporter
    - Has poofy orange hair
    - Friends with the world's most awesome dog
- Haddock
    - A sea captain
    - Has a fantastic beard
    - Loves whiskey
        - Possibly also scotch?

In the box below, turn the character's characteristics into sub-bullets.

```markdown
* Calculus, A professor, Has no hair, Often wears green
* Castafiore, An opera singer, Has white hair, Is possibly mentally unwell
```

<details>
<summary>Show the answer</summary>

```markdown
* Calculus
    * A professor
    *  Has no hair
    *  Often wears green
* Castafiore
    * An opera singer
    * Has white hair
    * Is possibly mentally unwell
```
</details>

---

Stupendous! While you could continue to indent and add sub-lists indefinitely, it's usually a good idea to stop after three levels; otherwise, your text becomes a mess.

There's one more trick to lists and indentation that we'll explore, and that deals with the case of paragraphs. Suppose you want to create a bullet list that requires some additional context (but not another list). For example, it might look like this:

1. Crack three eggs over a bowl.

    Now, you're going to want to crack the eggs in such a way that you don't make a mess.

    If you *do* make a mess, use a towel to clean it up!

2. Pour a gallon of milk into the bowl.

    Basically, take the same guidance as above: don't be messy, but if you are, clean it up!

3. Rub the salmon vigorously with butter.

    By "vigorous," we mean a strictly vertical motion. Julia Child once quipped:

    > Up and down and all around, that's how butter on salmon goes.

4. Drop the salmon into the egg-milk bowl.

    Here are some techniques on salmon-dropping:

    - Make sure no trout or children are present
    - Use both hands
    - Always have a towel nearby in case of messes

To create this sort of text, your paragraph must start on a line all by itself underneath the bullet point, and it must be indented by at least one space. For example, the list above looks like this in Markdown:

```markdown
1. Crack three eggs over a bowl.

 Now, you're going to want to crack the eggs in such a way that you don't make a mess.

 If you _do_ make a mess, use a towel to clean it up!

2. Pour a gallon of milk into the bowl.

 Basically, take the same guidance as above: don't be messy, but if you are, clean it up!

3. Rub the salmon vigorously with butter.

   By "vigorous," we mean a strictly vertical motion. Julia Child once quipped:
   > Up and down and all around, that's how butter on salmon goes.
4. Drop the salmon into the egg-milk bowl.

   Here are some techniques on salmon-dropping:

   * Make sure no trout or children are present
   * Use both hands
   * Always have a towel nearby in case of messes

```

Notice that the first two items have a single space. This looks a bit odd, so you might want to indent properly to match the characters up (like items three and four). In these paragraphs, you can include all sorts of other Markdown elements, like blockquotes, or even other lists!

In the box below, convert the bullet points into their own paragraphs.

```markdown
1. Cut the cheese
  * Make sure that the cheese is cut into little triangles.

2. Slice the tomatoes
  * Be careful when holding the knife.
  * For more help on tomato slicing, see Thomas Jefferson's seminal essay _Tom Ate Those_.
```

---

You now know how to make lists in Markdown!

[On to the next lesson!](Lesson%207.md)
