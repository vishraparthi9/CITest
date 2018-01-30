# CITest

## Install Jenkins

* Download war from here: https://updates.jenkins-ci.org/download/war/
* Run the jar from command line: java -jar <jenkins.war>
* Run *http://localhost:8080/* in browser. Enter the admin password as specified when you run the above command
* Choose **Install suggested plugins**
* Enter random credentials for **Create First Admin User**
* Click **Save & Finish**
* In the next page, click **Start using Jenkins**
* The actual Jenkins home page is displayed at this point

## Setup Local Nexus Repository

* Download and unzip latest Nexus OSS from here: https://www.sonatype.com/download-oss-sonatype
* There should be a bin folder which has nexus start up script. So, start nexus using that: ./bin/nexus
