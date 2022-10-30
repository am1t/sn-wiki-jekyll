---
title: First seed in my digital garden
---

### Welcome!

This is my first note. I have set it up in my [`notes/`](https://github.com/am1t/sn-wiki/tree/master/_notes) directory. This note is my playground around what can be done with Obsidian and the digital gardens. This possibly has nothing of interest for anyone who reads this. But for me, This matters a lot. I am learning as I work the system. For me, my [[digital garden setup]] is a good place to start.

### Link syntax

To link to another note, you can use multiple syntaxes. The following four use the "double-bracket" notation ([view the Markdown source file](https://github.com/maximevaillancourt/digital-garden-jekyll-template/blob/master/_notes/your-first-note.md#link-syntax) to see the underlying syntax).

- Using the note title: [[a note about cats]]
- Using the note's filename: [[cats]]
- Using the note's title, with a label: [[A note about cats|link to the note about cats using the note title]]
- Using the note's filename, with a label: [[cats|link to the note about cats using the note's filename]]

You can organize notes in subdirectories and link them normally. For example, the links above all point to the `_notes/animals/cats.md` file. Here's another example: [[tigers]].

So what if I want to link to [[consistency]]. Nice! It added it! 

And what about [[move your body every day]]. Brilliant!

In all cases, if the double-bracket link does not point to a valid note, the double brackets will still be shown, like this: [[there is no note that matches this link]].

Alternatively, you can use regular [Markdown syntax](https://www.markdownguide.org/getting-started/) for links, with a relative link to the other note, like this: [this is a Markdown link to the note about cats](/cats){: .internal-link}. Don't forget to use the `.internal-link` class to make sure the link is styled as an internal link (without the little arrow).

Since the Web is all about HTML, you can always use plain HTML if you want, like this: <a class="internal-link" href="/cats">This is a link to the note about cats with HTML</a>.

Of course, you can also link to external websites, like this: [this is a link to Wikipedia](https://wikipedia.org/). Again, you can use plain HTML if you prefer. Footnotes are also supported and will be treated like internal links.[^1] You can point to other notes in your footnotes.[^2]

[^1]: This is a footnote. For more information about using footnotes, check out the [Markdown Guide](https://www.markdownguide.org/extended-syntax/#footnotes).
[^2]: This is another footnote that links to the note about [[cats]]. You may also point to [[notes that do not exist]] if you wish.

### Tweet embedding

Note: This behavior is disabled by default for privacy reasons. See "Site configuration" section below to enable it.

You may include a tweet URL on its own line (like below), and it would be replaced with an official Twitter embed if the site configuration demands it.

https://twitter.com/jack/status/20

### Media embedding

You may embed media files within a note using HTML5 media tags. Here's an example for an audio file:

"Jazzy Frenchy" by Benjamin Tissot from bensound.com
<audio controls>
  <source src="/assets/jazzyfrenchy.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

### Automatic bi-directional links

Notice in the "Notes mentioning this note" section that there is another note linking to this note. This is a bi-directional link, and those are automatically created when you create links to other notes.

### Link previews

If you're on a device with mouse support, try hovering your mouse on internal links to preview the notes: [[a note about cats]].

Links that have been previewed will be cached to avoid redundant requests.

### Images and other Markdown goodies

Finally, because you have the full power of Markdown in this template, you can use regular Markdown syntax for various formatting options.

Lists work as expected, here's the unordered list.

- List element A
- List element B
- List element C

And now the ordered list. 

1. List element
2. List element
3. List element

If you'd like to quote other people, consider using quote blocks:

> Lorem ipsum dolor sit amet

And of course, images look great:

<img src="/assets/image.jpg"/>

You can also ==highlight some content== by wrapping it with `==`.

### Code syntax highlighting

You can add code blocks with full syntax color highlighting by wrapping code snippet in triple backticks and specifying the type of the code (`js`, `rb`, `sh`, etc.):

```js
// Here's a bit of JavaScript:
console.log('hello!')
```

```rb
# And now some Ruby
def foo(bar)
  "baz"
end
```

```sh
$ cat /dev/urandom | grep "the answer to life" # shell scripts look nice too
```


### Next steps

Do I want to style this place? May be, I am not too sure. But I want to use this place for capturing my thoughts for sure. I will keep updating things in Obsidian and push them to the space.

[ ] Minimal styling improvement for  consistency
[ ] Starting moving in content

Idea is to move, have fun, and learn new something every day! ✌️