# res
### dimension color fontSize

add this to your project build.gradle
```
allprojects {
    repositories {
       ...
        maven { url 'https://jitpack.io' }
    }
}
```
then add this to your app module build.gradle
```
 compile 'com.github.hongqianfly:res:2.0'
```
