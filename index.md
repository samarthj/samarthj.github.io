# PROFILE

## SUMMARY
I am a language and technology agnostic software/ systems engineer. In any situation, I always want to have something to offer my team and something which I can learn from them. The hunger for learning more and newer things is the highest priority that motivates me. To that end, I have experience from surface-level UI Designs down to managing the memory of individual execution units, in both the context of an application working on a handheld device or a large distributed system serving hundreds of thousands of users.

I am good at working on hard/new problems. I thrive in an environment where there are unknown unknowns or known unknowns, and trying to get a handle on them and finding a solution drives and motivates me a lot in my work.

I like to expand my knowledge as much as I can. The affinity to solving hard and new problems helps me with that. But I also desire to dive deep into a system and get as many details about it as possible. That helps me with quick decision-making and my debugging process. And it also helps me support my colleagues by assisting with their issues or at least pointing them in the right direction.


* * *
## SKILLS
Software Architecture • Cloud Computing • Linux System Administration • Mobile Applications • Web Applications • Database Administration • Distributed Systems • Shell Scripting • Java • Python • Ruby • Go • Rust (learning) • CMake (incidental)

* * *
## EXPERIENCE
### Amazon Web Services, Seattle
Team:  AWS Elastic Container Registry

| Position                         |            Duration |
| :------------------------------- | ------------------: |
| Software Development Engineer II |  OCT 2017 – Present |
| Software Development Engineer    | APR 2016 – SEP 2017 |


Key Responsibilities involved Software Development, Database Software & Administration, and Backend System Administration. With a particular focus on performance, maintenance, and availability improvements. 

Key accomplishments:

1. Garbage collection. I was the sole developer who built the entire code-base for reaping tombstoned data. The incremental retrieval and batched update paradigms that I developed became callable interfaces for future read and write performance improvements. (Java, MySQL, AWS S3)

2. Fast backup restores. Independently built a solution to snapshot and restore the database at a terabyte-scale in hours vs. days. (MySQL, Alfbus, Shell)

3. Automated schema migrations. Independently scripted automation for both views so that automated migrations and rollbacks can be accomplished using code-reviewed code pushed through monitored deployments, with little to no human intervention. This was key for feature rollout, with the service hosted in 20+ AWS regions spanning several hundreds of hosts. (Shell, MySQL, Linux)

4. Consistently kept the codebase on the bleeding edge of upstream development. It resulted in several gains in read performance over time. In particular, as the sole developer, eliminated all unbounded and unindexed reads, resulting in O(1) read performance for several APIs. Since the workload of the service is on the order of 10:1 read:write, this improved overall performance significantly. (Alfbus, MySQL, Java)

5. Improved runtime of billing data processing, purely in software, independently. The techniques used included checkpointing, parallel-processing, sustained heap size reduction, JVM optimization, reference duplication, and last but not least, O(n^2) to O(n) reduction in runtime. Responsible for halving runtime on two separate occasions. (Java, MySQL, AWS S3)

6. Automated system device raid configuration / re-bootstrapping. Due to transitioning hardware configurations and varying availability of hardware in different regions and availability zones, the state in which the disks were provisioned on a host was unpredictable. Independently worked on eliminating the need to run commands on hosts manually. Most of the future issues could be fixed by simply reprovisioning the host or rebooting. (Linux, Shell)

7. Amazon ECR supports Docker Image Manifest V2, Schema 2 - Worked on delivering this feature in partnership with one other engineer and a product manager.

8. Other Feature work - also involved in team consensus building for the functional design of how Lifecycle policy rules do the decision-making and evaluation. I spent ~20% of my time independently working on day-to-day operationally focussed improvements, targeted at removing manual work and improving runtimes. Independently worked on creating and reviewing the backbone design for KMS Encryption. Providing support for image scanning capabilities on ECR images for a different team within AWS - Sagemaker.

9. Other Operational improvements have I done independently - Automated sanity checks for DB instances to validate readiness before activation during deployments. Migration of all databases worldwide to full utf8 support on all instances for protection against unvalidated input. Logging for all downstream requests to AWS services to improve debug-ability. Put the service in the Gamma under 1.6x times the load it saw in production in the largest commercial region for a week for testing, surfacing unknown issues, and fixing them. Added the ability to test pushing and pulling images to and from every released version of docker for ECR. Launched ECR in CPT and MXP - reducing wall-clock time and effort needed to release the service in a region from a month to 10-15 days. Improved data durability for image layers in ECR by adding hash validation for every uploaded part and the whole blob for each object stored in ECR.



### Carnegie Mellon University, Pittsburgh

| Position                                      |            Duration |
| :-------------------------------------------- | ------------------: |
| Graduate Teaching Assistant - Cloud Computing | AUG 2015 - DEC 2015 |

I was involved in project creation, conducting lectures, and holding office hours. The teaching assistants primarily facilitated the entire course under the guidance of the faculty. I directly prepared the course content incorporating Data Centers, Durability, Availability, Fault Tolerance, MapReduce, and Apache Spark.


### Infosys Ltd., Pune, India

| Position                               |            Duration |
| :------------------------------------- | ------------------: |
| Senior Systems Engineer, Mobility Unit | OCT 2013 – JUL 2014 |
| Systems Engineer, Mobility Unit        | AUG 2011 – SEP 2013 |

Enterprise Mobile Application Development across all platforms - native (Android, iOS), cross-platform/hybrid (PhoneGap, Titanium), pure web-based (HTML5, CSS3, jQuery, jQuery mobile, Sencha Touch, AngularJS).

Projects:

1. **Westpac** – Credit Card & Loan Application: Did a system overhaul of the existing web portal built on Spring framework and moved to mobile-friendly technologies, with a RESTful (Java) backend and AngularJS frontend. I designed the complete Software Architecture of the front-end based on a product line model that supports easy branding changes alongside a responsive web design. I also performed several performance optimizations and UX enhancements for smooth application flow across all browsers, including backward compatibility to Internet Explorer 6.

