# Property Order [<img src="https://s3.amazonaws.com/media-p.slid.es/uploads/467124/images/2872758/stylelint-icon-black.svg" alt="StyleLint" width="90" height="90" align="right">][stylelint]

[![npm version][npm-img]][npm-url]
[![dependency status][david-img]][david-url]

A [Stylelint][] config that sorts CSS properties the way [Recess][] did and
Bootstrap [did][]/[does][].

\*With some modifications & additions for modern properties.

## Usage

1.  Add [stylelint][] and this package to your project:
    ```sh
    npm install --save-dev stylelint @pazurite/stylelint-config
    ```
2.  Configure your stylelint configuration file to extend this package:
    ```js
    {
      "extends": "@pazurite/stylelint-config",
      "rules": {
        // Add overrides and additional rules here
      }
    }
    ```

## References

[@mdo on CSS Property Order][mdo-order]

[npm-url]: https://www.npmjs.com/package/@pazurite/stylelint-config
[npm-img]: https://img.shields.io/npm/v/@pazurite/stylelint-config
[david-url]: https://david-dm.org/pazurite/stylelint-config
[david-img]: https://img.shields.io/david/pazurite/stylelint-config
[stylelint]: https://github.com/stylelint/stylelint
[recess]: https://github.com/twitter/recess/blob/29bccc870b7b4ccaa0a138e504caf608a6606b59/lib/lint/strict-property-order.js
[did]: https://github.com/twbs/bootstrap/blob/f58997a0dae54dc98d11892afef9acb85bdc6a1e/.scss-lint.yml#L136
[does]: https://github.com/twbs/bootstrap/blob/ba878eb542ab6c04786741569ba089d02e9bea46/.stylelintrc#L36
[mdo-order]: http://markdotto.com/2011/11/29/css-property-order/
