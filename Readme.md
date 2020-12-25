# Burp Loader
	**Prequisite -> Installed Java and Burp Suite Pro**
	**Download Latest Version of Burp Suite Pro from Port Swigger's official website and Install It. Then Follow Below Steps for Activation**
-----------------------------------------------------------------
	**1. Place Both files in this Directory**
		If Windows	: C"\User\abcd\AppData\local\BurpSuitePro\
		If Linux 	: /opt/BurpSuitePro
	**2. Run This Command. Replace ___ with Version**
		1. If Windows:
			"C:\Program Files\Java\jdk-13.0.2\bin\java.exe" --illegal-access=permit -Dfile.encoding=utf-8 -javaagent:BurpSuiteLoader_v2020.11.3.jar -noverify -jar burpsuite_pro_v202_____.jar
		2. If Linux:
			/usr/lib/jvm/java-11-openjdk-amd64/bin/java --illegal-access=permit -Dfile.encoding=utf-8 -javaagent:BurpSuiteLoader_v2020.11.3.jar -noverify -jar burpsuite_pro_v202_____.jar
	**3. If you have problems with activate license, you can use old burploader**
		java -jar burploader-old.jar
	**4. Activate Burp Suite Pro Manually with Burploader-old.jar**
		1. Copy Licence Request from Loaded BurpSuite_Pro to Burploader-old
		2. Copy license response from Burploader-old to BurpSuite_Pro, and next. Done
