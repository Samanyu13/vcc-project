# VCC Course Project  
## Virtualization and Cloud Computing (CSL7510)
---

## Team Members
### Garvit Chugh (M20CS018)
### Samanyu A Saji (M20CS013)
---

## Instructor: Dr. Sumit Kalra (Assistant Professor, Department of Computer Science & Engineering, Indian Institute of Technology, Jodhpur)
---

## Overview


The major goal of our project is to inspect, construct and evaluate the execution of the two types of job - Map Reduce, and Webservice - on a large simulation infrastructure. We will be dealing with multiple, with each of these having multiple hosts as well. Additionally, we will be making use of different VM allocation policies and load balancing algorithms, in order to manage the heavy work being assigned. 


## Running the Project

### Prerequisites
- SBT should be installed. You can download it from [here](https://www.scala-sbt.org/)


### Docker Image

Click [here](https://hub.docker.com/r/garvitchugh/vcc_project) to download the docker image.

### Run it Locally ((Applicable for Linux/Mac))
For running it locally, 
- Clone our repo

```
git clone https://github.com/Samanyu13/vcc-project
```
- Change directory to the project folder.
- Now, build and generate the  jar file using sbt as follows.
```
sbt clean compile run
```

## Project Report
The detailed report of our project can be found [here](https://docs.google.com/document/d/1uVkqR_UgqZvxqQVxEg4Huh_bBOcA-ILCdEziEgtwXh8/edit?usp=sharing).