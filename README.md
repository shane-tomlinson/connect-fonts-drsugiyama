# connect-fonts-drsugiyama

A [connect-fonts](https://github.com/shane-tomlinson/connect-fonts) fontpack for the Dr Sugiyama font.

## Usage

1. Include [connect-fonts](https://github.com/shane-tomlinson/connect-fonts) in a node module.
```
const font_middleware = require("connect-fonts");
```

2. Include the font packs that you want to serve.
```
const drsugiyama = require("connect-fonts-drsugiyama");
```

3. Add a middleware by calling the `setup` function.
```
    app.use(font_middleware.setup({
      fonts: [ drsugiyama ],
      allow_origin: "https://exampledomain.com"
    }));
```

4. Add a link tag to include the font CSS.
```
    <link href="/en/drsugiyama/fonts.css" type="text/css" rel="stylesheet"/ >
```

5. Set your CSS up to use the new font by using the "Dr Sugiyama" font-family.
```
   body {
     font-family: 'Dr Sugiyama', 'sans-serif', 'serif';
   }
```


## Author
* Shane Tomlinson
* shane@shanetomlinson.com
* stomlinson@mozilla.com
* set117@yahoo.com
* https://shanetomlinson.com
* http://github.com/stomlinson
* http://github.com/shane-tomlinson
* @shane_tomlinson

## Credits

Original font set downloaded from Google Font Directory. Dr Sugiyama created by [Alejandro Paul](sudtipos@sudtipos.com)

## License

This software is licenced under version 2.0 of the MPL

  https://www.mozilla.org/MPL/

Fonts are licensed under version 1.1 of the SIL Open Font License

  http://scripts.sil.org/OFL


