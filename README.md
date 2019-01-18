
This is a simple Progressive Web App using Angular 5 that tracks real-time cryptocurrency prices. Find your top favourite coins here, like Bitcoin, Ethereum, Ripple and more. What's more, you can add this app to your iPhone and Android Home Screen now.

## Features

* Pure front end coding, no back end services;
* Fetch real-time price data from [CryptoCompare's public APIs](https://www.cryptocompare.com/api/) every 15 seconds;
* Colour changes to indicate real-time price change;
* Draw historical price trends using [Chart.js](http://www.chartjs.org/) with customised styles and functions;
* Integrated with [Ant Design](https://ng.ant.design/) for simple and unified visual style;
* Cross-browser compatability and mobile-friendly;
* Support Progressive Web Apps' features. Now you can add it to your iPhone and Android Home Screen, or into Chrome Apps.


## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Serving with http-server to Support Service Worker

Because `ng serve` does not work with service workers, you must use a separate HTTP server to test your project locally. You can use any HTTP server. The example below uses the http-server package from npm. To reduce the possibility of conflicts, test on a dedicated port.

```bash
cd dist
npx http-server -p 8080
```

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Get angular help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