2. **Goldman Sachs** – Make an Impact: Built an Android application designed to aid in the campus recruitment conducted by Goldman Sachs across the globe and create awareness about the various career paths in the company. I designed the complete Mobile Software Architecture that decouples all content (sourced from Goldman Sachs and their portals on Twitter, YouTube, Facebook, and LinkedIn) from the UI and can be dynamically updated without requiring an update to the application. I also performed several performance optimizations and UX enhancements which impressed the client to ask for similar changes on their iOS application. I received a Bravo Award for Excellence in Feb 2014 for my contributions to this project.

3. **C93** – Mobile Virtual Wallet: Built concept mobile applications on Android and iOS that provide a complete mobile digital commerce ecosystem solution that includes banking & telephone/online/NFC payment functionalities, complemented with statistical reporting and budget management. Designed the entire Mobile Software Architecture that interfaces with Infosys’ Finacle Digital Commerce (FDC) as the backend. The solution used a product-line architecture, allowing easy changes to branding and quick addition of new services, with several performance optimizations to ensure a viable solution and a slick interface on both phone and tablet. A first-of-its-kind solution in the Australian market, it gained immense traction. It was in development as a commercial solution for several service providers across many domains when I left. I received a Bravo Award for Excellence in Oct 2013 for my contributions to this project.

### Frost & Sullivan, Chennai, India

| Position                                        |            Duration |
| :---------------------------------------------- | ------------------: |
| Intern, Industrial Automation & Process Control | JUL 2010 - DEC 2010 |

Primary responsibilities involved doing market research on the domain with interviews with primary sources and secondary research, preparing reports on specialized areas, e.g., Green innovations in the energy sector, Automation improvements, and roadmaps in the aviation industry with a case study on Boeing, and others. As well as giving presentations on established reports.

* * *
## EDUCATION

### Carnegie Mellon University, School of Computer Science

| Degree                          | Duration            | CGPA |
| :------------------------------ | :------------------ | :--- |
| Masters in Software Engineering | AUG 2014 - DEC 2015 | 3.60 |

Relevant Courses: Cloud Computing, Architecture for Software Systems, Introduction to Machine Learning, Management of Software Development, Methods: Deciding What to Design, Analysis of Software Artifacts, Software Development Studio

Projects:

1. **Twitter Analytics Project** – Built end-to-end infrastructure for extracting analytics information from compressed raw Twitter data larger than 1TB in size. AWS Elastic MapReduce was used to extract and transform raw data from Amazon S3 and stored in MySQL and HBase databases. It was load tested via multiple web queries of varying complexity via web services built on Undertow and achieved on average throughput of 5,000 PRS and latency of 15 ms. As a result of the performance in the projects in the course was offered a position as Teaching Assistant.

2. **Input Text Predictor** – Built a simple text predictor that analyzes the text from over 6000 books (40GB) of data to build a Bayesian probabilistic model for phrases up to 5 words long. The analytics for the data was done using Amazon Elastic MapReduce with a cost of less than 1USD/hour, and the probabilistic model was stored in HDFS using Hive for queries through a web service.

3. **Trusted Family’s Data Analytics Portal** – Built a Data Visualization Framework front-end using EmberJS and an Analytics Engine using Ruby that uses analytics data from Trusted Family’s social platform stored in MongoDB to provide business insights for their account managers and their client’s organizations. Designed the Software System Architecture for the Analytics Engine that allows Trusted Family to modify business rules of the analytics framework on the fly to improve user-facing performance and alter the analysis pattern in the future. In addition, as the Quality Manager kept the defect density to 11/KSLOC during development, with only 1 escaped defect after release.

### Birla Institute of Technology and Science, Goa, India

| Degree                             | Duration            | CGPA |
| :--------------------------------- | :------------------ | :--- |
| BE Electronics and Instrumentation | AUG 2007 - MAY 2011 | 6.03 |

Relevant Courses: Digital Electronics & Computational Organization, Microprocessors

* * *
## PERSONAL PROJECTS

### Arch User Repository
I am Currently maintaining 10+ projects and growing. Most notably, the entire git repo stack of RedHat’s Podman, Buildah, Crun ecosystem. Earlier, I also maintained 1password dev builds as well. Which was later transferred over to the owners of the software. [https://github.com/samarthj/AUR](https://github.com/samarthj/AUR)

### Open-source contributions

1. Upstream implementation of support for secrets management for podman-compose. [https://github.com/containers/podman-compose/pull/320](https://github.com/containers/podman-compose/pull/320)

2. Github Action for automated archlinux containerized builds and releases to AUR / asset releases to anywhere. [https://github.com/marketplace/actions/archlinux-pkgbuild](https://github.com/marketplace/actions/archlinux-pkgbuild)

3. A MariaDB builder for building a container img written using buildah. In particular there exists no scripted solution either for building mariadb standalone or as a docker image that allows customization of features during compile time. Except digging through the documentation and figuring it out oneself. This is my attempt at providing such a solution. [https://github.com/samarthj/mariadb-builder](https://github.com/samarthj/mariadb-builder)

4. A helper library for common python actions. I extracted this from several personal projects and converted it to a library to use and share. At the moment it contains helpers for logging, sleeps that use normal distribution instead of a single value and a retry decorator generic enough to allow for multiple different retry strategies with a single decorator over multiple exceptions, wait times and exit criteria. [https://github.com/samarthj/pylib-helpers](https://github.com/samarthj/pylib-helpers)

* * *
## CONTACT
email: [contact@SAMARTHJ.com](mailto:contact@samarthj.com)
* * *
