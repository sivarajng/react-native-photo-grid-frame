# react-native-photo-grid-frame
React Native component that builds a grid of photos with a Dynamic Photo Size and Popup the Photo on click.

## Install

`npm install react-native-photo-grid-frame --save`

## Screenshots
![alt text](https://raw.githubusercontent.com/sivarajng/resources/master/react-native-photo-grid-frame/images/screenshot1.png)
![alt text](https://raw.githubusercontent.com/sivarajng/resources/master/react-native-photo-grid-frame/images/screenshot2.png)
![alt text](https://raw.githubusercontent.com/sivarajng/resources/master/react-native-photo-grid-frame/images/screenshot3.png)
![alt text](https://raw.githubusercontent.com/sivarajng/resources/master/react-native-photo-grid-frame/images/screenshot4.png)

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
import { PhotoGrid } from 'react-native-photo-grid-frame';
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
