# @honkit/honkit-plugin-ga

HonKit plugin for Google Analytics 4.

## Install

Install with [npm](https://www.npmjs.com/):

    npm install @honkit/honkit-plugin-ga

## Usage

Install with npm and use it for your book with in the `book.json`:

```json
{
    "plugins": ["@honkit/honkit-plugin-ga"],
    "pluginsConfig": {
        "ga": {
            "trackingID": "G-XXXXYYYY",
            "anonymizeIP": true
        }
    }
}
```

## Options

| Name        | Type    | Default  | Description                                                |
|-------------|---------|----------|------------------------------------------------------------|
| trackingID  | string  | Required | The tracking ID of your gtag service.                      |
| anonymizeIP | boolean | false    | Whether the IP should be anonymized when sending requests. |

## Documents

- https://developers.google.com/analytics/devguides/collection/gtagjs/pages

## Changelog

See [Releases page](https://github.com/honkit/honkit-plugin-ga/releases).

## Running tests

Install devDependencies and Run `npm test`:

    npm test

## Contributing

Pull requests and stars are always welcome.

For bugs and feature requests, [please create an issue](https://github.com/honkit/honkit-plugin-ga/issues).

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Author

- azu: [GitHub](https://github.com/azu), [Twitter](https://twitter.com/azu_re)

## License

MIT © azu
