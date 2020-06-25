# Markdown

## Headings

<!-- tabs:start -->

#### ** Rendered **

# Heading 1 {docsify-ignore}

## Heading 2 {docsify-ignore}

### Heading 3 {docsify-ignore}

#### Heading 4 {docsify-ignore}

##### Heading 5 {docsify-ignore}

###### Heading 6 {docsify-ignore}

#### ** Markdown **

```markdown
# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6
```

<!-- tabs:end -->

## Text

<!-- tabs:start -->

#### ** Rendered **

Body text

**Bold text**

*Italic text*

~~Strikethrough~~

<mark>Marked text</mark>

<pre>Preformatted text</pre>

<small>Small Text</small>

This is <sub>subscript</sub>

This is <sup>superscript</sup>

#### ** Markdown **

```markdown
Body text

**Bold text**

*Italic text*

~~Strikethrough~~

<mark>Marked text</mark>

<pre>Preformatted text</pre>

<small>Small Text</small>

This is <sub>subscript</sub>

This is <sup>superscript</sup>
```

<!-- tabs:end -->

## Links

<!-- tabs:start -->

#### ** Rendered **

[Inline link](https://google.com)

[Inline link with title](https://google.com "Google")

[Reference link by name][link1]

[Reference link by number][1]

[Reference link by self]

[link1]: https://google.com
[1]: https://google.com
[Reference link by self]: https://google.com

#### ** Markdown **

```markdown
[Inline link](https://google.com)

[Inline link with title](https://google.com "Google")

[Reference link by name][link1]

[Reference link by number][1]

[Reference link by self]

[link1]: https://google.com
[1]: https://google.com
[Reference link by self]: https://google.com
```

<!-- tabs:end -->

## Lists

<!-- tabs:start -->

#### ** Rendered **

**Numbered Lists**

1. Go to the store
1. Buy milk
   1. Make sure it's full-fat milk
   1. And organic
1. Buy eggs

**Bulleted Lists**

- Bread
- Milk
  - Full-fat
  - Organic
- Eggs

**Task Lists**

- [x] Bread
- [x] Milk
  - [x] Full-fat
  - [ ] Organic
- [ ] Eggs

**Dropdowns**

<details open>
<summary>Open me!</summary>
<br>
Hello there!
</details>

#### ** Markdown **

```markdown
**Numbered Lists**

1. Go to the store
1. Buy milk
   1. Make sure it's full-fat milk
   1. And organic
1. Buy eggs

**Bulleted Lists**

- Bread
- Milk
  - Full-fat
  - Organic
- Eggs

**Task Lists**

- [x] Bread
- [x] Milk
  - [x] Full-fat
  - [ ] Organic
- [ ] Eggs

**Dropdowns**

<details open>
<summary>Open me!</summary>
<br>
Hello there!
</details>
```

<!-- tabs:end -->

## Blockquotes

<!-- tabs:start -->

#### ** Rendered **

> We have two ears and one mouth so that we can listen twice as much as we speak.
>
> *- Epictetus*

#### ** Markdown **

```markdown
> We have two ears and one mouth so that we can listen twice as much as we speak.
>
> *- Epictetus*
```

<!-- tabs:end -->

## Code

<!-- tabs:start -->

#### ** Rendered **

This is `inline code`

```python
items = ["hat", "cat"]
for (index, item) in enumerate(items):
  print("Item in index number {} is {}".format(index, item))
```

#### ** Markdown **

````markdown
This is `inline code`

```python
items = ["hat", "cat"]
for (index, item) in enumerate(items):
  print("Item in index number {} is {}".format(index, item))
```
````

<!-- tabs:end -->

## Notices

<!-- tabs:start -->

#### ** Rendered **

!> **Important** notice with `inline code` and additional placeholder text used
to force the content to wrap and span multiple lines.

?> **Tip** notice with `inline code` and additional placeholder text used to
force the content to wrap and span multiple lines.

#### ** Markdown **

```markdown
!> **Important** notice with `inline code` and additional placeholder text used
to force the content to wrap and span multiple lines.

?> **Tip** notice with `inline code` and additional placeholder text used to
force the content to wrap and span multiple lines.
```

<!-- tabs:end -->

## Tabs

Tabs provided via the
[docsify-tabs](https://jhildenbiddle.github.io/docsify-tabs) plugin.

<!-- tabs:start -->

#### **English**

Hello!

#### **French**

Bonjour!

#### **Nepalese**

Namaste!

#### ** Markdown **

```markdown
<!-- tabs:start -->

#### **English**

Hello!

#### **French**

Bonjour!

#### **Nepalese**

Namaste!

<!-- tabs:end -->
```

<!-- tabs:end -->

## Tables

<!-- tabs:start -->

#### ** Rendered **

| Left Align | Center Align | Right Align | Non&#8209;Breaking&nbsp;Header |
| ---------- |:------------:| -----------:| ------------------------------ |
| A1         | A2           | A3          | A4                             |
| B1         | B2           | B3          | B4                             |
| C1         | C2           | C3          | C4                             |

#### ** Markdown **

```markdown
| Left Align | Center Align | Right Align | Non&#8209;Breaking&nbsp;Header |
| ---------- |:------------:| -----------:| ------------------------------ |
| A1         | A2           | A3          | A4                             |
| B1         | B2           | B3          | B4                             |
| C1         | C2           | C3          | C4                             |
```

<!-- tabs:end -->

## Keyboard

<!-- tabs:start -->

#### ** Rendered **

<kbd>&uarr;</kbd> Arrow Up

<kbd>&darr;</kbd> Arrow Down

<kbd>&larr;</kbd> Arrow Left

<kbd>&rarr;</kbd> Arrow Right

<kbd>&#8682;</kbd> Caps Lock

<kbd>&#8984;</kbd> Command

<kbd>&#8963;</kbd> Control

<kbd>&#9003;</kbd> Delete

<kbd>&#8998;</kbd> Delete (Forward)

<kbd>&#8600;</kbd> End

<kbd>&#8996;</kbd> Enter

<kbd>&#9099;</kbd> Escape

<kbd>&#8598;</kbd> Home

<kbd>&#8670;</kbd> Page Up

<kbd>&#8671;</kbd> Page Down

<kbd>&#8997;</kbd> Option, Alt

<kbd>&#8629;</kbd> Return

<kbd>&#8679;</kbd> Shift

<kbd>&#9251;</kbd> Space

<kbd>&#8677;</kbd> Tab

<kbd>&#8676;</kbd> Tab + Shift

#### ** Markdown **

```markdown
<kbd>&uarr;</kbd> Arrow Up

<kbd>&darr;</kbd> Arrow Down

<kbd>&larr;</kbd> Arrow Left

<kbd>&rarr;</kbd> Arrow Right

<kbd>&#8682;</kbd> Caps Lock

<kbd>&#8984;</kbd> Command

<kbd>&#8963;</kbd> Control

<kbd>&#9003;</kbd> Delete

<kbd>&#8998;</kbd> Delete (Forward)

<kbd>&#8600;</kbd> End

<kbd>&#8996;</kbd> Enter

<kbd>&#9099;</kbd> Escape

<kbd>&#8598;</kbd> Home

<kbd>&#8670;</kbd> Page Up

<kbd>&#8671;</kbd> Page Down

<kbd>&#8997;</kbd> Option, Alt

<kbd>&#8629;</kbd> Return

<kbd>&#8679;</kbd> Shift

<kbd>&#9251;</kbd> Space

<kbd>&#8677;</kbd> Tab

<kbd>&#8676;</kbd> Tab + Shift
```

<!-- tabs:end -->

## Horizontal Rule

<!-- tabs:start -->

#### ** Rendered **

---

#### ** Markdown **

```markdown
---
```

<!-- tabs:end -->

## Images

<!-- tabs:start -->

#### ** Rendered **

![Random image from Unsplash](//source.unsplash.com/collection/881815 "Source: Unsplash")

#### ** Markdown **

```markdown
![Landscape](//source.unsplash.com/collection/881815 "Source: Unsplash")
```

<!-- tabs:end -->

## Emoji

A complete list is available here: [Emoji cheatsheet](https://www.webpagefx.com/tools/emoji-cheat-sheet/)

## Source

1. https://jhildenbiddle.github.io/docsify-themeable/#/
