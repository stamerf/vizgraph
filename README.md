# VizGraph

A simple tool for Using [Graphviz](https://graphviz.gitlab.io/). Based on [Viz.js](https://github.com/mdaines/viz.js) & [Electron](https://github.com/electron/electron).

This tool was fokred and modified in such a way that it is possible to visualise json files quickly.

---

CircleCI Building: [![CircleCI](https://circleci.com/gh/jcf94/vizgraph.svg?style=svg)](https://circleci.com/gh/jcf94/vizgraph)

---

Sample usage from [Graphviz Gallery](https://graphviz.gitlab.io/gallery/):

![](doc/img/exp1.png)

![](doc/img/exp2.png)

---

This project is on its **beta release** now.

# Usage

The major framework is based on Electron, so it should be worked on **All Platforms** that support Node.js( Exp. Windows, Mac and Linux).

## For Developers

First, make sure you have a proper [Node.js Environment](https://nodejs.org/en/download/):

```bash
node -v
npm -v
```

Then start it easily.

```bash
git clone https://github.com/jcf94/vizgraph.git
cd vizgraph
npm install
npm start
```

Enjoy it.

Use [electron-builder](https://github.com/electron-userland/electron-builder) to pack release for platforms you like.

## For Users

Get the latest [release](https://github.com/jcf94/vizgraph/releases).

Now we have portable packages for Windows(.exe) and Most Linux Repositories(.AppImage).

## Addition to visualize JSON file (Fork of original Project)

For a different project I needed support to translate JSON files to a graph. JSON files are easier to handle and interpret in different software projects than vizgraph text. For this purpose a file starting with ## (double hashtag) will be read as json and translated to vizgraph. There is no possibility to change the default visual settings with the json file right now. An example file can be found on the top level of this repository (exampleJSONgraph.txt).
