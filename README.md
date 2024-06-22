# Nord Dark Theme

## Installation

### Build the extension with web-ext

Install [web-ext](https://github.com/mozilla/web-ext):

```text
npm install --global web-ext
```

Build the extension with `web-ext` command:

```text
cd src
web-ext build
```

This command will generate a ZIP file.

### Install the theme

1. Set `xpinstall.signatures.required` to `false` in `about:config`.
2. Click `Install Add-on From File...` in `about:addons`. Select the ZIP file built in the previous step.

## Credit

Thie theme is modified from [Nord Dark Theme by Crozbo](https://addons.mozilla.org/en-US/firefox/addon/nord-dark-theme/).

## License

Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
