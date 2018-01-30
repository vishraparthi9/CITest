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
* There will be a bin folder usually in this path: nexus-3.7.1-02-mac/nexus-3.7.1-02/ considering that nexus-3.7.1 is the version downloaded. So, start nexus using that: **./bin/nexus**

## SSH between Jenkins and Git
* Follow these steps: https://mohitgoyal.co/2017/02/27/configuring-ssh-authentication-between-github-and-jenkins/
