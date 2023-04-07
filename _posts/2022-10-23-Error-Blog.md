---
toc: true
layout: base
categories: [markdown]
title: Project Week 1 Blog
---

Error on Web Domain

![]({{ site.baseurl }}/images/badgatewayerror.png)

Error, non-functional curl

![]({{ site.baseurl }}/images/curlerror.png)

Error

![]({{ site.baseurl }}/images/errorp1.png)

Solution: To solve this error, quite simply, we read the instructions in the error message. In the error message, we noticed that “persistent_volume:/app/volumes” and “/home/ubuntu/SSJN_flask/volumes” were the place where our error sat. Recognizing that these directories were part of the docker compose file, we went back to our docker compose file to investigate. We remembered we’d changed the name of our flask repository on AWS from SSJN_flask to p3t2_ssjn_flask, but this change hadn’t been reflected in the docker compose file. So, we quickly changed the “device” to p3t2_ssjn_flask instead of SSJN_flask. The next time we tried to run the sudo docker/compose up -d command, it worked. However, it first asked us to use the -rm command to start routing our changes to the new file. It only took us 10 minutes to fix this big error! This demonstrates that our whole team truly has a thorough understanding of how AWS deployment works.

Error fixed:

![]({{ site.baseurl }}/images/errorfix.png)

post