## highlight.js

用在：layouts/partials/highlight-js.html

```bash
mkdir -p static/js/languages
curl https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/highlight.min.js -Lf -o static/js/highlight.min.js
## 特定语言
curl https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/languages/go.min.js -o static/js/languages/go.min.js

mkdir -p static/styles
## 样式
curl https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/default.min.css -o static/styles/default.min.css
curl https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/github.min.css -o static/styles/github.min.css
curl https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styes/atom-one-dark.min.css -o static/styles/atom-one-dark.min.css
```

## Font Awesome

参考：[Alternate Install: Using all.js](https://docs.fontawesome.com/web/setup/host-yourself/svg-js#alternate-install-using-alljs)

用在：

- layouts/partials/footer/font-awesome-js.html
- layouts/partials/sidebar/social.html

```bash
# curl https://use.fontawesome.com/releases/v5.12.1/js/all.js -Lf -o static/js/all.js
curl https://use.fontawesome.com/releases/v6.6.0/js/all.js -Lf -o static/js/all.js
```