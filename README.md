# Artifact-scanning-for-cloud

This repository assembles and classifies tons of security solutions for artifact scanning, which especially can be adapted in cloud environments. I collect github repositories for **SCA** (Software Composition Analysis), **SBOM** (Software Bills and Materials), **Software Inventory**, also some application testing solutions such as **SAST** (Static Application Security Testing), **DAST** (Dynamic Application Security Testing), and **IAST** (Interactive Application Security Testing)

---
## What is artifact?

According to Gartner, sysdig and a plethora of institutes, artifacts scanning is one of the core components for CNAPP. So what is artifact here? **An artifact** in computing, generally, is a ***visible byproduct during software development***. It describes a software's architecture, design and function. It seems as a roadmap to help people understand the software's development process.

---
## Examples of artifacts
The picture below describes what kind of artifacts exist during software development process (from [TechTarget](https://www.techtarget.com/searchsoftwarequality/definition/artifact-software-development#:~:text=An%20artifact%20is%20a%20byproduct,models%2C%20printed%20documents%20or%20scripts.)). To summarize, artifacts can be

* Diagrams
* Images
* Meeting Notes
* Software documents
* Source code
* Prototypes
* Risk assesements

---
## Artifact Scanning
In cloud computing, artifact scanning is necessary and critical to find vulnerabilities or misconfigurations of our cloud environments through dockerfile, packages, filesystem, software binary, and etc. According to [Sysdig](https://sysdig.com/learn-cloud-native/cloud-security/cloud-native-application-protection-platform-cnapp-fundamentals/), there are two main genres of artifact scanning, which are **SCA (Software Composition Analysis) and Application Security Testing**.

---
## Software Analysis on the System
### SCA (Software Composition Analysis)


### SBOM (Software Bill of Materials)
Generally speaking, SBOM is somewhat different from SCA, and it can be utilized to support SCA's cons while running with them mutually complementary.

1. Syft ([anchore](https://github.com/anchore/syft))
2. Dependency Track ([DependencyTrack](https://github.com/DependencyTrack/dependency-track))

### Software Inventory

---
## Application Security Testing
### SAST (Static Application Security Testing)

### DAST (Dynamic Application Security Testing)

### IAST (Interactive Application Security Testing)
---

## Theoretical Definition

1. Definition of artifact [TechTarget](https://www.techtarget.com/searchsoftwarequality/definition/artifact-software-development#:~:text=An%20artifact%20is%20a%20byproduct,models%2C%20printed%20documents%20or%20scripts.)
2. Definition of artifact [Wikipedia](https://en.wikipedia.org/wiki/Artifact_(software_development))
3. CNAPP overview [Sysdig, What is a CNAPP?](https://sysdig.com/learn-cloud-native/cloud-security/cloud-native-application-protection-platform-cnapp-fundamentals/)