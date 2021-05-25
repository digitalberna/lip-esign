# lip-esign

Web Components implementation of the LIP eSign system

This repository is aimed mainly to developers.

## Setup

Install dependencies:

```bash
$ npm install @lip/esign
```

# Add in project

You can import the components in your project in different way depending on the environment:

as Javascript files with a bundler (like Webpack)

```javascript
// import components
import '@lip/esign/index';

// import utils
import { validateCode } from '@lip/esign/utils';
```

as Javascript files from HTML without a bundler

```html
<script type="module" src="./node_modules/@lip/esign/index.js"></script>
<script type="module" src="./node_modules/@lip/esign/utils.js"></script>
```
