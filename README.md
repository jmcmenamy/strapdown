# Strapdown.js

See [here](https://github.com/ndossougbe/strapdown) for a more thorough description, all credit goes to the original authors. I made very minor and messy edits.

I forked this to be able to only do toc generation on existing html, no markdown parsing. Instead, I use the [Github API](https://docs.github.com/en/rest/markdown/markdown?apiVersion=2022-11-28) to convert markdown to html, and I use [this](https://github.com/sindresorhus/github-markdown-css) for styling the html.

I liked the look of the toc generation in the original, and found it easier to do this than replicate it myself.