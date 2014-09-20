liberty-server
==============

WebSphere Liberty Profile assembly (to deploy as maven artifact).

Please first execute "getliberty.sh" in order to download Liberty setup files:

* wlp-developers-runtime-8.5.5.3.jar
* wlp-developers-extended-8.5.5.3.jar

Of course, you can also manually download them if you prefer.

To unpack/install Liberty just run:

    java -jar wlp-developers-runtime-8.5.5.3.jar --acceptLicense .
    java -jar wlp-developers-extended-8.5.5.3.jar --acceptLicense .

This will create a Liberty runtime in folder "wlp".

You can proceed to make whatever changes you like to "wlp" contents.

To create the Liberty assembly artifact just run:

    mvn clean package


