# Install de dependencies

`npm install`

To run the test suite
`npm test`

## Test cases

There are many unit tests (Using 'jest' just running 'jest' or using on the VS Code integrated view (Install Facebook Jest Plugin for VS Code ).

```javascript
```

```javascript
```

The test case for main API function is :

```javascript
test("test ", () => {
    expect(result).toEqual(expected);
});
```

## TODO

-   [ ] Check the TODO tags on the code evaluate and refactor some functions
-   [ ] Create test cases with data set with 48 hours (48 data points)
-   [ ] Create test cases with special condition scenarios ( datapoints with zeros)
-   [ ] Validate the [implementation](https://github.ibm.com/Watson-IoT/munich-iot-dataset-sorting/blob/078a69a404f017cbf5f60147ddcfd6a751e0a96f/src/energy-prediction-graph-dataset.js#L179) proposed for the scenario :

```javascript
What to do for the scenario:
              nodeA.negativeNumbers === nodeB.negativeNumbers &&
              nodeA.highestNegative === nodeB.highestNegative
```
