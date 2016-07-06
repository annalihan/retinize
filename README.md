#retinize
retinize.js utilizing gm to automate down-scaling of images to target lower resolution or non-retina browsers. Accepts @4x and @2x resolutions, outputting to @2x, and @1x.

#Prerequisites
* Works in Node 0.12+.
* Requires [GraphicsMagick](https://github.com/aheckmann/gm) for Node. Please go there for installation directions and relevant questions.

#Install
1. Install [GraphicsMagick](https://github.com/aheckmann/gm)  for Node (follow instructions).
2.  Install retinize `npm install --save-dev retinize`
3.  Modify your `package.json`, regisiter task `retinize`.

> "scripts": {
    "retinize": "node node_modules/retinize/retinize.js \`pwd\`"
  }

#Usage
`npm run retinize`

