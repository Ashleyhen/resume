# Ashley Hendrickson | Java Engineer

(517)‌ ‌240-3203‌ ‌|‌ ‌ashleygabrielhendrickson@gmail.com‌‌ ‌

## Kohls, Menomonee Falls WI | June 2022 - February 2024

### Spring boot developer

### IFA Inventory Forecast Allocation team

Replacing third party forecasting and inventory application's with much better systems that Kohl's can tailor to its specific needs. When IFA receives a purchase order from a analysis our system takes that purchase order, and sends it through a forecasting system to compute the optimal way to break apart, and allocate that order to stores where it will sell best. Our system can break orders down to the size level and allocate merchandise of size small, to stores with a small size bias for that specific item saving the store alot.

* Project used Spring Boot Microservices with REST APIs which were used to optimize and 
forecast sales of purchase orders, given specific configurations and constraints provided by the vendors and distribution centers.
* Project also had a batch service that would run daily synchronizing DC Split, DC Store, and direct-to-store orders. Our services would receive purchase orders, format, and validate them before sending them to a Kafka topic which would be consumed by an optimization service which would optimize the purchase orders for the SKU net forecasting model. 
* Used Gitlab as the source control and for our CI/CD pipeline, deployed it to OpenShift we used a 
KADO model which is similar to Git workflow. 
* Utilized Dynatrace to debug and monitor deployments as well as debug issues that occurred and gathered metrics.
* Led the initiative to migrate allocation merchandise hierarchy service away from Merchandise 
Department Manager service which we were retiring. 
* Wrote design document and went over it with manager and pair programming partner. 

### OLM Order Life cycle Management team

Replacing third party applications that the store depends on. Tracking "buy online pick up in store" BOPUS orders and, buy online ship to store BOSS orders, OLM tracks orders in the store fulfillment center and orders in the store that had to be shipped to another store. We also helped with building out the software associates use in there zebra device to find orders in the store.       


* Project used Spring Boot Microservices with REST APIs which were used to track orders from the distribution centers to the store. Orders would be updated as they left the store fulfillment center. 
* I worked on marking orders as lost, updating orders, printing order labels, and sending E-mail order 
confirmations.
* Used Gitlab as the source control and for our CI/CD pipeline, deployed to OpenShift using a KADO model (similar to git workflow). 
* Utilized Dynatrace to debug and monitor deployments and debug issues that occurred. Also used it to gather metrics. 
* During migration, I designed a way to compare sterling orders with OLM orders by adding all expected outputs to a JSON file. The validator service would run once a day which would validate the expected sterling results and equal to our OLM result. The unexpected results would be saved to a Mongo table. 

### Acquired‌ ‌Skills‌ ‌

* Cloud 
    - gcp 
    - openshift
    - kubernetes
    - helm
* Testing
    - cucumber - automated integration test
    - mockito - unit test
    - swagger
* Monitoring
    - dynatrace ‌
    - splunk
* Work Environment
    - pair programming
    - TDD (test driven development)
    - jira‌ ‌‌‌ ‌‌ ‌
    - agile
    - pipeline gitlab
    - production deployment (service now)
* Backend tools
    - kafka, zoo keeper and schema registries
    - nodejs 
    - spring batch
    - ‌spring boot (Java) 
    - micro services
* Databases
    - Oracle SQL (Relational DB)
    - postgresql (Relational DB)
    - Mongo DB (Non Relational DB)


------------------

## Ford,‌ ‌Dearborn MI‌ | July‌ ‌2021‌ ‌-‌ ‌May 20‌22 ‌

### Spring boot developer

### Global‌ ‌Ordering‌ ‌and Logistics team ‌

Migrate and maintain legacy systems. The project I worked on was JMC to Mexico, helping to connect dealers in mexico with a chines manufacturing plant JMC. One of the micro services would validate PCVs (Personal Commercial Vehicle), with constrants such as a blue interior trim and blue exterior trim and specific engine before returning a list of PCVs to choose from.  
‌
### Acquired‌ ‌Skills‌ ‌


* Cloud 
    - pivotal cloud foundry 
* Monitoring
    - splunk
* Work Environment
    - TDD (test driven development)
    - agile
    - git workflow
    - pipeline gitlab
* Backend tools
    - RabbitMQ
    - ‌spring boot (Java) 
    - micro services
    - rabbit mq
* Databases
    - Oracle SQL (Relational DB)


------------------

## Initech‌ ‌global‌ ‌,‌ ‌Grand‌ ‌Rapids,‌ ‌MI‌ | ‌ May‌ ‌2019‌ ‌-‌ ‌April‌ ‌2021‌‌ ‌

### Full stack developer

### APES‌‌ ‌

