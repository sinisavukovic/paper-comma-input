[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/sinisavukovic/paper-comma-input)
[![Build Status](https://travis-ci.org/sinisavukovic/paper-comma-input.svg?branch=master)](https://travis-ci.org/sinisavukovic/paper-comma-input)

## &lt;paper-comma-input&gt;

`<paper-comma-input>` is a material design text field which automatically adds comma to separate out the digits.

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="paper-comma-input.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paper-comma-input value="1000"></paper-comma-input>
```

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install paper-comma-input --save
```

## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/paper-comma-input/paper-comma-input.html">
    ```

3. Start using it!

    ```html
    <paper-comma-input value="1000"></paper-comma-input>
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

1. Install [bower](http://bower.io/) & [polymer](https://www.npmjs.com/package/polymer-cli):

    ```sh
    $ npm install -g polymer-cli
    ```

2. Install local dependencies:

    ```sh
    $ bower install
    ```

3. Start development server and open `http://localhost:8080/components/paper-comma-input/`.

    ```sh
    $ polymer serve
    ```

## Credits

[Interesting by Default](https://www.interestingbydefault.com/)

## License

[MIT License](http://opensource.org/licenses/MIT)
