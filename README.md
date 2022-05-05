# prettier-config-christianecg

![prettier-logo](https://img.shields.io/badge/prettier--config--christianecg-v1.0.0-blue)
![GitHub followers](https://img.shields.io/github/followers/christianecg?style=social)
![Twitter Follow](https://img.shields.io/twitter/follow/christianecg_?style=social)

This package provides a ChristianECG extensible prettier configuration.

## Usage

I provide an exported configuration object in the package. To use it, you should install our package.

```shell
npm i prettier-config-christianecg -D
```

Then, you can use it in your prettier configuration as an extended configuration on your prettier.config.js file.

```javascript
module.exports = {
	~
	...require('prettier-config-christianecg'),
	~
}
```

Feel free to modify the rules and add your own when you want.

## Contributing

If you want to contribute, you can fork the repository and make your own changes.

I am very open to any contribution, and I will try to add it to the package as soon as possible.

## License

To guarantee the quality of the package, I will only release it under the MIT license. You can find the license in the [LICENSE](LICENSE) file.
