# 10k-apart-2016
A "Random" Website - My entry for the 10k Apart contest

(http://anirudhkhanna.github.io/10k-apart-2016)

## Some noteworthy optimizations

### URLs
- Used `<a href="">` for current page/directory link instead of the complete `<a href="http://anirudhkhanna.github.io/10k-apart-2016">`

- Omitted the protocol name for external sites. For example, `//github.com` instead of the complete URL `http://github.com`

- Used `../` instead of giving a full URL to the previous directory (i.e. `anirudhkhanna.github.io`).

- URL shorteners were not used because although they could reduce the number of characters, they are not always considered safe.

### Code Formatting
- The formatting is a bit compact.

- Especially in CSS, where the code format is like this:
```
nav ul {margin:5px 0 0 0;}
nav ul li {display:inline; padding-right:50px;}
...
```

### No superfluous tags
It was tried that unnecessary tags were cut down. For example,
```
<span id="titlelink">
  <a>...</a>
</span>
```
becomes:
```
<a id="titlelink">...</a>
```

### Minimum and optimized images
Images were avoided mostly. The images used (like in the favicon) were really small and optimized.

## Character entities for symbols
Only character entities (like ✎, ✉ etc.) were used as icons on the site wherever required.

## Minimal JS used, with fallback options
