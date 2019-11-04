# react-native-react-native-couchbase-orm

## Getting started

`$ npm install react-native-couchbase-orm --save`

### Mostly automatic installation

`$ react-native link react-native-couchbase-orm`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-couchbase-orm` and add `ReactNativeCouchbaseOrm.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libReactNativeCouchbaseOrm.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.reactlibrary.ReactNativeCouchbaseOrmPackage;` to the imports at the top of the file
  - Add `new ReactNativeCouchbaseOrmPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-couchbase-orm'
  	project(':react-native-couchbase-orm').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-couchbase-orm/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-couchbase-orm')
  	```


## Usage
```javascript
import ReactNativeCouchbaseOrm from 'react-native-couchbase-orm';

// TODO: What to do with the module?
ReactNativeCouchbaseOrm;
```
