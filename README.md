# Angular 4 Web Application Starter Kit

This is a starter kit for building web applications in Angular 4. The following features are configured:

- Security vulnerability checking with Node Security Platform
- Linting using tslint for typescript and stylelint for css
- Webpack build process with a production build and local build with hot reloading using webpack-dev-server.
- Unit testing and code coverage with Karma and Jasmine<br/>
**Currently there is no end-to-end testing framework configured, such as protractor. However, this may be added in the future.*

## Get Started

1. **Install [Node 6](https://nodejs.org)**.
2. **Clone this repository.** - `git clone https://github.com/bschneier/angular-starter-kit.git` or [download the zip](https://github.com/bschneier/angular-starter-kit/archive/master.zip)
3. **Open a command prompt and navigate to the directory you just created.**
4. **Install Node Packages.** - `npm install`
5. **Run the app.** - `npm start`<br/>
This will check all packages for any security vulnerabilities, lint all typescript and css files and run all unit tests before deploying a local instance of the application in webpack-dev-server with hot reloading.