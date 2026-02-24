# 1 Peppol Specifications Migration Log

## Phase 1 : Version Update ✅

1. Compile target updated to 17
```xml
        <java.version>17</java.version>
        <maven.compiler.source>17</maven.compiler.source>
        <maven.compiler.target>17</maven.compiler.target>
```        

[build log](https://gist.github.com/harsha-amarasiri/a17a3662ebc7dc442f98b9b50caadf41/raw/67391c0da5c75192e8c764dc63eabd25dd260f33/compile-target-verification.log)



## Phase 2 : Dependency Update ✅  

### Dependency Updates [ [Reactor dependency scan log](https://gist.github.com/harsha-amarasiri/a17a3662ebc7dc442f98b9b50caadf41/raw/67391c0da5c75192e8c764dc63eabd25dd260f33/dep-update-scan.log) ]


### [1/6] `peppol-specifications` (Parent)

| Dependency | Old | New |
|---|---|---|
| `com.sun.xml.bind:jaxb-impl` | `4.0.5` | `4.0.6` |
| `jakarta.xml.bind:jakarta.xml.bind-api` | `4.0.2` | `4.0.5` |
| `net.sf.saxon:Saxon-HE` | `12.6` | `12.9` |
| `org.projectlombok:lombok` | `1.18.38` | `1.18.42` |
| `org.testng:testng` | `7.11.0` | `7.12.0` |

| Plugin | Old | New |
|---|---|---|
| `org.apache.maven.scm:maven-scm-api` | `1.13.0` | `2.2.1` |
| `org.apache.maven.scm:maven-scm-provider-gitexe` | `1.13.0` | `2.2.1` |

### [2/6] `peppol-bdx`

| Dependency | Old | New |
|---|---|---|
| `com.sun.xml.bind:jaxb-impl` | `4.0.5` | `4.0.6` |
| `jakarta.xml.bind:jakarta.xml.bind-api` | `4.0.2` | `4.0.5` |
| `net.sf.saxon:Saxon-HE` | `12.6` | `12.9` |
| `org.projectlombok:lombok` | `1.18.38` | `1.18.42` |
| `org.testng:testng` | `7.11.0` | `7.12.0` |

| Plugin | Old | New |
|---|---|---|
| `org.apache.maven.scm:maven-scm-api` | `1.13.0` | `2.2.1` |
| `org.apache.maven.scm:maven-scm-provider-gitexe` | `1.13.0` | `2.2.1` |

### [3/6] `peppol-busdox`

| Dependency | Old | New |
|---|---|---|
| `com.sun.xml.bind:jaxb-impl` | `4.0.5` | `4.0.6` |
| `jakarta.xml.bind:jakarta.xml.bind-api` | `4.0.2` | `4.0.5` |
| `net.sf.saxon:Saxon-HE` | `12.6` | `12.9` |
| `org.projectlombok:lombok` | `1.18.38` | `1.18.42` |
| `org.testng:testng` | `7.11.0` | `7.12.0` |

| Plugin | Old | New |
|---|---|---|
| `org.apache.maven.scm:maven-scm-api` | `1.13.0` | `2.2.1` |
| `org.apache.maven.scm:maven-scm-provider-gitexe` | `1.13.0` | `2.2.1` |

### [4/6] `peppol-sbdh`

| Dependency | Old | New |
|---|---|---|
| `com.sun.xml.bind:jaxb-impl` | `4.0.5` | `4.0.6` |
| `jakarta.xml.bind:jakarta.xml.bind-api` | `4.0.2` | `4.0.5` |
| `net.sf.saxon:Saxon-HE` | `12.6` | `12.9` |
| `org.projectlombok:lombok` | `1.18.38` | `1.18.42` |
| `org.testng:testng` | `7.11.0` | `7.12.0` |

| Plugin | Old | New |
|---|---|---|
| `org.apache.maven.scm:maven-scm-api` | `1.13.0` | `2.2.1` |
| `org.apache.maven.scm:maven-scm-provider-gitexe` | `1.13.0` | `2.2.1` |

### [5/6] `peppol-schematron`

| Dependency | Old | New |
|---|---|---|
| `com.sun.xml.bind:jaxb-impl` | `4.0.5` | `4.0.6` |
| `jakarta.xml.bind:jakarta.xml.bind-api` | `4.0.2` | `4.0.5` |
| `net.sf.saxon:Saxon-HE` | `12.6` | `12.9` |
| `org.projectlombok:lombok` | `1.18.38` | `1.18.42` |
| `org.testng:testng` | `7.11.0` | `7.12.0` |

| Plugin | Old | New |
|---|---|---|
| `org.apache.maven.scm:maven-scm-api` | `1.13.0` | `2.2.1` |
| `org.apache.maven.scm:maven-scm-provider-gitexe` | `1.13.0` | `2.2.1` |

### [6/6] `peppol-ubl21`

| Dependency | Old | New |
|---|---|---|
| `com.sun.xml.bind:jaxb-impl` | `4.0.5` | `4.0.6` |
| `jakarta.xml.bind:jakarta.xml.bind-api` | `4.0.2` | `4.0.5` |
| `net.sf.saxon:Saxon-HE` | `12.6` | `12.9` |
| `org.projectlombok:lombok` | `1.18.38` | `1.18.42` |
| `org.testng:testng` | `7.11.0` | `7.12.0` |

| Plugin | Old | New |
|---|---|---|
| `org.apache.maven.scm:maven-scm-api` | `1.13.0` | `2.2.1` |
| `org.apache.maven.scm:maven-scm-provider-gitexe` | `1.13.0` | `2.2.1` |

[dependency updates build](https://gist.github.com/harsha-amarasiri/a17a3662ebc7dc442f98b9b50caadf41/raw/67391c0da5c75192e8c764dc63eabd25dd260f33/dependency-update-build.log)

---
### Plugin Updates [ [Reactor plugin scan log](https://gist.github.com/harsha-amarasiri/a17a3662ebc7dc442f98b9b50caadf41/raw/67391c0da5c75192e8c764dc63eabd25dd260f33/plugin-scan.log) ]

### [1/6] `peppol-specifications` (Parent)

| Plugin | Current | Available |
|---|---|---|
| `org.codehaus.mojo:properties-maven-plugin` | `1.1.0` | `1.3.0` |
| `maven-compiler-plugin` | `3.10.1` | `3.15.0` |
| `maven-gpg-plugin` | `3.0.1` | `3.2.8` |
| `maven-javadoc-plugin` | `3.4.1` | `3.12.0` |
| `maven-release-plugin` | `2.5.3` | `3.3.1` | 
| `maven-resources-plugin` | `3.3.0` | `3.4.0` | 
| `maven-source-plugin` | `3.2.1` | `3.4.0` | 

### [2/6] `peppol-bdx`

| Plugin | Current | Available | 
|---|---|---|
| `org.jvnet.jaxb:jaxb-maven-plugin` | `4.0.8` | `4.0.12` |
### [3/6] `peppol-busdox`

| Plugin | Current | Available | 
|---|---|---|
| `org.jvnet.jaxb:jaxb-maven-plugin` | `4.0.8` | `4.0.12` | 
| `com.sun.xml.ws:jaxws-maven-plugin` | `4.0.3` | `4.0.3` | 

### [4/6] `peppol-sbdh`

| Plugin | Current | Available | 
|---|---|---|
| `org.jvnet.jaxb:jaxb-maven-plugin` | `4.0.8` | `4.0.12` | 

### [5/6] `peppol-schematron`

| Plugin | Current | Available | 
|---|---|---|
| `org.jvnet.jaxb:jaxb-maven-plugin` | `4.0.8` | `4.0.12` | 

### [6/6] `peppol-ubl21`

| Plugin | Current | Available | 
|---|---|---|
| `org.jvnet.jaxb:jaxb-maven-plugin` | `4.0.8` | `4.0.12` | 



[ plugin updates build ](https://gist.github.com/harsha-amarasiri/a17a3662ebc7dc442f98b9b50caadf41/raw/67391c0da5c75192e8c764dc63eabd25dd260f33/plugin-update-build.log)

## Phase 3 : Deprecated API Cleanup

- [TBD]