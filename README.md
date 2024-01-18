# Ashley Hendrickson | Java Engineer

(517)‌ ‌240-3203‌ ‌|‌ ‌ashleygabrielhendrickson@gmail.com‌‌ ‌

## Kohls, Menomonee Falls WI | June 2022 - present

### Spring boot developer

### IFA Inventory Forecast Allocation team

Replacing third party forecasting and inventory application's with much better systems that Kohl's can tailor to its specific needs. When IFA receives a purchase order from a analysis our system takes that purchase order, and sends it through a forecasting system to compute the optimal way to break apart, and allocate that order to stores where it will sell best. Our system can break orders down to the size level and allocate merchandise of size small, to stores with a small size bias for that specific item saving the store alot.

* The project used Spring Boot Micro services with a REST API's that were used to optimize and forecast the sales of purchase orders, given specific configurations and constraints provided by the vendors and the distribution centers. The project also had a batch service that would run daily synchronizing DCsplit, DCstore, and direct to store orders. Our services would receive purchase orders, format and validate them before sending them to a kafka topic which would be consumed by a optimization service which would optimize the purchase orders for the skunet forecasting model. We used Gitlab as the source control and for our CICD pipeline, deploying to open-shift we used a KADO model which is similar to git workflow. I used Dynatrace to debug and monitor deployments and debug issues that occured, as well as gather metrics. 

* I lead the initiative to migrate allocation mechindise hierachy service away from Merchadise Department Manager service which we were retiring. I wrote up a design document went over it with my manager and my pair. I worked with teams consuming from our service and with teams who we consumed from. 

### OLM Order Life cycle Management team

Replacing third party applications that the store depends on. Tracking "buy online pick up in store" BOPUS orders and, buy online ship to store BOSS orders, OLM tracks orders in the store fulfillment center and orders in the store that had to be shipped to another store. We also helped with building out the software associates use in there zebra device to find orders in the store.       

* The project used Spring Boot Micro services with a REST API's that were used track orders from the destribution centers to the store, Orders would be updated as they left the store fulfillment center. I worked on marking orders as lost, updating orders, printing order labeles and sending email order confirmations. We used Gitlab as the source control and for our CICD pipeline, deploying to open-shift we used a KADO model which is similar to git workflow. I used Dynatrace to debug and monitor deployments and debug issues that occured, as well as gather metrics. 

* During our migration I designed a way to compare sterling orders with OLM orders by adding all expected outputs to a json file. The validator service would run once a day which would validating the expeced sterling results our equal to our OLM result. The unexpected results would be saved to a mongo table.    

### Acquired‌ ‌Skills‌ ‌

* 5 solid principles of oop
* cucumber - automated integration test
* dynatrace
* gcp
* jira‌ ‌‌‌ ‌‌ ‌
* kafka, zoo keeper and schema registries
* kubernetes
* mockito - unit test
* nodejs micro services
* openshift ‌
* oracle sql‌‌
* pair programming
* service now
* splunk
* spring batch
* test driven development
* ‌spring boot micro services

------------------

## Ford,‌ ‌Dearborn MI‌ | July‌ ‌2021‌ ‌-‌ ‌May 20‌22 ‌

### Spring boot developer

### Global‌ ‌Ordering‌ ‌and Logistics team ‌

Migrate and maintain legacy systems. The project I worked on was JMC to Mexico, helping to connect dealers in mexico with a chines manufacturing plant JMC. One of the micro services would validate PCVs (Personal Commercial Vehicle), with constrants such as a blue interior trim and blue exterior trim and specific engine before returning a list of PCVs to choose from.  
‌
### Acquired‌ ‌Skills‌ ‌

* jira‌ ‌‌‌ ‌‌ ‌
* openshift ‌
* rabbit mq
* sql‌‌
* ‌spring boot micro services

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

* aws‌ ‌lambda‌ ‌‌‌cdk‌
* material‌ ‌ui,‌ ‌bootstrap,‌ ‌‌material‌ ‌icons,‌ ‌flexbox,‌ ‌grid‌ ‌layout‌‌ ‌
* multi-module‌ ‌maven‌ ‌project‌
* spring boot
* sql ‌
* testing‌ ‌and‌ ‌auto-generating‌ ‌rest‌ ‌api‌ ‌with‌ ‌swagger‌ ‌ ‌
* ‌angular‌ ‌with typescript
* ‌properly‌ ‌maintained‌ ‌angular‌ ‌component‌ ‌state‌ ‌and‌ ‌life‌ ‌cycle‌ ‌hooks.‌‌ ‌
* ‌trello‌‌ task manager‌ ‌tasks‌ ‌for‌ ‌agile‌ ‌development‌ ‌with‌ ‌two-week‌ ‌sprint‌ ‌intervals‌ ‌

--------------------------------

## Education

Grand‌ ‌Valley‌ ‌State‌ ‌University,‌‌ ‌*Allendale‌ ‌MI‌‌ Bachelor‌ ‌of‌ ‌Computer‌ ‌Science‌* |‌ ‌April‌ ‌2020‌

## About Me

I have passion for bitcoin I have implemented a bitcoin wallet using in [rust](https://github.com/Ashleyhen/rust-bitcoin-wallet/tree/dev). I can unlock and lock UTXO using P2TR, P2WPKH and P2PKH I also can connect to the lightning network. 


## links

* linkedin <https://www.linkedin.com/in/ashley-hendrickson-92746b172/>
