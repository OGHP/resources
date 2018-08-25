# Resources for creating a website

### Add README.md and .gitignore and MIT Licence

### CSS folders:
    <link rel="stylesheet" href="styles/base.css">
    <link rel="stylesheet" href="styles/layout.css">
    <link rel="stylesheet" href="styles/modules.css">

### reset.css:
/* http://meyerweb.com/eric/tools/css/reset/
   v2.0 | 20110126
   License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed,
figure, figcaption, footer, header, hgroup,
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure,
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}

### .eslintrc
{
  "globals" : {
    "rawData": true,
    "Article": true,
    "articleView": true,
    "app": true,
    "Handlebars": true,
    "page": true,
    "$": true,
    "marked": true,
    "hljs": true
  },
  "extends": "eslint:recommended",
  "parserOptions": {
    "ecmaVersion": 6,
    "ecmaFeatures": {"impliedStrict": true}
  },
  "env": {
    "browser": true,
    "jquery": true,
    "node": true,
    "es6": true
  },
  "rules": {
    "eqeqeq": ["error", "always"],
    "no-template-curly-in-string": "error",
    "no-console": "off",
    "no-undefined": "off",
    "indent": ["error", 2],
    "quotes": ["warn", "single", {"allowTemplateLiterals": true}],
    "no-multi-spaces": ["warn", {"exceptions": { "VariableDeclarator": true }}],
    "no-trailing-spaces": "warn",
    "new-cap": "warn",
    "no-redeclare": ["error", { "builtinGlobals": true }]
  }
}


### handlebars:
<script src="https://cdnjs.cloudflare.com/ajax/libs/handlebars.js/4.0.11/handlebars.min.js"></script>

### jQuery
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
