Shopping-mall Web Site
======================
* 대학교4학년2학기 웹프로그래밍 수업을 통해 만든 "런치박스" 쇼핑몰 웹 사이트   
# Requirements
* [spring Framwork 4.8.1](https://spring.io/tools#main)
* [jdk-14.0.2](https://www.oracle.com/java/technologies/javase/jdk14-archive-downloads.html)
* [eclips](https://www.eclipse.org/)
* [maven](http://maven.apache.org/)
# instructions
1. 파일들을 eclips에 import 시킵니다.   
[File] -> [import] -> [General] -> [Existing Projects into WorkSpace] -> [Select root directory]에서 선택합니다. -> [Finish]
2. eclipse 아래부분에 [server] -> [Tomcat v8.5 Server at localhost] 더블클릭 -> [Modules]에서  Path : /proj 를 / 로 편집.
3. import가 되고 나서 만약 프로젝트에 x 표시가 나타난다면
[프로젝트에서 오른쪽 마우스 클릭] -> [Build Path] -> [configure build path...] -> [Libraries] -> [JRE System Library] 더블클릭 -> [Alternate JRE] : jdk-14.0.2 선택 -> [Apply]   
만약 이럼에도 없어지지 않는다면 [project] -> [clean] 을 한번 해보세요.
4. 프로젝트 선택 후 [Run as] -> [Run on Server] 를 선택합니다.   
*전 apache tomcat 8.5 version 을 사용했습니다.(설치:https://tomcat.apache.org/download-80.cgi)
# use technology
1. eclipse
2. spring mvc framework
3. jdk-14.0.2
4. apache-tomcat 8.5
5. mysql 8.0
6. mybatis
7. html/css/javascript
# at a glance
![2](https://user-images.githubusercontent.com/55746374/101240102-6f49d680-3730-11eb-9b87-801e79a16655.PNG)
