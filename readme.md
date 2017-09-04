# CoEDL d3.js Playground

## About

This repository contains a collection of experiments and examples for using the d3.js visualisation library with [primarily] language data.

## Usage

The recommended method for exploring the examples is to clone the repository, and launch an HTTP server at the root of the folder (e.g. where this `readme.md`, and the `dist/` and `sandbox` directories reside). In OS X, you can simply launch an HTTP server on port 8000 using the python command:

```bash
python -m SimpleHTTPServer 8000
```

which you can access on `http://localhost:8000`, and the hello world example on `http://localhost:8000/sandbox/hello-world/`

### Why not just open `/sandbox/some-folder/index.hml`?

This will be just fine for examples that don't require loading in data from an external source. Local data need to be loaded in with a `http://` protocol (i.e. not `file:///`).

## Contribution

To make a contribution to the examples, fork the repository, and add a new folder within the `sandbox` directory, e.g. `my-awesome-example`. The the minimum, there should be an `index.html` including the d3 demo, as well as a `readme.md` explaining what the example/experiment demonstrates.

If you have additional dependencies (e.g. data, images), place them into appropriately named subdirectories within your `my-awesome-example` root, e.g. `/sandbox/my-awesome-example/data`.
