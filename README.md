# CGPT_scaleWeightsAndMeasures

### Weights and Measures scaling using ChatGPT

You will need Node.js and npm

Get OpenAI API key. Copy `.env.example` to `.env` and add the API key there.

Do an `npm install` and run with `npm start`

It should be possible to test some weights and measures scaling with something like:

`http://localhost:3000/scaleWeightsAndMeasures?quantity=20&fromUnit=ounces&toUnit=milliliters&scaleFactor=2`

from a browser. It will comeup with an answer like:

`{"scaledValue":"Answer: 40 ounces is equal to 1136.5225 milliliters"}`

