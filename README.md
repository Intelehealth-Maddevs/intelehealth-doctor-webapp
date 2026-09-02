# IntelehealthUi

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.2.2.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
Node.js
   ```
   https://nodejs.org/en/
   ```
   
    
### Installing
A step by step series of examples that tell you how to get a development environment running
1. Clone or download this repository
2. Install all the dependencies.
```
"npm install"
```
3. Create a local `.env` file using `.env.example` as the list of required variables. Deployment builds must provide the same variables through the build environment or an injected `.env` file.
4. Start the server
```
"npm start"
```

5. Open in browser
```
 "localhost:4200"
```

### Environment configuration

`src/environments/environment.ts` and `src/environments/environment.prod.ts` are generated files and are not tracked by Git. The npm lifecycle scripts generate them before development, production builds, tests, linting, and end-to-end tests.

Run the generator directly only when needed:

```
npm run config-dev
npm run config-prod
npm run config-test
```

The generator fails when a required variable is missing, preventing a build with incomplete deployment configuration.

## Built With

* [Angular](https://angular.io/) - Angular Framework
* [Angular Material](https://material.angular.io/) - Designing
* [BootStrap](https://getbootstrap.com/) - Table, Cards and other UI design
