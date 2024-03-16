# code-zip-manager

[![npm version](https://badge.fury.io/js/code-zip-manager.svg)](https://www.npmjs.com/package/code-zip-manager)

A simple command-line Code zip Manager in JavaScript using fs-extra and inquirer.

## Installation

Install the required packages using npm:

```bash
npm install fs-extra inquirer --save
``` 

## Usage

```bash
const zipManager = require('code-zip-manager');

// Uncomment and run one of the functions below
// zipManager.createzip();
// zipManager.listzips();

```

## Creating a zip

Run the createzip function to interactively create a new code zip. You will be prompted to enter the zip name and code.

## Listing zip

Run the listzips function to display a list of available code zip.

The new version will be updated....
auto-zip