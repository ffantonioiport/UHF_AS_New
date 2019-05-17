# UHF_AS_New
The new version of the R2000 library is used, and the read and write count data is returned by callback.

##  Import dependent library
**AndroidStudio** Added in dependencies in build.gradle

```
//Outer layer build.gradle
allprojects {
    repositories {
        jcenter()
        maven { url 'https://jitpack.io' }
    }
}
```
```
 dependencies {
    compile 'com.github.SpeedataG:UHF:7.8.3'
  }
```
## Low battery usage instructions
  * Battery power is less than 15%. UHF is forbidden.
  
## API documentation

	Detailed interface description in showdoc，地址：http://www.showdoc.cc/web/#/79868361520440?page_id=452063154391852

Beijing Spirent Technology Co., Ltd.

URL http://www.speedata.cn/

Technical support Tel: 155 4266 8023

QQ：2480737278
