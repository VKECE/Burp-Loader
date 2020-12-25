1. burp/StartBurp has been compiled by a new version of the Java Runtime (class file version 53.0).
You should use java9+

2. Place the 2 files in the same directory, then run:

if Windows:

"C:\Program Files\Java\jdk-13.0.2\bin\java.exe" --illegal-access=permit -Dfile.encoding=utf-8 -javaagent:BurpSuiteLoader_v2020.11.3.jar -noverify -jar burpsuite_pro_v2020.11.3.jar

if Linux:

/usr/lib/jvm/java-11-openjdk-amd64/bin/java --illegal-access=permit -Dfile.encoding=utf-8 -javaagent:BurpSuiteLoader_v2020.11.3.jar -noverify -jar burpsuite_pro_v2020.11.3.jar

3. If you have problems with activate license, you should use to do it old burploader (for older versions like 2.1.07). Run:

java -jar burploader-old.jar

4. activate burp license manually with burploader-old.jar:

copy license request from loaded burpsuite_pro_v2020.11.3.jar to burploader-old, copy license response and paste to BurpSuite, press next. Done.

P.S.: There we use the same loader as in 2020.4 version (https://github.com/x-Ai/BurpSuiteLoader).

