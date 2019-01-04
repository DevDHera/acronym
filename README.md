# @devdhera/acronym

<p align="center">
    <a href="https://github.com/DevDHera/acronym">
        <img src="https://img.shields.io/npm/v/@devdhera/acronym.svg" alt="npm version">
    </a>
    <a href="(https://packagephobia.now.sh/result?p=@devdhera/acronym">
        <img src="https://packagephobia.now.sh/badge?p=@devdhera/acronym" alt="install size">
    </a>
</p>

Simple Acronym generator for all the node lovers :heart:

## How to Install

Simply run the following in the terminal.

```sh
npm i @devdhera/acronym
```

## How to Use

```js
const acronym = require('@devdhera/acronym');

acronym('for your information', (err, resp) => {
    if (err) {
        console.log(err);
    }

    console.log(resp);
});
```