GAEBTCMiner
=========
Google App Engine Bitcoin Miner (Java)

Background Infomation
---------
Google App Engine is Google's computing platform, it provide some free CPU hours per application. Each user can create up to 10 applications for free. I have checked the [Terms of Service](https://developers.google.com/appengine/terms), and do not think this violate it. If you have any concern, please stop using it immediately.
Installation Guide
---------
Due to how Google App Engine works, you need the SDK to install it. Here are the steps:

• Install Java SDK by following the document from [Google App Engine](https://developers.google.com/appengine/docs/java/gettingstarted/installing)

• Edit src/net.sdiz.bitcoin.jdo/Config.java and give your miner account details

• Register a new GAE account or use the exsiting one, you need a mobile phone

• Create applications as many as you can, pick the default options is fine

• Deploy the project with the application names created just above step 

• Repeat the last three steps for the other application names left

Alternative Installation
---------
If you really hate eclipse, there is an ant build.xml provided. But you are on your own.
