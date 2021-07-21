# cordova-plugin-video-trimming-editor


https://github.com/iknow4/Android-Video-Trimmer  
https://github.com/HHK1/PryntTrimmerView  

![ios](https://user-images.githubusercontent.com/4780752/63224897-d8d56700-c205-11e9-8756-0d17b3ca4b3e.png)
![android](https://user-images.githubusercontent.com/4780752/63224898-d96dfd80-c205-11e9-808c-2d6e0e2decbc.png)

## Requirement
cordova >= 7.1.0  
cordova-ios >= 4.5.0  
cordova-android >= 8.0.0  

https://github.com/dpa99c/cordova-plugin-androidx  
https://github.com/nrikiji/cordova-plugin-carthage-support  
https://github.com/akofman/cordova-plugin-add-swift-support  
[Carthage(>= 0.3.3)](https://github.com/Carthage/Carthage)  


## Installation
```
cordova plugin add cordova-plugin-video-trimming-editor
```

## Supported Platforms
- iOS  
- Android  

## Example


```js

VideoTrimmingEditor.open(
  {
    input_path: '/path/to/xxx.mp4',
    video_max_time: 10,
  },
  function(result) {
    console.log(result); // { output_path: "/path/to/zzz.mp4" }
  },
  function(error) {
  }
);
```


