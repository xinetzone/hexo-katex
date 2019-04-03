# hexo-katex

Use KaTeX to display math in Hexo sites.

## Install 

Install [hexo-renderer-pandoc](https://github.com/wzpan/hexo-renderer-pandoc) and config math engine.

```
pandoc:
  mathEngine: katex
```

Then install hexo-katex.

```
npm install hexo-katex --save
```

KaTeX css link will be automatically injected into post, if you want to add it manually, modify `_config.yml`.

```
katex:
  css: false
```

You can define macros like that:

```
katex:
  macros:
    \hash: \mathop\mathrm{hash}
```


## Writing

Inline math `$E = m * c^2$`

Display math

```
$$
E = m * c^2
$$
```
