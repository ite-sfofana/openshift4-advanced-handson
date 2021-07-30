# advanced-handson-ocp4

## 2. Build Process
The Red Hat OpenShift Container Platform build process transforms either source code or binaries and other input parameters into container images that become available for deployment on the platform. To build a container image, OpenShift requires a BuildConfig resource. The configuration for this resource includes one build strategy and one or more input sources such as git, binary or inline definitions.

### 2.1 Build Strategies
Each strategy requires a container image.
The following are the available build strategies in OpenShift: 
#### 2.1.1 Source
#### 2.1.2 Pipeline
#### 2.1.3 Docker
#### 2.1.4 Custom

## Setup a simple pipeline 

[Simple a CICD-Pipeline](simple-pipeline/setupCICD.adoc)
