<#<a name="The project to automate testing of REST Services">The project to automate testing of REST Services Help Project at Reqres.in[Reqres.in](https://reqres.in/)</a>
<p  align="center">
<img src="images/logo/reqres.PNG">

</p>


# <a name="Contents">Contents</a>
+ [Description](#Description)
+ [Technologies and Tools](#Technologies-and-Tools)
+ [Launch Options](#Launch-Options)
  + [Commands for gradle](#Commands-for-gradle)
  + [Run in Jenkins](#Run-in-jenkins)
+ [Telegram notifications](#Telegram-notifications)
+ [Test results in Allure Report](#Test-results-in-Allure-Report)
+ [Integration with Allure TestOps](#Integration-with-Allure-TestOps)



# <a name="Description">Description</a>
  The project consists of API tests for the site https://reqres.in/.
  Brief list of facts about the project:
- [x] Used Models and Specifications (Specs)
- [x] Used by REST Assured to test GET, POST, DELETE services
- [x] Allure rest-assured listener with custom templates
- [x] Integration with `Allure TestOps`
- [x] Autotests as test documentation


# <a name="Technologies and Tools">Technologies and Tools</a>
<p  align="center">
  <code><img width="5%" title="IntelliJ IDEA" src="./images/logo/Idea.png"></code>
  <code><img width="5%" title="Java" src="./images/logo/Java.png"></code>
  <code><img width="5%" title="Selenide" src="./images/logo/Selenide.png"></code>
  <code><img width="5%" title="Gradle" src="./images/logo/Gradle.png"></code>
  <code><img width="5%" title="JUnit5" src="./images/logo/Junit5.png"></code>
  <code><img width="5%" title="Allure Report" src="./images/logo/Allure.png"></code>
  <code><img width="5%" title="Allure TestOps" src="./images/logo/TestOps.png"></code>
  <code><img width="5%" title="Github" src="./images/logo/GitHub.png"></code>
  <code><img width="5%" title="Jenkins" src="./images/logo/Jenkins.png"></code>
  <code><img width="5%" title="REST-Assured" src="./images/logo/rest-assured-logo.PNG"></code>
  <code><img width="5%" title="Selenoid" src="./images/logo/selenoid-logo.PNG"></code>
</p>

`Java` - Autotest programming language \
`Selenide` - a framework on which autotests are written \
`Gradle` - automatic build tool \
`JUnit5` - testing framework \
`Jenkins` - CI/CD to run tests \
`Selenoid` - for launching a browser remotely in `Docker` containers \
`REST Assured` - for testing REST-API services\
`Allure Report` - for building graphical reports \
`Allure TestOps` - as a test management system

[Back to Contents ⬆](#Contents)

# <a name="Launch Options">Launch Options</a>

## <a name="Commands for gradle">Commands for gradle</a>

To run locally and in Jenkins, use the following command:
```bash
gradle clean test
```


## <a name="Run in Jenkins">Run in [Jenkins](https://jenkins.autotests.cloud/job/demo_rest_api_reqres/)</a>


Main page of the project:
<p  align="center">
<img src="images/screens/JenkinsHistory.PNG" width="950">
</p>


_The project build result is available in:_
>- <code><strong>*Allure Report*</strong></code>
>- <code><strong>*Allure TestOps*</strong></code>

# <a>Telegram notifications</a>
The Telegram bot sends a short report to the specified telegram chat based on the results of each build.
<p  align="center">
<img src="images/screens/Telegram.PNG" width="550">
</p>

If you want to use this project to send a report to your telegram chat, you will need to create a configuration file.

File example `config.json`
<p  align="center">
<img src="images/screens/TelegramConfig.PNG" width="550">
</p>


[Back to Contents ⬆](#Contents)

# <a name="Test results in Allure Report">Test results in [Allure Report](https://jenkins.autotests.cloud/job/demo_rest_api_reqres/allure/)</a>

## Home


<p align="center">
  <img src="images/screens/Allure1.PNG" width="950">
</p>

##  Tests

<p align="center">
  <img src="images/screens/Allure2.PNG" width="950">
</p>


##  Graphs

<p align="center">
  <img src="images/screens/Allure3.PNG" width="950">
</p>


[Back to Contents ⬆](#Contents)

# <a>Integration with [Allure TestOps](https://allure.autotests.cloud/launch/29001)</a>


## Allure TestOps Dashboard

<p align="center">
  <img src="images/screens/Testopps1.PNG" width="950">
</p>

## Allure TestOps Test Cases

<p align="center">
  <img src="images/screens/Testopps2.PNG" width="950">
</p>

[Back to Contents ⬆](#Contents)
