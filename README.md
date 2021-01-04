Portable Jekyll
==============

The portable version contains everything which is required to run Jekyll v3.2.1 on Windows:

* Ruby 2.0
* Ruby development Kit
* Git 2.0

##Usage Instructions##
Have a look at this [Wiki](https://github.com/madhur/PortableJekyll/wiki)

Copy this to environment variables:

```
D:\Code\PortableJekyll\ruby\bin; D:\Code\PortableJekyll\devkit\bin; D:\Code\PortableJekyll\git\bin;D:\Code\PortableJekyll\Python\App; D:\Code\PortableJekyll\devkit\mingw\bin;D:\Code\PortableJekyll\curl\bin
```

And create a new environment variable named SSL_CERT_FILE, value:

```
D:\Code\PortableJekyll\curl\bin
```

The setpath.cmd use the "%~dp0" to represent your current directory, after running it in command line, the setting is ok.

Then you can run jekyll new myblog or jekyll serve anywhere you want.
