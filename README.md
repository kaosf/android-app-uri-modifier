# Android App URI Modifier

This tool is suitable for [Android Empty App](https://github.com/kaosf/android-empty-app).

## Usage

```sh
./modify-android-uri 'http://myapp.mydomain.org'
```

The URI string `<string name="uri">http://app.example.com</string>` in `res/values/strings.xml` will be changed to `<string name="uri">http://myapp.mydomain.org</string>`.

## License

[MIT](http://opensource.org/licenses/MIT)
