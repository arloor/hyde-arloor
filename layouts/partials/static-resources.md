mkdir -p static/js/languages
curl https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/highlight.min.js -Lf -o static/js/highlight.min.js
curl https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/languages/go.min.js -o static/js/languages/go.min.js

mkdir -p static/styles
curl https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/default.min.css -o static/styles/default.min.css
curl https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/github.min.css -o static/styles/github.min.css
curl https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styes/atom-one-dark.min.css -o static/styles/atom-one-dark.min.css

curl https://use.fontawesome.com/releases/v5.12.1/js/all.js -Lf -o static/js/all.js