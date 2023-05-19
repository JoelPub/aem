# aem
**第一次启动**
		   java -XX:MaxPermSize=256m -Xmx1536M -jar cq-quickstart-6.5.0.jar   
	publisher: java -Xmx1024M -jar cq-quickstart-6.5.0.jar -r publish  
**之后启动**
 ```javascript
		<aem-install>/crx-quickstart/bin/
		./start
```
**MVN:**
```javascript
	cd projects/hd_project
	mvn clean install -PautoInstallPackage
	cd projects/amp_project
	mvn clean install -PautoInstallPackage
```
