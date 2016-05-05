# Angular2 RxJS Socket.io chat-application

Features:
- JSON Web Token user authentication.
- Chat functionalities implemented using observable pattern and web socket.

Stack:
- Angular 2.0beta
- RxJS
- Bootstrap
- Socket.io
- Express

Build system is created with Webpack. List of webpack loaders used:
- <a href="https://github.com/TypeStrong/ts-loader">ts-loader</a>
- <a href="https://github.com/wbuchwalter/tslint-loader">tslint-loader</a>
- <a href="https://github.com/webpack/style-loader">style-loader</a>
- <a href="https://github.com/webpack/css-loader">css-loader</a>
- <a href="https://github.com/jtangelder/sass-loader">sass-loader</a>
- <a href="https://www.npmjs.com/package/url-loader">url-loader</a>
- ...
To see the full list of available loaders go to <a href="https://webpack.github.io/docs/list-of-loaders.html">webpack loaders</a>.

This boilerplate includes Typings(typeScript definition manager), which is somewhat redundant as typedefinitions for NG2 and RxJS are maintained in the npm packages. You can still add the regular d.ts files with 'typings install <package>' command.

References:
- https://github.com/AngularClass/angular2-webpack-starter
- https://github.com/joeeames/WebpackFundamentalsCourse
- https://github.com/auth0-blog/angular2-authentication-sample
