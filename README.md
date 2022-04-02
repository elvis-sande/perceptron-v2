Neural Network JavaScript library for Coding Train tutorials

## Examples / Demos
Here are some demos running directly in the browser:
* [XOR problem](https://github.com/elvis-sande/perceptron-v2/examples/xor/)
* [Handwritten digit recognition](https://github.com/elvis-sande/perceptron-v2/examples/mnist/)
* [Doodle classifier](https://github.com/perceptron-v2/elvis-sande/examples/doodle_classification/)

## To-Do List

* [x] Redo gradient descent video about
* [x] Delta weight formulas, connect to "mathematics of gradient" video
* [x] Implement gradient descent in library / with code
    * redo this challenge
    * cover softmax activation, cross-entropy
    * graph cost function?
    * only use testing data
* [ ] Support for neuro-evolution
    * [ ] play flappy bird (many players at once).
    * [ ] play pong (many game simulations at once)
    * [ ] steering sensors (a la Jabril's forrest project!)
* [ ] Combine with ml5 / deeplearnjs

## Getting Started

### Prerequisites

You need to have the following installed:

1. Nodejs
2. NPM
3. Install the NodeJS dependencies via the following command:

```
npm install
```

### Installing

This Project doesn't require any additional Installing steps

### Documentation

* `NeuralNetwork` - The neural network class
  * `predict(input_array)` - Returns the output of a neural network
  * `train(input_array, target_array)` - Trains a neural network

## Running the tests

The Tests can either be checked via the automaticly running CircleCI Tests or you can also run `npm test` on your PC after you have done the Step "Prerequisites"

## Built With

* [Nodejs](https://nodejs.org/) - The code language used
* [CircleCI](https://circleci.com/) - Automated Test Service
* [Jest](https://facebook.github.io/jest/) - Testing Framework used

## Contributing

Please send PullRequests. These need to pass a automated Test first and after it will get reviewed and on that review either denied or accepted.

## Libraries built by the community

Here are some libraries with the same or similar functionality to this one built by the community:

- [Java Neural Network Library](https://github.com/kim-marcel/basic_neural_network) by [kim-marcel](https://github.com/kim-marcel)
- [Library-less Java Neural Network](https://github.com/Fir3will/Java-Neural-Network) by [Fir3will](https://github.com/Fir3will)
- [Python Neural Network Library](https://github.com/Gabriel-Teston/Machine-Learning) by [Gabriel-Teston](https://github.com/Gabriel-Teston)
- [Python Neural Network Library](https://github.com/GypsyDangerous/simple-deep-neural-network/blob/master/README.md) by [David Snyder](https://github.com/GypsyDangerous)
- [JavaScript Multi-Layer Neural Network Library](https://github.com/notshekhar/neuralnet) by [Shekhar Tyagi](https://github.com/notshekhar)
- [F# Neural Network Library](https://github.com/jackroi/NeuralNetwork-fsharp) by [jackroi](https://github.com/jackroi)
- [TinyNeuralNetwork4Java](https://github.com/anirudhgiri/TinyNN4J) by [Anirudh Giri](https://github.com/anirudhgiri)
- [miniANN Neural Network Library JavaScript](https://github.com/savvysiddharth/mini-ANN-js) by [Siddharth Maurya](https://github.com/savvysiddharth)
- [Convolutional Neural Network Library JavaScript](https://github.com/therealyubraj/CNN_JS) by [Yubraj Sharma](https://github.com/therealyubraj)

Feel free to add your own libraries.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/CodingTrain/Toy-Neural-Network-JS/tags).

## License

This project is licensed under the terms of the MIT license, see LICENSE.
