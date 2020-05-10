## Thematic breaks

***
---
___


## ATX headings

# foo
## foo
### foo
#### foo
##### foo
###### foo


## Setext headings

Foo *bar*
=========

Foo *bar*
---------


## Indented code blocks

    a simple
      indented code block


## Fenced code blocks

```
<
 >
```

```python
from nltk.metrics.distance import edit_distance

def normalized_edit_distance(s1, s2):
    return edit_distance(s1, s2) / max(len(s1), len(s2))
```


## HTML blocks

<table><tr><td>
<pre>
**Hello**,

_world_.
</pre>
</td></tr></table>


## Link reference definitions

[foo]: /url "title"

[foo]


## Paragraphs

aaa

bbb


## Blank lines

  

aaa
  

# aaa

  


## Block quotes

> # Foo
> bar
> baz


## List items

1.  A paragraph
    with two lines.

        indented code

    > A block quote.

- one

 two


## Lists

- foo
- bar
+ baz


## Backslash escapes

\!\"\#\$\%\&\'\(\)\*\+\,\-\.\/\:\;\<\=\>\?\@\[\\\]\^\_\`\{\|\}\~


## Entity and numeric character references

&nbsp; &amp; &copy; &AElig; &Dcaron;
&frac34; &HilbertSpace; &DifferentialD;
&ClockwiseContourIntegral; &ngE;


## Code spans

`foo`


## Emphasis and strong emphasis

*foo bar*

**foo bar**


## Links

[link](/uri "title")

[link [foo [bar]]][ref]

[ref]: /uri


## Images

![foo](/url "title")


## Autolinks

<http://foo.bar.baz>


## Raw HTML

<a><bab><c2c></a>


## Hard line breaks

foo  
baz


## Soft line breaks

foo
baz


## Textual content

hello $.;'there