Apes‌ ‌was‌ ‌my‌ ‌first‌ ‌client‌ ‌project‌ ‌made for Amway, this project was a intenral application ‌for ‌‌monitor‌ ‌and‌ ‌add‌‌ financial‌ ‌documentation.‌ ‌I‌ ‌helped‌ ‌migrate‌ ‌from‌ ‌the‌ ‌old‌ ‌application‌ ‌that‌ ‌used a j2ee framework ‌to‌‌ a ‌Angular‌ ‌front‌ ‌end‌ ‌and‌ ‌a‌ spring boot back‌end with multi‌ ‌modularized‌ ‌maven‌ ‌application‌ to help scale and maintain the application. I‌‌ also‌ ‌integrated‌ ‌a‌ ‌few‌ ‌AWS‌ ‌internal‌ ‌lambdas‌ ‌for‌ ‌some‌ ‌of‌ ‌the‌ ‌batch‌ ‌processes using AWS cdk.‌‌ ‌

### MyInitech‌‌ ‌

MyInitech‌ ‌was‌ ‌my‌ ‌first‌ ‌non-intern‌ ‌internal‌ ‌project,‌ ‌it‌ ‌was‌ ‌a all purpose tool used‌ ‌by‌ ‌the‌ ‌company‌ ‌to‌ ‌monitor‌ ‌and‌ ‌organize‌‌ internal‌ ‌projects,‌ ‌staff,‌ ‌timesheets,‌ ‌vacation‌ ‌days,‌ ‌project‌ ‌documents,‌ ‌and‌ ‌more.‌ ‌ The‌ ‌old‌ ‌application‌ ‌used ‌plain‌ ‌javascript‌ ‌and‌ ‌was‌ ‌hosted‌ ‌with‌ ‌JSP.‌ ‌I‌ ‌helped‌ ‌migrate‌ ‌the‌ ‌front‌ ‌end‌ ‌to‌ ‌a‌ ‌new‌ ‌Angular‌‌ front end. ‌I‌ ‌also‌ ‌fixed‌ ‌existing‌ ‌bugs‌ ‌on‌ ‌the‌ ‌older‌ ‌monolithic‌ ‌spring‌ ‌boot‌ ‌backend.‌‌ ‌

### HOA‌‌ ‌

HOA‌ ‌was‌ ‌my‌ ‌first‌ ‌project‌ ‌as‌ a ‌intern,‌ ‌this application was ‌a‌ ‌HomeOwners‌ ‌Association‌ ‌application‌ ‌that‌ ‌could‌ ‌be‌‌ used‌ ‌by‌ ‌the‌ ‌landlord‌ ‌to‌ ‌keep‌ ‌track‌ ‌of‌ ‌tenants‌ ‌whether‌ ‌they‌ ‌paid‌ ‌or‌ ‌not‌, if‌ ‌they‌ ‌had‌ ‌complaints‌,‌ ‌and what‌‌ properties‌ ‌are‌ ‌being‌ ‌occupied‌ ‌as‌ ‌well‌ ‌as‌ ‌damages.‌ ‌I‌ ‌used‌ ‌Angular‌ ‌to‌ ‌help‌ ‌develop‌ ‌the‌ ‌front‌ ‌end‌ ‌and‌ ‌spring‌‌ for the backend.

### Acquired‌ ‌Skills‌ ‌

* Cloud
    - aws‌ ‌lambda‌ ‌‌‌cdk‌
    - sqs
* front end
    - material‌ ‌ui,‌ material‌ ‌icons,‌‌ ‌
    - bootstrap,‌ flexbox,‌ ‌grid‌ ‌layout‌‌ ‌
    - Angular Typescript
* back end
    - multi-module‌ ‌maven‌ ‌project‌
    - spring boot (Java) 
    - testing‌ ‌and‌ ‌auto-generating‌ ‌rest‌ ‌api‌ ‌with‌ ‌swagger‌ ‌ ‌
* Work Environment
    - TDD (test driven development)
    - agile
    - git workflow
    - pipeline gitlab
    - ‌trello‌‌ task manager‌ ‌ ‌ ‌
    - agile‌ ‌development‌ ‌‌ ‌
* Database
    - postgresql ‌

--------------------------------

## Education

Grand‌ ‌Valley‌ ‌State‌ ‌University,‌‌ ‌*Allendale‌ ‌MI‌‌ Bachelor‌ ‌of‌ ‌Computer‌ ‌Science‌* |‌ ‌April‌ ‌2020‌

## About Me

I have passion for bitcoin I have implemented a bitcoin wallet using in [rust](https://github.com/Ashleyhen/rust-bitcoin-wallet/tree/dev). I can unlock and lock UTXO using P2TR, P2WPKH and P2PKH I also can connect to the lightning network. 


## links

* linkedin <https://www.linkedin.com/in/ashley-hendrickson-92746b172/>
