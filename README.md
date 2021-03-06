# Mastering Markdown

Markdown is a markup language used to write both HTML and formatted text. It is easy to read just by itself as well as it converts to HTML.

## Tooling

Choose an editor which you are already comfortable with for writing/editing Markdown.

Use **MarkdownEditing** package for **Sublime Text**.
Use **Markdown-Writer** package for **Atom**.
Use **Markdown All in One** extension for **VSCode**.

**Marked 2**, **Mou** and **Multi Markdown** are apps for editing/viewing Markdown.
[Dillinger](https://dillinger.io), [StackEdit](https://stackedit.io) are In-browser Markdown editors.

## Paragraph And Text Decoration

This is a paragraph.

This is **bold**.

This is _italic_.

This is a ~~strikethrough~~.

## Headings

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

Alternatively, for H1 and H2, an underline-ish style:

Heading 1
=========

Heading 2
---------

## Links

<https://github.com>

[Github](https://github.com)

[Mastering Markdown](https://masteringmarkdown.com "A mini video series to learn to write in Markdown")

Here is my github [profile][1]. And here is a link to this [repository][repo].
This [repository][repo] contain notes from Mastering Markdown by Wes Bos.

[1]: https://github.com/4nkt
[repo]: https://github.com/4nkt/mastering-markdown

## Images

Here is an image.

![](https://unsplash.it/500/500?random)

Here is an image with an alternate text.

![some alternate text](https://unsplash.it/500/500?image=1012)

Here is an image with an alternate text and tooltip.

![some alternate text](https://unsplash.it/500/500?image=1000 "some tooltip")

Here is another image.

![some alternate text][image]

Here is a small image as a link to bigger version.

[![](https://unsplash.it/100/100?image=523)](https://unsplash.it/500/500?image=523)

And one more example.

[<img src="https://unsplash.it/200/200?image=999" />](https://unsplash.it/500/500?image=999)

[image]: https://unsplash.it/500/500?image=900

## Unordered Lists

Here are some examples of unordered lists:

+ milk
+ eggs
+ bread

- sugar
- salt
- pepper

* cheese
* cream
* butter

## Ordered Lists

Here is an example of ordered list:

1. Combine Ingredients
2. Gently Stir Together
3. Bake at 350 for 20 minutes

Another example:

1. Mix Ingredients
1. Stir Together
1. Bake at 350 for 20 minutes

## Nested Lists

1. Combine Following Ingredients
    * Item 1
    * Item 2
1. Stir Together
    * Nested Item

        This is a paragraph.

        ![](https://unsplash.it/500/500?image=111)
1. Bake

## Line Breaks

To create a line break, end a line with two or more spaces, and then add a new line.

This is the first line.  
And this is the second line.

## Horizontal Rules

This is followed by a horizontal rule.

---

## Block Quotes

> You miss 100% of the shots you don't take.
>
> \- **Wayne Gretzky**

## Code Blocks

Here are some examples of code blocks:

    var x = 100;
    const dog = 'snickers';

```php
$age = 50;
$name = "ankit";
echo strtoupper($name);
```

```
echo "hello"
```

Hey did you try `var x = 100;`?

```diff
var x = 100;
- var y = 200;
+ var y = 400;
```

## Tables

|Dog's Name|Dog Breed|Dog's Age|
|:---------|:-------:|--------:|
|Snickers|Bulldog|2|
|Prudence|Pug|8|

## Checkboxes

* [ ] Get Milk
* [x] Crack Eggs
* [ ] Cook Bacon

## HTML

HTML can be directly used inside Markdown. This is helpful if you prefer certain HTML tags to Markdown syntax. For example, some people find that it's easier to use HTML tags for images.

<p>
  Here is an example of a paragraph with some <b>bold</b> text and an image
  <img src="https://unsplash.it/500/500?image=910" />
  <br/>written in HTML.
</p>

## Github Issues / Pull Requests

A issue/PR in Github can be linked using #`issue/PR number`.

## Github Mentions

@`username` is used for mentions in Github.

## Github Emojis

:smiley: :fire: :heart: :facepunch: :see_no_evil: :sunglasses: :rocket: :shit: :scream:

## Resources :books:

* [Mastering Markdown — A mini video series to learn to write in Markdown](https://masteringmarkdown.com/)
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [Markdown Guide](https://www.markdownguide.org/)
* [Github Markdown Emoji Cheatsheet](https://gist.github.com/rxaviers/7360908)
* [GitHub Markdown Tips](https://dev.to/burdettelamar/github-markdown-tips--2gpk)
