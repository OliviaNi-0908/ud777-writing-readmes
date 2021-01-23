# Markdown 101
Markdown is a light markup language often used for READMEs (though you'll find other use cases for it, too!). It is fairly straightforward, and much of the syntax is intuitive.

But as it turns out, there are many different _dialects_ of Markdown, just like in a spoken language. Each of these dialects is known as a _flavor_ of Markdown. Most of these dialects are pretty much the same, with only minor differences.

Since your READMEs will ultimately end up on GitHub, we'll be using **GitHub Flavored Markdown**. I've included a link to the full documentation for it in the instructor notes (and we'll be using that later in this course), but I'll get you started with a quick crash course.

## Feeling Bold?
To make text **bold**, surround it with double asterisks. So this code:
```
Isn't today a **wonderful** day?
```
becomes: Isn't today a **wonderful** day?

## _Italics_, I tell you!
To _italicize_ text, surround it with underscores. So this code:
```
And in that moment I thought to myself: _Did I turn off the stove?_
```
becomes: And in that moment I thought to myself: _Did I turn off the stove?_

Much like the previous example, this code reads much more like English, which is great for when you're skimming the original document.

## To `code`, or not to `code`?
Inline `code` is useful for indicating that you're writing code and not a regular word. For this, you'll surround text in backticks (`, not a single quote). So this code:
```
You should use the `strong` tag.
```
becomes: You should use the `strong` tag.

...which makes much more sense than "You should use the strong tag."

## The Title Sequence
Headings are even simpler! For `h1` through `h6` tags, all you'll need is a `#` before your text. The number of `#`s you include tells Markdown which header tag you're using. For example:
```
## This is an h2.
```
```
### This is an h3.
```
becomes...

## This is an h2.
### This is an h3.


## Let's practice!
Here's a link to the basic [Markdown documentation](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github). You can also check out the differences in GitHub flavored Markdown [here](https://docs.github.com/en/github/writing-on-github).
