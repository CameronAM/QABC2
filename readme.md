
# The QABC website

This generates the qabc website - http://www.qabc.org.au/

# Getting started
This application uses [Metalsmith](http://www.metalsmith.io/) to generate a static site.

1. Install the latest version of nodejs.
2. Install [yarn](https://yarnpkg.com/en/)
3. Run `yarn` in the checkout directory to pull in the dependancies
4. Run `node .\node_modules\metalsmith\bin\_metalsmith` to build the site
5. The site will be generated in the `build` directory

I use [http-server](https://www.npmjs.com/package/http-server) to test locally before deployment.
