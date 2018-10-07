#### 使用gradle-release和maven-publish
##### 发布到central仓库
```bash
gradle clean build release publishMavenPublicationToCentralRepository 
```
##### 发布到release或者snapshot
###### 发布release仓库
```bash
gradle clean build release publishMavenPublicationToReleaseRepository 
```
###### 发布到snapshot仓库
```bash
gradle clean build publishMavenPublicationToReleaseRepository 
```
#### 发布到jecenter仓库
```bash
gradle clean build release bintrayUpload
```
