## Profile
### About Me
I am an all around software developer with experiences ranging from mobile front-ends to large scale databases systems and everything else in between.
* * *
### Details

Name: Samarth Jain

Age: 31 years

Location: Seattle, WA, USA
* * *
## Work Experience

- ### Amazon Web Services

  | Position | Duration|
  |:----------|--------:|
  | Software Development Engineer II | Oct 2017 – Present |
  | Software Development Engineer | Apr 2016 – Sep 2017 |
  
  **_Project Experience_:**
  
  - Releases:
    - **Automate database schema migration:** _Fully manual process to automated CR based schema migration for 1000s of host in 25 regions_
    - **Create binary backups for quick db backups and restore:** _Used to use mysqldump which took hours to restore. Moving to binary backups improved performance by a large amount and was only bound by the hosts capability to transport and extract the dump._
    - **Reapers:** _Garbage collection for TB size database. A system of total 13 different state machines that cleanup the database on a cron. Fully configurable to be able to reap N objects in M batches for A accounts and R resources for each of the reapers. One special case reaper GCs live objects that are (in)directly interact-able by the user._
    - **Support for Docker Image Manifest V2 Schema2 and OCI Image Manifest Specification Support:** _Adding support for the new schema types while maintaining support for the original Docker Image Manifest Schema1, with up and down translations._
    - **Performance improvement for per hour billing:** _Improved billing performance by refactoring the code to function at scale using check-pointing and parallelism to gain up to 3-4x times the initial performance. Choosing to optimize the heap size aggressively, so that the host and dataset size are not the bottleneck. Leaving compute as a variable to be tweaked, let jvm run its course and prioritize host compute resources over others for hardware provisioning._ 
    - **Improved data durability for image layers in ECR:** _Added md5 checking for every uploaded part and the whole blob for each layer stored in ECR_ 
    - **Improved database query performance:** _Modified the common libraries to use the newer db apis and explicitly specifying indices (and creating new ones where necessary). Since the workload of the service is order of 10:1 read:write, this improved overall performance significantly_
  - Operational Improvements:
    - **Improved reliability of db instance deployments:** _Automated sanity checks for db instances to validate readiness before activation during deployments._
    - **Migration of all databases worldwide to full utf8 support on all instances**
    - **Logging for all downstream request to aws services to improve debug-ability**
    - **Load test for service:** _Put the service in Gamma under 1.6x times the load that it saw in production in the largest commercial region for a week for testing._
    - **End to end testing for every version of docker:** _Added the ability to test pushing and pulling images to and from every released version of docker for ECR._
    - **Launched ECR in CPT and MXP:** _Reduced wall-clock time and effort needed to release in a region by automating multiple manual and web interactive tasks in to easy to configure command line calls._

- ### Infosys Limited

  | Position | Duration|
  |:----------|--------:|
  | Senior Systems Engineer, Mobility Unit | Oct 2013 – July 2014 |
  | Systems Engineer, Mobility Unit | Aug 2011 – Sep 2013 |
  
   **_Project Experience_:** All projects were developed using Agile SDLC and was involved in all areas from Requirements Elicitation & Requests for Proposals, to Software Architecture Design to final Software Development and Delivery to the customer.
   
  - **Westpac – Credit Card & Loan Application:** _Did a system overhaul of the existing web portal built on Spring framework and moved to mobile friendly technologies, with a RESTful (Java) backend and AngularJS frontend. Designed the complete Software Architecture of the front-end based on a product line model that supports easy branding changes alongside a responsive web design. Affected several performance optimizations and UX enhancements for smooth application flow across all browsers, including backward compatibility to Internet Explorer 6._
  
  - **Goldman Sachs – Make an Impact:** _Built an Android application designed to aid in the campus recruitment conducted by Goldman Sachs across the globe and to create awareness about the various career paths in the company. Designed the complete Mobile Software Architecture that decouples all content (sourced from Goldman Sachs and their portals on Twitter, YouTube, Facebook and LinkedIn) from the UI and can by dynamically updated without requiring an update to the application. Affected several performance optimizations and UX enhancements which impressed the client to ask for similar changes on their iOS application. Received a Bravo Award for Excellence in Feb 2014 for the contributions to this project._
  
  - **C93 – Mobile Virtual Wallet:** _Built concept mobile applications on Android and iOS that provide a complete mobile digital commerce ecosystem solution that includes banking & telephone/online/NFC payment functionalities, complemented with statistical reporting and budget management. Designed the complete Mobile Software Architecture that interfaces with Infosys’ Finacle Digital Commerce (FDC) as the backend. The solution was designed using a product line based architecture, which allows easy changes to branding and quick addition of new services, with several performance optimizations to ensure a viable solution as well as slick interface on both phone and tablet. Being a first of its kind solution in the Australian market, the project has gained immense traction and is being currently developed as a commercial solution for several service providers across many domains. Received a Bravo Award for Excellence in Oct 2013 for the contributions to this project._

