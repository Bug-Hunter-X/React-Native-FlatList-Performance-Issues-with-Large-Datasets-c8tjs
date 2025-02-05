# React Native FlatList Performance Optimization

This repository demonstrates a common performance issue in React Native's `FlatList` component when dealing with large datasets and provides solutions for optimization.

## Problem

Rendering a large number of items in a `FlatList` can lead to performance problems, such as dropped frames, UI unresponsiveness, and even crashes.  This is due to the overhead of rendering many components simultaneously.

## Solution

Several strategies can mitigate these performance issues:

* **Pagination:** Load and render data in smaller chunks as the user scrolls.
* **Virtualization:** Only render the items currently visible on the screen.
* **Component Optimization:** Optimize the rendering of individual items in the list to reduce the workload.

This repository provides examples of implementing these optimization techniques.

## Usage

1. Clone this repository.
2. Run `npm install` to install the dependencies.
3. Run `npx react-native run-android` or `npx react-native run-ios` to start the app.

Compare the performance of the buggy and optimized versions of the `FlatList` component.