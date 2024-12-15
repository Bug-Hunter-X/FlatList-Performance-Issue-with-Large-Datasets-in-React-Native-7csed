# React Native FlatList Performance Issue

This repository demonstrates a common performance problem encountered when using FlatList in React Native with large datasets. The initial implementation suffers from performance degradation or crashes due to inefficient rendering.

The solution implements optimization techniques to improve the performance significantly.

## Problem

The `DataFetch.js` file contains a basic implementation that fetches data from an API and renders it using FlatList.  When the dataset is large, the app becomes unresponsive or crashes due to the number of components that needs to be rendered. 

## Solution

The `DataFetchSolution.js` file demonstrates solutions to improve performance including pagination and virtualization techniques. These techniques significantly improve rendering performance when dealing with large datasets.

## Setup

1. Clone this repository
2. `npm install` or `yarn install`
3. Run the app on your preferred emulator or device.