# Track Awesome Unicode Updates Weekly

:joy: :ok_hand: A curated list of delightful Unicode tidbits, packages and resources.

[🏠 Home](/README.md) · [🔍 Search](https://test.trackawesomelist.com/search/) · [🔥 Feed](https://test.trackawesomelist.com/jagracey/Awesome-Unicode/week/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 jagracey/Awesome-Unicode](https://github.com/jagracey/Awesome-Unicode/blob/master/README.md) · ⭐ 807 · 🏷️ Miscellaneous

[ [Daily](/content/jagracey/Awesome-Unicode/README.md) / Weekly / [Overview](/content/jagracey/Awesome-Unicode/readme/README.md) ]



## [Jul 04 - Jul 10, 2016](/content/2016/27/README.md)

### :collision: Lowercase Transformation Collisions / Wait a second... what did I just read?

*   **String length is typically determined by counting codepoints.** This means that surrogate pairs would count as two characters. Combining multiple diacritics may be stacked over the same character. `a + ̈  == ̈a   `, increasing length, while only producing a single character.
*   **Similarily, reversing strings often is a non-trivial task.** Again, surrogate pairs and diacritics must be reversed together. [ES Reverser (⭐859)](https://github.com/mathiasbynens/esrever) provides a pretty good solution.
*   **Upper and lower case mappings are not always one-to-one.** They can also be:
    *   One-to-many: (ß → SS )
    *   Contextual: (…Σ ↔ …ς AND …ΣΤ… ↔ …στ… )
    *   Locale-sensitive: ( I ↔ ı AND İ ↔ i )

### Unicode Blocks / Wait a second... what did I just read?

*   [Version 9.0.0](http://www.unicode.org/versions/Unicode9.0.0/) (Latest Version, August 2016 - adds exactly 7,500 characters)
*   [Version 8.0.0](http://www.unicode.org/versions/Unicode8.0.0/)

## [Jun 13 - Jun 19, 2016](/content/2016/24/README.md)

### One-To-Many Case Mappings / Wait a second... what did I just read?

*   [python-ftfy (⭐3.3k)](https://github.com/LuminosoInsight/python-ftfy) - Given Unicode text, make its representation consistent and possibly less broken.
*   [vim-troll-stopper (⭐166)](https://github.com/vim-utils/vim-troll-stopper) - Stop Unicode trolls from messing with your code.

### Recursive HTML Tag Renaming Script / Wait a second... what did I just read?

*   [What Every Programmer Absolutely, Positively Needs To Know About Encodings And Character Sets To Work With Text](http://kunststube.net/encoding/)

## [May 30 - Jun 05, 2016](/content/2016/22/README.md)

### Myths of Unicode

*   **Unicode is simply a 16-bit code** - Some people are under the misconception that Unicode is simply a 16-bit code where each character takes 16 bits and therefore there are 65,536 possible characters. This is not, actually, correct. It is the single most common myth about Unicode, so if you thought that, don't feel bad.
*   **You can use any unassigned codepoint for internal use** - No. Eventually that hole will be filled with a different character. Instead use private use or noncharacters.
*   **Every Unicode code point represents a character** - No. There are lots of nonCharacters (FFFE, FFFF, 1FFFE,…)
    There are also surrogate code points, private and unassigned codepoints, and control/format “characters" (RLM, ZWNJ,…)
*   **Unicode will run out of space** - If it were linear, we would run out in 2140 AD. But it isn't linear. See <http://www.unicode.org/roadmaps/>
*   **Case mappings are 1-1** - No. They can also be:
    *   One-to-many: (ß → SS )
    *   Contextual: (…Σ ↔ …ς AND …ΣΤ… ↔ …στ… )
    *   Locale-sensitive: ( I ↔ ı AND İ ↔ i )

### One-To-Many Case Mappings / Wait a second... what did I just read?

*   [PhantomScript (⭐39)](https://github.com/jagracey/PhantomScript) - :ghost: :flashlight: Invisible JavaScript code execution & social engineering
*   [ESReverser (⭐859)](https://github.com/mathiasbynens/esrever) - A Unicode-aware string reverser written in JavaScript.
*   [mimic (⭐3.7k)](https://github.com/reinderien/mimic) - \[ab]using Unicode to create tragedy
*   [Unicode Consortium's Emoji Chart](http://www.unicode.org/emoji/charts/full-emoji-list.html)
*   [Emojipedia](http://emojipedia.org/) - Information about specific emoji, news blog.
*   [emojitracker](http://emojitracker.com/) - Realtime emoji use on Twitter.
*   [World Translation Foundation](http://www.emojifoundation.com/) - A way to promote, explore, and translate the written word into the pictorial alphabet of Emoji.
*   [Can I Emoji?](http://caniemoji.com/android-2/) - Displays the current status of native Emoji support across iOS, Android and Windows.
*   [How to register an emoji URL](http://www.name.com/blog/how-tos/2015/12/want-an-emoji-url-this-is-how-you-register-one/)

### Recursive HTML Tag Renaming Script / Wait a second... what did I just read?

*   <https://en.wikipedia.org/wiki/Unicode_font#List_of_Unicode_fonts>
*   <http://www.unifont.org/fontguide/>
*   [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets](http://www.joelonsoftware.com/articles/Unicode.html) - By Joel Spolsky
*   [The Unicode Consortium's Recommended Reading List](http://www.unicode.org/resources/readinglist.html)
*   [Space Yourself](https://www.smashingmagazine.com/2015/10/space-yourself/) - Smashing Magazine's Spacing Guide
*   [JavaScript has a Unicode Problem](https://mathiasbynens.be/notes/javascript-unicode)
*   [Creative usernames and Spotify account hijacking](https://labs.spotify.com/2013/06/18/creative-usernames/)
*   [Shapecatcher](http://shapecatcher.com/) - Draw the character you're looking for.
*   [Confusable Unicode Characters](http://unicode.org/cldr/utility/confusables.jsp?r=None)
*   [Unicode Character Database](http://www.unicode.org/ucd/)
*   [Database Dumps of Codepoints.net](https://dumps.codepoints.net/)
*   [Unicode Blocks List](http://www.unicode.org/Public/UCD/latest/ucd/Blocks.txt)
*   [Unicode Character Code Charts](http://www.unicode.org/charts/index.html)
*   [Unicode Case Charts](http://www.unicode.org/charts/case/)
*   [Unicode Normalization Chart](http://www.unicode.org/charts/normalization/)
*   [Unicode FAQ](http://www.unicode.org/faq/)

### Unicode Blocks / Wait a second... what did I just read?

*   **Universal repertoire** 	 - Every writing system ever used shall be respected and represented in the standard
*   **Logical order** 		 - In bidirectional text are the characters stored in logical order, not in a way that the representaion
*   **Efficiency**			 - The documentation must be efficient and complete.
*   **Unification**			 - Where different cultures or languages use the same character, it shall be only included once. This point is
*   **Characters, not glyphs** - Only characters, not glyphs shall be encoded. In a nutshell, glyphs are the actual graphical
*   **Dynamic composition**	 - New characters can be composed of other, already standardized characters. For example, the character “Ä” can be composed of an “A” and a dieresis sign (“ ¨ ”).
*   **Semantics**				 - Included characters must be well defined and distinguished from others.
*   **Stability**				 - Once defined characters shall never be removed or their codepoints reassigned. In the case of an error, a codepoint shall be deprecated.
*   **Plain Text**			 - Characters in the standard are text and never mark-up or metacharacters.
*   **Convertibility**		 - Every other used encoding shall be representable in terms of a Unicode encoding.
*   [Version 7.0.0](http://www.unicode.org/versions/Unicode7.0.0/)
*   [Version 6.3.0](http://www.unicode.org/versions/Unicode6.3.0/)
*   [Version 6.2.0](http://www.unicode.org/versions/Unicode6.2.0/)
*   [Version 6.1.0](http://www.unicode.org/versions/Unicode6.1.0/)
*   [Version 6.0.0](http://www.unicode.org/versions/Unicode6.0.0/)
*   [Version 5.2.0](http://www.unicode.org/versions/Unicode5.2.0/)
*   [Version 5.1.0](http://www.unicode.org/versions/Unicode5.1.0/)
*   Version 5.0.0 (unavailable)
*   [Version 4.0.1](http://www.unicode.org/versions/Unicode4.0.1/)
*   [Version 4.0.0](http://www.unicode.org/versions/corrigendum5.html)