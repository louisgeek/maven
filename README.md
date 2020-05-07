# maven

 ```
  allprojects {
  	repositories {
		...
		//github 
	 // maven { url "https://raw.githubusercontent.com/louisgeek/maven/master" }
 maven { url "https://code.aliyun.com/louisgeek/maven/raw/master" }
        
  	}
  }
  ```
  
  ```
  dependencies {
		implementation 'com.github.louisgeek:xwalk_core_library:23.53.589.4'
        implementation 'com.github.louisgeek:kaldi-android:5.2_20200502'
             
  }
  ```
