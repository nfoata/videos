﻿Videos
======

# Change management: Preparing the technical framework

```
Why, What, How, When/For when, Who, Where
Tools, Method, Technique

In the Line or Transversal ?


,-------------------------,----------------------------------------------------,
|  Why, for what          |             How   ?                                | Used where         By who
,-------------------------,---------------------,------------------------------,
| Management of (product) | Application types   | Application names            |                                  Service
|-------------------------|---------------------|------------------------------|  
|  source versions        |  DCVS               |  Gitolite                    | Development, Conf  Dev, Ops      Transversal 
|  source code            |  Source repository  |  Reprepro                    |                                  Transversal
|  binaries               |  Compilator         |  Javac ...                   | 
|  packaging              |  Package repository |  Reprepro                    | 
|  images                 |  Image repository   |  Docker Registry             |
|  deployment process     |  CI and CD          |  Jenkins                     |
|  quality                |  Unit Tests         |  JUnit / TestNG              |
|                         |  Functional Tests   |  JMeter, Bash                |
|                         |  IHM Tests          |  RobotFramework, Selenium    |
|                         |  Benchmarks         |  JMeter, ApacheBend, Vegeta  |
|  global processes       |  Forge              |                              |
|  security               |                     |                              |
|  source documentation   |                     |  Javadoc                     |
|  archit. documentation  |                     |  UML diagrams                |
|  release documentation  |                     |  Release notes               |
|  product documentation  |                     |  APIs ...                    |
|  help documentation     |                     |                              |
|  training documentation |                     |                              |
'-------------------------'---------------------'------------------------------'

,-------------------------,---------------------,------------------------,
| Management of (project) | Application types   | Application names 
|-------------------------|---------------------|-------------------------
|  planification, Agenda  |                     |  GanttProject 
|  project documentation  |
|  Needs, Requirements    |
|  CBS, WBS               |
|  PSD                    |
|  training documentation |
|  Product backlog        |
'-------------------------'---------------------'------------------------------'

,-------------------------,---------------------,------------------------,
| Management of (trans)   | Application types   | Application names 
|-------------------------|---------------------|-------------------------
|  Best practices         |
|  Knowledge and skills   |
'-------------------------'---------------------'------------------------------'

```


2018/09/12
----------

```
0000   Introduction
0001   Download of Ubuntu                 http://www.youtube.com/watch?v=UI4--Udgzec
0002   Download of Virtualbox             http://www.youtube.com/watch?v=b5Aju9M9-IA
0003   Installation of Virtualbox         http://www.youtube.com/watch?v=ueL31E1XrJ4
0004   Installation of Ubuntu             http://www.youtube.com/watch?v=xX-sl9r0T1Y
0005   Installation of Virtualbox add-ons http://www.youtube.com/watch?v=v8qnAiXlnRk
0006   Installation of Docker-CE          http://www.youtube.com/watch?v=ARFexJ7UvBo
```

2018/09/13
----------

```
0007   Installation of Git                http://www.youtube.com/watch?v=EcmRCGyhdQw
0008   Generation of security keys        http://www.youtube.com/watch?v=NrMGM_s7HFs
0009   Using Github                       http://www.youtube.com/watch?v=6crhj2RBIUo Git/SSHKeys
```

2018/09/14
----------

```
0010   Installation of OpenSSH            http://www.youtube.com/watch?v=wFrUBJFqtIw 
0011   Installation of Gitolite           http://www.youtube.com/watch?v=AucR7Vin7Po Git/OpenSSH/SSHKeys                                  
```


2018/09/15
----------

```
0012   Generation of GPG security keys    http://www.youtube.com/watch?v=oJDyHjQnYeI
0013   Installation of an Apache server   http://www.youtube.com/watch?v=B3QsraBH1-Y
```


2018/09/18
----------

```
0014   Installation of MongoDB on Windows
0015   Installation of MongoDB on Ubuntu
0016   Installation of NodeJS and NPM     http://www.youtube.com/watch?v=2GepD59hPaM
0017   Install test of NodeJS and NPM     http://www.youtube.com/watch?v=rEzos6_PPvQ
0018   Installation of Snap and Juju
0015   Installation of a Forge
```


0014   Installation of Reprepro
0013   Installation of Docker Registry
0014   Installation of Jenkins
0015   Installation of a Forge
https://wiki.debian.org/DebianRepository/SetupWithReprepro
https://docs.docker.com/registry/deploying/
https://askubuntu.com/questions/321589/unable-to-mount-the-cd-dvd-image-on-the-machine-sandbox

# Business As Usual

Installation of a NTP Server
Installation of a DNS
Installation of a Load Balancer
Installation of a Proxy
Installation of a Firewall
