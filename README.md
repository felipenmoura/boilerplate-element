# Citation Custom Elements

This custom elemnt allows you to add stylized citations and blockquotes.

> Maintained by [Felipe N. de Moura](https://github.com/felipenmoura).

## Demo

> [Check it live](http://felipenmoura.github.io/citation-custom-element/).

## Usage

1. Import Web Components' polyfill:

	```xml
	<script src="http://cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130816/polymer.min.js"></script>
	```

2. Import Custom Element:

	```xml
	<link rel="import" href="src/citation.html">
	```

3. Start using it!

	```xml
	<x-citation>
    Citation content.
  </x-citation>
	```

## Options

Attribute   | Options               | Default   | Description
---         | ---                   | ---       | ---
`author`    | *string*              | ``        | The citation's author name
`href`      | *string*              | ``        | Citation source link or authors ref
`color`     | `red`, `gree`, `blue` | ``        | A color effect to the citation(and decoration)
`decoration`| *string*              | `—`       | A separator decoration to identify the author

## Theming

You can customize the element parts by adding properties to the following classes:

  .citation-container{}
  .citation-content{}
  .citation-author{}
  .citation-author a{}
  .citation-container:before{} /* the decoration icon */
  .citation-container.red{}
  .citation-container.yellow{}
  .citation-container.green{}


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](http://opensource.org/licenses/MIT)