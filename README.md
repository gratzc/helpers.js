# helpers.js

A collection of small JavaScript helper functions for various use cases. All of these little snippets solve problems that are very common, but don't have a widespread decent implementation.

---

__baseURL__

Grabs only the base of any given URL. You can also hide the TLD.

```js
baseURL('http://www.maxvoltar.com/archive/more-beats')
```

__readingtime__

Returns the estimated time to complete reading of a text in a human readable format.

```js
readingtime(2720, 'Reading this takes {time}.', 270)
```

__smoothscroll__

Scrolls the body element smoothly to the top using only Vanilla JS.

```js
smoothscroll()
```

__wordcount__

Counts the words in any given string of text and counts the words correctly. You can define the output using a placeholder.

```js
wordcount('Hello, it\'s me', 'This is {count} words long.')
```