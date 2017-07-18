# sample-react-apollo-problem
Sample showing [issue #860](https://github.com/apollographql/react-apollo/issues/860) whereby a version of `react-dom` is being installed as an `optionalDependencies` within the `node_modules` folder of `react-apollo`

https://github.com/apollographql/react-apollo/issues/860

## Setup

    yarn install


## Problem
Open the `node_modules`.  React-dom is in both `node_modules` and the `react-apollo/node_modules` folder:

![Folder Structure](https://user-images.githubusercontent.com/185555/28298180-efaf3f5c-6bc5-11e7-9e4e-a011b0310c1a.png)




