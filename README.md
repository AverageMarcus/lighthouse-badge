## Lighthouse score badges

Be proud of your [Lighthouse](https://github.com/googlechrome/lighthouse) score! Display
this badge in a Github readme, on your site, in a presentation,...wherever.

Large:

[![Lighthouse score: 100/100](https://lighthouse-badge.appspot.com/?score=100)](https://github.com/ebidel/lighthouse-badge)
[![Lighthouse score: 65/100](https://lighthouse-badge.appspot.com/?score=65)](https://github.com/ebidel/lighthouse-badge)
[![Lighthouse score: 35/100](https://lighthouse-badge.appspot.com/?score=35)](https://github.com/ebidel/lighthouse-badge)

Compact:

[![Lighthouse score: 100/100](https://lighthouse-badge.appspot.com/?score=100&compact)](https://github.com/ebidel/lighthouse-badge)
[![Lighthouse score: 65/100](https://lighthouse-badge.appspot.com/?score=65&compact)](https://github.com/ebidel/lighthouse-badge)
[![Lighthouse score: 35/100](https://lighthouse-badge.appspot.com/?score=35&compact)](https://github.com/ebidel/lighthouse-badge)

### Examples

API: `https://lighthouse-badge.appspot.com/?score=<SCORE>[&compact]`

Parameters:

- `score`: required. set from [0,100].
- `compact`: optional. Renders smaller image instead.

Markdown

```
[![Lighthouse score: 100/100](https://lighthouse-badge.appspot.com/?score=100)](https://github.com/ebidel/lighthouse-badge)

[![Lighthouse score: 65/100](https://lighthouse-badge.appspot.com/?score=65&compact)](https://github.com/ebidel/lighthouse-badge)
```

HTML

```
<a href="https://github.com/ebidel/lighthouse-badge" target="_blank">
  <img src="https://lighthouse-badge.appspot.com?score=100">
</a>

<a href="https://github.com/ebidel/lighthouse-badge" target="_blank">
  <img src="https://lighthouse-badge.appspot.com?score=165&compact">
</a>
```
