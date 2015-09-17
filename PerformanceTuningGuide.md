A collection of tuning tips to hep you make CommuniGate Pro even more efficient under certain work loads

# Introduction #

This guide is a short list of some of the options that you can tweak on CommunIGate Pro to make it perform better under loads for email or Real-time router operations. As with all "tweaking" the tweaker and the tweaked can vary from place to place, so use this as a guide and when you might have questions, post an email to the CommuniGate Systems community on [LinkedIN](https://www.linkedin.com/groups/CommuniGate-Systems-Unified-Communications-1799159/about) or a mailing list.

First have a look at the product guide and see if you can learn soem of the tips there.

[CommuniGate Pro Tuning](http://www.communigate.com/cgatepro/Scalability.html)


# Details #

Some of the work loads we will discuss include:
  * CommuniGate Pro acting as a email Message Transfer Agent


--- When using the CommuniGate Pro server as a Message Transport Agent for email systems, there are a few things you can look to tweaking that will enhance performance of the server for heavy workloads. Keep in mind that the "workload" a server can experience can radically differ form site to site. Meaning, there can be wide disparity for "average message size" (attachments), and many other factors like filters running on the same server for anti-abuse, and DNS performance.


Some areas to look at are increasing the number of input/output channels the server uses. You can read about these here:

[CommuniGate Pro SMTP Settings](http://www.communigate.com/cgatepro/SMTP.html)


  * CommuniGate Pro acting as a SIP router
  * CommuniGate Pro acting as a frontend in a cluster in a multi-service role with SSL