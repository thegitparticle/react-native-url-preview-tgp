
# react-native-url-preview-tgp - fork of react-native-url-preview


Parses text and wraps URLs , transform the url to a beautiful link preview

## Getting started 

`$ npm install react-native-url-preview --save`

## Usage 
```javascript
import RNUrlPreview from 'react-native-url-preview';

<RNUrlPreview text={"any text to be parsed , https://www.youtube.com/watch?v=Kmiw4FYTg2U"}/>
```

## Examples

Please refer to the [react-native-url-preview example](https://github.com/maherzaidoune/RNUrlPreviewExample) provided to see how `react-native-url-preview` can be used .

## Demo

<p align="center" >
        <a href="https://github.com/maherzaidoune/react-native-url-preview"><img src="https://i.imgur.com/dJLTTRr.gif" title="source: imgur.com" /></a>
        <a href="https://imgur.com/ruyH0PR"><img src="https://i.imgur.com/ruyH0PR.gif" title="source: imgur.com" /></a>
</p>

## Customization 

| Parameter                | Required? | Default                    | Type      | Description                                            |
| :----------------------- | :-------: | :------------------------- | :-------- | :----------------------------------------------------- |
| text                     |    YES    | Null                       | `string`  | The text that is parsed and where the URL is retrieved |
| title                    |    NO     | True                       | `Boolean` | determine whether the URL title is displyed or not     |
| description              |    NO     | True                       | `Boolean` | determine whether the URL description is displyed or not     |
| titleStyle               |    NO     | defaultStyle               | `style`   | self explanatory i believe                             |
| containerStyle           |    NO     | defaultStyle               | `style`   | you can pass a custom container style                  |
| imageStyle               |    NO     | defaultStyle               | `style`   | you can pass a custom image style                      |
| faviconStyle             |    NO     | defaultStyle               | `style`   | you can pass a custom favicon style                    |
| textContainerStyle       |    NO     | defaultStyle               | `style`   | you can pass a custom style for the text container     |
| descriptionStyle         |    NO     | defaultStyle               | `style`   | self explanatory i believe                             |
| titleNumberOfLines       |    NO     | 2                          | `number`  | self explanatory i believe                             |
| descriptionNumberOfLines |    NO     | Ipad?4:3                   | `number`  | self explanatory i believe                             |
| imageProps               |    NO     | `{ resizeMode: "contain"}` | `object`  | you can pass a custom props to image                   |
| requestOptions           |    NO     | `{}`                       | `object`  | pass additional options to url preview request
| onLoad                   |    NO     | `() => {}`                 | `function`| callback called when url preview data is loaded          |
| onError                  |    NO     | `() => {}`                 | `function`| callback called if url preview fails to load           |
## Credits 

- Thanks to [marouan frih](https://github.com/Madm0x) for the REGEX
- extract information from a URL with [link-preview-js](https://github.com/ospfranco/link-preview-js)
