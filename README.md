# Understanding `a` tags in HTML

The `a` tag is a fundamental HTML element responsible for much of the linking goodn ess that makes HTML great!

## Components
Let's take a quick look at how the tag works:

``` html
<a href="sourceurl">Displayed Text</a>
```

As in any tag, there's a basic structure of ```<tag attr="value">content</tag>```. The fantastic, amazing attribute in the `a` tag is `href` -- short for "hypertext reference". The `href` attribute identifies a target URL; when this HTML snippet is displayed in a browser, the browser will direct you to the URL in the href attribute. Let's try it out:

``` html
<a href="https://google.com">Google Owns All Your Data</a>
```

<a href="https://google.com">Google Owns All Your Data</a>

As with most HTML tags, the `a` tag accepts a number of possible attributes. Some of them are used only rarely, but you will often see the `target` attribute in the real world. THis allows you to specify where to open the link you click on:
- `_self` means "open here"
- `_blank` means "open in a new tab"
- `_parent` means "if you're looking at an [internal frame](https://developer.mozilla.org/en/docs/Web/HTML/Element/iframe), open this link in the frame's arent tab. Otherwise, just open here like in `_self`

## Try it yourself

You can clone this repository and load a local copy of [the tutorial page](./a-tag-tutorial.html) in your browser to see the tag in action. Then make some changes to the file to learn this yourself!

## Learn More

The [Mozilla Developer Network](https://developer.mozilla.org/en/docs/Web/HTML/Element/a) has lots more detail about this and every HTML tag!

