# CGPT_scaleWeightsAndMeasures

#### Weights and Measures scaling using OpenAI API

This is a simple/toy REST service in Node.js and Express using OpenAI API for converting and scaling weights and measures (it can be used for other purposes with a few changes).

You will need Node.js and npm

Get OpenAI API key. Copy `.env.example` to `.env` and add the API key there.

Do an `npm install` and run with `npm start`

It should be possible to test some weights and measures scaling with something like:

`http://localhost:3000/scaleWeightsAndMeasures?quantity=20&fromUnit=ounces&toUnit=milliliters&scaleFactor=2`

from a browser. It will comeup with an answer like:

`{"scaledValue":"Answer: 40 ounces is equal to 1136.5225 milliliters"}`

Experiment with training data and question !

