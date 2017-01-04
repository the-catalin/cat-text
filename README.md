[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/the-catalin/cat-text)

# cat-text

`cat-text` is a [Polymer](https://github.com/Polymer/polymer) element that displays a text with a transition effect. Although the same appearance can be obtained with pure CSS transitions, the cat-text true power is revealed when used in conjunction with other elements, like [cat-image](https://github.com/the-catalin/cat-image)

## Short example:

<!--
```
<custom-element-demo>
  <template>  	
    <link rel="import" href="cat-text.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<cat-text
	transition-type="slide"
	slide-offset="180"
	transition-direction="right"
	transition-duration="1"
	transition-delay="0">
	This is a sample text
</cat-text>
```

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install --save cat-text
```

Or [download as ZIP](https://github.com/the-catalin/cat-text/archive/master.zip)

## Usage

1. Import Web Components' polyfill (if needed):

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/cat-text/cat-text.html">
    ```

3. Start using it!

	```html
	<cat-text>Your text here</cat-text>
	```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## History

For detailed changelog, check [Releases](https://github.com/the-catalin/cat-text/releases).

## License

[The MIT License (MIT)](https://opensource.org/licenses/MIT)

Copyright (c) 2017 Catalin Ungureanu