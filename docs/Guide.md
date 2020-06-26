# How to use

Create a concept file named `<Concept>.md` in the `docs` folder. This will create an entry on the sidebar for the filename. Format the file using markdown. Also create an entry in `_sidebar.md` to make the page visible.

## Code blocks

Create a code block using the syntax below, or an `inline code` like so:

```python
items = ["hat", "cat"]
for (index, item) in enumerate(items):
  print("Item in index number {} is {}".format(index, item))
```

## Creating tabs

Create tabs by using the syntax below:

<!-- tabs:start -->

#### ** English **

Hello!

#### ** French **

Bonjour!

#### ** Nepalese **

Namaste!

<!-- tabs:end -->

Documentation for tabs: https://jhildenbiddle.github.io/docsify-tabs/#/

## Previewing

To preview the file, `cd` into the docs directory and run:

`docsify serve`

to deploy the localhost version of the site. Preview it using the given localhost link.

## Deploying

Once you are happy with the changes, push the changes onto the Github repository:

## Link to site

The site is hosted on Github via the following link:

https://abhiyanbeta.github.io/python_concepts/

My repository containing the source files are here:

https://github.com/abhiyanbeta/python_concepts/

## Sources

This site was created using Docsify and the theme used was Themeable. For documentation, visit:

1. https://docsify.js.org/#/
1. https://jhildenbiddle.github.io/docsify-themeable/#/
1. https://jhildenbiddle.github.io/docsify-tabs/#/
