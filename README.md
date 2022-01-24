# Pretty-print3r

This module prettifies parsed elements from text documents.

## How does Pretty-print3r work?

Pretty-print3r is a simple nodejs module that takes a string argument as part of its start script and prints a .html document. The argument can be one or many sentences and must consist of either regular sentences, questions or exclamations.

The module prints to its internal output.html file in the IO directory. The format is a html document that identifies the three various sentence types and highlights them accordingly: regular sentences are italic, questions are bold and exclamations are red text.

Pretty printer depends on doc-pars3r to get a parsed document that can be broken down into its various parts and sub-parts, i.e. sentences, words and closing punctuation.

## Prerequisites

- Node.js [installed](https://nodejs.org/en/download/)
- NPM installed (this comes with node.js)

## Using Pretty-print3r

1. Clone the Pretty-print3r repository to your local machine.

NOTE: pretty-print3r is under development and is not published to npm. THEREFORE, PRETTY-PRINT3R SHOULD NOT AT PRESENT BE USED IN A PRODUCTION ENVIRONMENT.

```
git clone https://github.com/niall-thurrat/1dv610-l2-pretty-printer.git
```

2. Install npm dependencies from the root directory

```
npm install
```

3. Use a start script with a string argument that contains one or many sentences.

NOTE: mid sentence punctuation e.g. commas, semi-colons, etc., are not handled and will throw errors.

```
npm start 'one sentence. two sentences? three sentences!'
```

4. Open the output.html file in a browser to see your pretty html list formatted results.
