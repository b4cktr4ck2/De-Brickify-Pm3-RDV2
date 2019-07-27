---
layout: default
---

In this tutorial, we're going to go through the process of un-bricking a Proxmark3. I did this to an RDV2 that had bricked on me, but the steps can easily be modifed to work with a Pm3 Easy.

# What you'll need to get started

*   A bricked Proxmark3. If you don't have one that's bricked, go ahead and brick one by flashing the bootloader and unplugging halfway through (**NOTE: Don't actually do this**)
*   A Bus Pirate version 3, capable of using Firmware 6.0. An example of what you want is [this](https://www.sparkfun.com/products/12942). Pick up a [cable](https://www.sparkfun.com/products/9556) too.
*   A pin header to connect the Proxmark and Bus Pirate cable. I recommend you buy a breakable curved pin header, that way you can break it into 6-pin chunks, as that's how long the pin header must be.
*   A multimeter, to test continuity and identify what cable to plug into which pin on the Proxmark.
*   (OPTIONAL) A soldering kit, to solder the pin header onto the Proxmark. You don't actually **have** to solder it on, but it's going to make flashing the bootloader and full image a pain because you have to hold the pin header in place and keep it stable. It's _reallllllllllly_ tricky but technically doable.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
