Tests #2


NEW EDIT
---

CHANGE 1: Added two trailing spaces after "Here's a line break test."  Hoping that it enters "This should be the same paragraph as before." into a new line, but the same paragraph.
Here's a line break test.  
This should be the same paragraph as before.

This should be a separate paragraph.

***

# Header Uno

_Note:_ The alt-text doesn't show.  No idea what it does or means.

This should be an image with a link to a YouTube video.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=GoqFj81bpok
" target="_blank"><img src="http://img.youtube.com/vi/GoqFj81bpok/0.jpg" 
alt="AHAHA" width="240" height="180" border="10" /></a>

---

CHANGE 2: Testing why bullet spacing differs.

1. Same bullet (asterisks), two leading spaces
  * Sublist, unordered.  Uses two indenting spaces
  * Bullet point 2
  * Bullet point 3
2. Same bullet (asterisks), one leading space
 * unordered list using plus sign
 * unordered list using hyphen
 * unordered list using asterisk
3. Same bullet (pluses), two leading spaces
  + unordered list using plus sign
  + unordered list using hyphen
  + unordered list using asterisk
4. Different bullets, two leading spaces
  + Plus
  - Minus
  * Asterisks
5. Different bullets, one leading space
 * Asterisk
 + Plus
 - Minus

 Properly-indented paragraph here.  Use at least one space to indent.  
 Use two trailing spaces in above paragraph to have new line in same paragraph.
^ This worked!



6. Sixth item.  CHANGE 3: Let's see if this resets as 1., or continues as 6.  
   1. CHANGE 4: Does adding extra leading space (3 total) allow an ordered, numbered sublist?
   2. Number 2
   1. Number 3.  Marked as "1.", testing if sublist number order matters


-----

CHANGE 5: Entered additional line between display text and reference link.
Reference-style:

![alt text][Cactus pic]

[Cactus pic]: https://upload.wikimedia.org/wikipedia/commons/thumb/e/e2/Buckhorn_Cholla_Bloom.jpg/3024px-Buckhorn_Cholla_Bloom.jpg "Hoping this title will work"

---------

TESTS #1

testing

First repo - February *28*, 2020

Raw HTML test: Definition List

<dl>
 <dt> Definition term </dt>
 <dd> Definition description </dd>

 <dt> Definition term 2 </dt>
 <dd> Definition description 2 </dd>
</dl>

---

Here's a line break test.  
This should be the same paragraph as before.

This should be a separate paragraph.

***

# Header Uno

This should be an image with a link to a YouTube video.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=GoqFj81bpok
" target="_blank"><img src="http://img.youtube.com/vi/GoqFj81bpok/0.jpg" 
alt="AHAHA" width="240" height="180" border="10" /></a>

## Header Dos

Emphasis test

**Bold**

*Italics*

__Bold__

_Italics_

_**Bold Italics**_

__*Bold Italics*__

*__Bold Italics__*

**_Bold Italics_**

This is *gonna be __BOLD__*.

~~strikethrough~~

Alt-Header: Lists
---

1. First ordered list item.
2. Second item.
2. Third item (marked as "2.")
  * Sublist, unordered.  Uses two indenting spaces
  * Bullet point 2
  * Bullet point 3
4. Fourth item
 + unordered list using plus sign
 - unordered list using hyphen
 * unordered list using asterisk
5. Fifth item

 Properly-indented paragraph here.  Use at least one space to indent.  
 Use two trailing spaces in above paragraph to have new line in same paragraph.

1. Sixth item (marked as "1.")
  1. Ordered sublist.  Uses two indenting spaces
  2. Number 2
  1. Number 3.  Marked as "1.", testing if sublist number order matters


-----

###### Header 6: Links

[I'm an inline-style link.](https://www.nytimes.com)

[I'm an inline-style link with a title.](https://www.nytimes.com "New York Times")

[I'm a reference-style link.][Link 1]

[I'm a reference style link with a title.][Link 2]

URLs like <https://www.google.com> get turned into links using "< >".


#### Images!

You can do either inline-style or reference-style.

Inline style:
![alt text](https://upload.wikimedia.org/wikipedia/commons/1/1e/Cylindropuntia_bigelovii_2.jpg "Teddy Bear Cholla - hover title")


Reference-style:

![alt text][Cactus pic]
[Cactus pic]: https://upload.wikimedia.org/wikipedia/commons/thumb/e/e2/Buckhorn_Cholla_Bloom.jpg/3024px-Buckhorn_Cholla_Bloom.jpg "Hoping this title will work"



[Link 1]: https://www.washingtonpost.com
[Link 2]: https://www.washingtonpost.com "Washington Post"



### Tables!

Use colons in hyphen row dividing header row to specify alignment.

| Header | Row | Here |
|:---:|---|---:|
|Ahhhhhhhhhhhhhhh|Aooooooooooooooo|Awoooooooga|
|Let's|Test|Alignment|
|1|2|3|
|Let's|Test|Emphases|
|*Uno*|__Dos__|`Tres`|

###### Inline code

This didn't work using the MD Live Preview website.  Let's try it here.

You specify the language.  Use three `s to mark where code starts and ends.

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```matlab
%Now this oughta be interesting
p = 1
while p<5
p = p+1
end
%Comments should be green, "while" should be blue (?)
```

## Blockquotes

> Here's a blockquote with no leading spaces

Quote break

 > Here's a blockquote with one leading space



