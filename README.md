# Flowdroid Tutorial
Jar and config file compilation for UBC EECE571J

Command for running flowdroid in Windows
```
java -Xmx4g -cp soot-trunk.jar;soot-infoflow.jar;soot-infoflow-android.jar;slf4j-api-1.7.5.jar;slf4j-simple-1.7.5.jar;axml-2.0.jar     soot.jimple.infoflow.android.TestApps.Test "C:\mobile571\flowdroid\nightlyBuilds\leakyApp.apk" C:\Users\sampr\AppData\Local\Android\sdk\platforms

```

Command for running flowdroid in Linux or Mac OS

```
java -Xmx4g -cp soot-trunk.jar:soot-infoflow.jar:soot-infoflow-android.jar:slf4j-api-1.7.5.jar:slf4j-simple-1.7.5.jar:axml-2.0.jar soot.jimple.infoflow.android.TestApps.Test "C:\mobile571\flowdroid\nightlyBuilds\leakyApp.apk" C:\Users\sampr\AppData\Local\Android\sdk\platforms

```
