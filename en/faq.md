# FAQ

## Why do I see the "App not found" issue

I am using Intellij IDEA and when I start the "HelloWorld" sample application in the IDE, I got the following error stack:

```
Exception in thread "main" org.osgl.exception.UnexpectedException: App not found. Please make sure your app start directory is correct
	at act.Act.start(Act.java:307)
	at act.Act.startApp(Act.java:269)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at act.boot.app.RunApp.start(RunApp.java:64)
	at act.Act.start(Act.java:610)
	at demo.helloworld.HelloWorldApp.main(HelloWorldApp.java:24)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at com.intellij.rt.execution.application.AppMain.main(AppMain.java:147)
```

### Answer

You need to update the Run configuration and make sure working directory is set correctly:
![image](https://cloud.githubusercontent.com/assets/216930/23855130/a2136556-0848-11e7-8184-2433004b123b.png)


