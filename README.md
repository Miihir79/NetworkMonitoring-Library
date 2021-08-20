# NetworkMonitoring-Library

The latest gradle version is not supported by jitpack.. will be shifting the library.
## Dependencies
Add to build.gradle project level file
``` Gradle
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  ```
  Add to build.gradle app level file
  ``` Gradle
  dependencies {
	        implementation 'com.github.Miihir79:NetworkMonitoring-Library:Tag'
	}
  ```
