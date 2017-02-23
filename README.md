# \<hl7visor\>

A page for viewing HL7 v.2.x in a human-readable format.

The page is served [here](https://alessiogiambrone.github.io/hl7visor_polymer/).

## How to work on the project

### Install the Polymer-CLI and all the dependencies

First, make sure you have the
  [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed.

Then build the dependencies with `bower install`.

Finally run `polymer serve` to serve your application locally.

### Viewing hl7visor

```
$ polymer serve
```

### Building hl7visor

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

### Running Tests

TODO: tests are to be implemented....

```
$ polymer test
```

Your application is already set up to be tested via
  [web-component-tester](https://github.com/Polymer/web-component-tester).

Run `polymer test` to run your application's test suite locally.
