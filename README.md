# react-native-photo-grid-frame
React Native component that builds a grid of photos with a Dynamic Photo Size

## Install

`npm install react-native-photo-grid-frame --save`

## Usage

```
/**
 * Sample React Native App
 * https://github.com/facebook/react-native
 * @flow
 */
import React, { Component } from 'react';
import {
  AppRegistry,
  ScrollView
} from 'react-native';
import { PhotoGrid } from './app/Pictures';
import Photos from './app/Photos';


export default class photoGrid extends Component {
  render() {
    return (
      <ScrollView>
        <PhotoGrid PhotosList={Photos} borderRadius={10}/>
      </ScrollView>
    );
  }
}

AppRegistry.registerComponent('photoGrid', () => photoGrid);
```