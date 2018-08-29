# Wolfram's Cellular Automata in Node
### By Liam Ilan


Wolfram's Cellular Automata is a form of 1 dimensional cellular automata in witch all possible rules are encoded into one byte as described here:
http://mathworld.wolfram.com/CellularAutomaton.html

This is an implementation of this system in node.


## How to use

First clone the repo by using:

```bash
$ git clone https://liamilan@bitbucket.org/liamilan/wolfram-cellular-automata.git
```

To run the project, enter the directory, and then use:

```bash
$ node index.js 18
```
or:

```bash
$ node index.js {rule number between 0 to 255}
```

Interesting rules:
https://plato.stanford.edu/entries/cellular-automata/supplement.html


## Development

Initialize inside the directory using:

```bash
$ npm init
```

To run eslint use:

```bash
$ npm run lint
```
