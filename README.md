# react-native-photo-grid-frame
React Native component that builds a grid of photos with a Dynamic Photo Size

## Install

`npm install react-native-photo-grid-frame --save`

## S reenshots
![alt text](https://raw.githubusercontent.com/sivarajng/react-native-photo-grid-frame/master/images/sample.jpg)
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
import { PhotoGrid } from './PhotoGrid';
import Photos from './Photos';


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