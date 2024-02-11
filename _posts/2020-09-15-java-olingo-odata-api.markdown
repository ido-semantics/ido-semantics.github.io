---
layout: post
title:  Java Olingo OData API Server
date:  2020-09-15 11:05:55 +0900
image:  /assets/images/blog/post-odata.png
image2:  /assets/images/blog/post-odata2.png
author: Ido J.
tags:   MitsubishiDenki Elec.
---

**Our goal was to build an API Server that would be used for a new OpenUI5 microservice. This includes the use of OData, a data format developed by Microsoft. I had the challenge of using Java without any frameworks, so I built the new API Server using only the Olingo library.**

After researching to create a lightweight API server without heavy frameworks, I discovered a library. According to my research, the Olingo library is the optimal choice for providing OData format. To accomplish our task, we began analyzing this library, which was new to us. There were a few errors and trials, but eventually, we succeeded in making it work properly.

> Building a REST API in Java is not difficult if you understand Java lambdas.

After successfully creating a prototype that integrates with OpenUI5, our client was satisfied with the fact that they could create new services without purchasing expensive SAP services. I also compiled and provided information and manuals for all this work, allowing the client's Java team to safely embark on the new project.
