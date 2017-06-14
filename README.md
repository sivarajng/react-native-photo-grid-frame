# react-native-photo-grid-frame
React Native component that builds a grid of photos with a Dynamic Photo Size

## Install

`npm install react-native-photo-grid-frame --save`

## Screenshots
![alt text](https://raw.githubusercontent.com/sivarajng/react-native-photo-grid-frame/master/images/screenshot1.png)
![alt text](https://raw.githubusercontent.com/sivarajng/react-native-photo-grid-frame/master/images/screenshot2.png)
![alt text](https://raw.githubusercontent.com/sivarajng/react-native-photo-grid-frame/master/images/screenshot3.png)
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