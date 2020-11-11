# Ionic App Auth

Ionic App Auth is a implementation of the [AppAuth-JS](https://github.com/openid/AppAuth-JS) for Ionic Users.
It includes code extensions for core cordova plugins to run the Ionic app such as [Advanced HTTP](https://github.com/silkimen/cordova-plugin-advanced-http) and [SafariViewController](https://github.com/EddyVerbruggen/cordova-plugin-safariviewcontroller).

The cordova plugins are optional and can be replaced with Angular/React/Vue http handlers and/or Capacitor Plugins.
This library is intended to be as flexible with compatiblity as Ionic V5 is attempting to be.

## Installation

Run following command to install Ionic App Auth in your project.

```bash
npm install ionic-appauth --save
```

## Examples

- React/Capacitor : https://github.com/wi3land/ionic-appauth-react-demo
- Angular/Cordova : https://github.com/wi3land/ionic-appauth-ng-demo
- Angular/Capacitor : https://github.com/wi3land/ionic-appauth-capacitor-demo

**NOTE**: You can use [OktaDev Schematics](https://github.com/oktadeveloper/schematics#ionic) to install the code from the Angular examples above. Cordova and Capacitor are both supported. The installation isn't Okta-specific, it just prompts you for an `issuer` and `clientId`.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* [AppAuth-JS](https://github.com/openid/AppAuth-JS)
* [AppAuth-Ionic](https://github.com/Belicosus/AppAuth-Ionic)
