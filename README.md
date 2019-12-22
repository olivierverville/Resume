# Resume

Hi, my name is Olivier Verville, and this repository is used as my online resume. As far back as I can remember, I've always had interest for computers; as soon as I was introduced to them, I loved it, and it's been a big part of my life since then. My interest for programming came a few years later. Even though programming is my area of expertise, I love pretty much everything IT-related. Whenever I find the occasion to, I'll mess around and undertake minor projects in areas such as networking, hardware, IoT, GFX editing, etc.

Nowadays I consider myself a Full Stack Developer as I've had experience in so many different IT contexts and areas, such as programming, networking, database management, test automation, reverse engineering, and the list goes on.

- [LinkedIn](https://www.linkedin.com/in/olivier-verville/)
- [Stack Overflow](https://stackoverflow.com/users/8332700/verv)
- [GitHub](https://github.com/olivierverville)

**Completed Projects**
- [Professional Projects](#professional-projects)
- [Personal Projects](#personal-projects)
- [Contributions to Open Source Projects](#contributions-to-open-source-projects)

**Programming Languages I've worked with**  
`C` , `C++` , `Java` , `Python` , `JavaScript` , `TypeScript` , `PHP` , `x86 Assembly` , `Groovy` , `VBA`

**Programming Languages I'd like to work with**  
`Rust` , `C#` , `Ruby` , `Kotlin` , `GO`

**CI/CD Software I've worked with**  
`Gitlab CI` , `Jetbrains TeamCity` , `Jenkins`

---

Professional Projects
---

**April 2019 - December 2019**

**Title**: Developer/Architect  
**Employer**: Askida  
**For**: Telecommunication Company

**Project**: Architecturing, development and maintenance of microservice oriented applications to manage and interact with the network infrastructure of various external clients. Including but not limited to: one touch provisioning of network equipments, management of SSL certificates, management of virtual servers, etc. The microservices were deployed on a OpenShift cluster. The project also involved establishing a development practice in a less experienced development team, building CI/CD pipelines, and more.

**Tags**: `Python` , `Flask` , `OpenShift`, `Network Infrastructure`

---

**February 2019 - March 2019**

**Title**: Developer  
**Employer**: Askida  
**For**: Telecommunication Company

**Project**: Maintenance and scaling of a java application with an electron-based frontend. The application collects data from various public API's and generates a report from this data. The frontend is used to enrich and in some cases rectify the generated report.

**Tags**: `Java` , `Spring` , `Javascript` , `Electron` , `REST API` , `FreeMarker` , `SQLite`

---

**September 2018 - February 2019**

**Title**: Developer  
**Employer**: Askida  
**For**: Telecommunication Company

**Project**: Development of a set of REST API that provides diagnosis and troubleshooting data for an IoT platform, using a micro service oriented architecture. Each API consisted of a set of Docker containers deployed as pods in a Kubernetes cluster.

**Tags**: `Java` , `Spring` , `Google Guice` , `Undertow` , `Micro Service` , `REST API` , `Kubernetes` , `PaaS`

---

**September 2018**

**Title**: Developer  
**Employer**: Askida  
**For**: Askida

**Project**: Development of a small internal application based off [Spring's PetClinic](https://github.com/spring-projects/spring-petclinic) to be used as a sample test application for the [Askida CT](https://askidact.com/en/) product. Project mostly consisted in expanding PetClinic's functionalities so that a more vast array of automated tests could be scripted and executed against it. 

**Tags**: `Java` , `Spring` , `Thymeleaf` , `MVC` , `Paypal API`

---

**April 2018 - August 2018**

**Title**: Developer  
**Employer**: Askida  
**For**: Public Service Organization

**Project**: Development of an automated research platform, aiming to automate a time consuming manual research procedure. The platform included a qualification stage, which determined whether a research request could be automated or not (based on a precise set of criterias in the request), and the treatment/research process. Built on top of Logstash and Elasticsearch.

The data was synchronized from an Oracle SQL database, via Logstash.

**Tags**: `Java` , `Spring` , `JUnit` , `Logstash` , `ElasticSearch` , `Kibana` , `Oracle` , `SQL`

---

**March 2018**

**Title**: Automation Engineer  
**Employer**: Askida  
**For**: Health IT Company

**Project**: Scripting of API tests over a FHIR API through a reverse proxy, and validation of recorded data by the reverse proxy through requests to a local REST API. Solution was entirely scripted using Robot Framework & Python.

**Tags**: `Python 2` , `Robot Framework` , `FHIR` , `REST API` , `XML`

---

**October 2017 — March 2018**

**Title**: Developer & Automation Engineer  
**Employer**: Askida  
**For**: Banking Company

**Project**: Conversion of a legacy app that automated an internal banking app (like a bot) from VBA, to a Python webservice. The internal banking app was converted into a web app from a previous project, and so their VBA automation app broke. It was converted into a local webservice (written in Python). The webservice uses selenium & chromedriver to reproduce the automation that was done in the legacy VBA app. The webservice exposed a simple REST API, and the legacy VBA code was patched to make requests to this API.

In parallel I was also responsible for setting up the architecture behind our internal automated tests (API tests) and setting up the whole thing on Jenkins (build app, launch webservice, start tests, etc.). The actual test cases and scripts weren't written by me.

**Tags**: `Python 3` , `Selenium` , `ChromeDriver` , `WebService` , `REST API` , `VBA` , `MS Access` , `Jenkins`

---

**October 2017 — December 2017**

**Title**: CI Automation Engineer  
**Employer**: Askida  
**For**: Development Company

**Project**: Automation of a complex build procedure on a PowerBuilder application. The procedure was previously done manually on a weekly basis and was time consuming (~3 hours, given the procedure was executed by someone used to it)

**Tags**: `CI/CD` , `PowerBuilder` , `PowerGen` , `TeamCity` , `Python 3`

---

**June 2017 — August 2017**

**Title**: Automation Engineer & QA analyst  
**Employer**: Askida  
**For**: Security Company

**Project**: Design and development of a BDD-oriented automated test architecture for an internal application. The test architecture was built on top of the Python framework Behave (Cucumber clone). I also was responsible for the writing and scripting of basic test scenarios. The solution was targeted for API tests on a SOAP API.

**Tags**: `Python 2` , `BDD` , `Behave` ,  `SOAP API`

---

**April 2016 — May 2017**

**Title**: QA Analyst & Developer  
**Employer**: Askida  
**For**: Banking Company

**Project**: Conversion of an internal banking app (written in MicroFocus COBOL, in 1983), to a Java web application. The backend was written in Java and used an Oracle database, and the frontend was entirely written in TypeScript. I worked the first 6 months on the project as a QA analyst, building up the test architecture, the setup on Jenkins, and developing an internal testing library for Robot Framework, which was the framework used for the scripting of the test cases (keyword driven approach). I spent the rest of the project as a developer, developing utility tools for the COBOL to Java conversion, creation of transaction stubs, and a few other things that saved hundreds of hours of work. Also participated to the actual development of the application.

**Tags**: `Java` , `TypeScript` , `Robot Framework` , `Python 2` , `Jenkins` , `Oracle` , `SQL` , `COBOL`

---

Personal Projects
---

**Median XL**

**Started**: June 2013  
**Finished**: Still evolving  
**Title**: Lead Developer  

**Project**: Reverse engineering and expansion of [Diablo II](http://us.blizzard.com/en-us/games/d2/)'s game engine. The game's engine was almost entirely rewritten by reversing and translating the binaries' assembly code back to source C code. The project consists of about 100,000 lines of source code that was translated from raw assembly code. Bugs from the original game's engine have been fixed, and it was ultimately expanded in a modding platform for my team.

**Tags**: `C` , `C++` , `MSVC` , `x86 Assembly` , `Source Code Injection` , `Reverse Engineering` , `OllyDBG`

---

**PVPGN**

**Started**: May 2017  
**Finished**: Still evolving  
**Title**: Developer  

**Project**: Development on a private fork of [PVPGN](https://github.com/pvpgn/pvpgn-server), adding and/or expanding functionalities for the server that hosts the Median XL project. These patches weren't contributed to the main public project because they were very specific changes to integrate with Median XL and would be of no interest for general usage.

**Tags**: `C++` , `gcc`

---

Contributions to Open Source Projects
---

**Robot Framework**

**Project**: https://github.com/robotframework  
Contributions to [Selenium2Library](https://github.com/robotframework/Selenium2Library), which became [SeleniumLibrary](https://github.com/robotframework/SeleniumLibrary) and development of utility libraries and tools for the framework.

**Tags**: `Python` , `Robot Framework`