* * *
## Education Experience

- ### Carnegie Mellon University, School of Computer Science 

  | Degree | Duration | CGPA |
  |:----------|:--------|:--------|
  |Masters in Software Engineering | Aug 2014 - Dec 2015 | 3.60 |
  
  _**Relevant Courses:** Cloud Computing, Architecture for Software Systems, Introduction to Machine Learning, Management of Software Development, Methods: Deciding What to Design, Analysis of Software Artifacts, Software Development Studio_
 
  **_Project Experience_:**
  
  - **Twitter Analytics Project** – _Built end-to-end infrastructure for extracting analytics information from compressed raw Twitter data larger than 1TB in size. Used Amazon Elastic MapReduce for extracting and transforming data raw data from Amazon S3, which was then stored in MySQL and HBase databases and load tested via multiple web queries of varying complexity via web services built on Undertow and achieved on average throughput of 5,000 PRS and latency of 15 ms. As a result of the performance in the projects in the course was offered a position as Teaching Assistant._
  
  - **Input Text Predictor** – _Built a simple text predictor that analyzes the text from over 6000 books (40GB) of data to build a Bayesian probabilistic model for phrases up to 5 words long. The analytics for the data was done using Amazon Elastic MapReduce with a cost of less than 1USD/hour and the probabilistic model was stored in HDFS using Hive for queries through a web service._
  
  - **Trusted Family’s Data Analytics Portal** – _Built a Data Visualization Framework front-end using EmberJS and an Analytics Engine using Ruby that uses analytics data from Trusted Family’s social platform stored in MongoDB to provide business insights for their account managers and their client’s organizations. Designed the Software System Architecture for the Analytics Engine that allows Trusted Family to modify business rules of the analytics framework on the fly to improve user-facing performance and the ability to modify the analysis pattern in the future. In addition as the Quality Manager and kept the defect density to 11/KSLOC during development with only 1 escaped defect after release._

* * *
## Technical Skills

- ### Languages
  
  | Details | Proficiency |
  |:--------|------------:|
  | Java 1.8+ | Proficient |
  | Python3+ | Proficient |
  | Bash | Proficient |
  | Go 1.5+ | Prior Experience |
  | Ruby 2.2+ | Prior Experience |
  | Objective-C | Prior Experience |

- ### Web Technologies

  | Details | Proficiency |
  |:--------|------------:|
  | JavaScript | Proficient |
  | HTML/HTML5 | Proficient |https://bio.samarthj.com/https://bio.samarthj.com/
  | CSS3 | Proficient |

- ### Databases

  | Details | Proficiency |
  |:--------|------------:|
  | JournalDB | Proficient |
  | MySQL | Proficient |
  | PostgresQL | Proficient |
  | DynamoDB | Prior Experience |
  | HBase | Prior Experience |

* * *
## Contact
email: [dev@samarthj.com](mailto:dev@samarthj.com)
* * *
