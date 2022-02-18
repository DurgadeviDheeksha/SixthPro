What is "bug leakage?" and What is "bug release?"
Bug leakage and bug release are two different terminologies. The whole QA process workaround these two terms. We can differentiate between them as follows:

Bug leakage: Bug leakage is something, when the bug is discovered by the end users or customer, and missed by the testing team to detect, while testing the software.
OR
A defect which exists in the application and not found by the tester which is eventually found by the customer/end-user.

Bug release: A bug release is when a particular version of software is released with a set of known bug(s)/defect(s). These bugs are usually of low severity/priority. It is done when a software company can afford the existence of bug in the released software rather than the time/cost for fixing it in that particular version.

It is the core responsibility of Software testing company to find the bugs at the earlier stage so that a good product can be handed over to the client.

Hope this information is useful to you and you can get back to us in case need more information.
A bug leakage results when a bug is detected which should have been detected in earlier builds/versions of the application.

A defect which exists during testing yet unfound by the tester which is eventually found by the tester/end-user is also called bug leakage.

A bug release is when a particular version of s/w is released with a set of known bug(s)/defect(s). These bugs are usually 
low severity and/or low priority bugs. It is done when the company can afford the existence of bug in the released s/w rather than 
the time/cost for fixing it in that particular version. 
These bugs are usually mentioned in the Release Notes.

How do you prevent the bug leakage?
Bug Leakage is defined as:

Software bugs/defects that are discovered in the current phase of product that was supposed to be found in an earlier phase of the product.

An example of this would be a customer reports seeing an issue on your product in a production environment after your team tests and deploys it from a staging/testing environment.

Although there are a wide variety of fixes for bug/defect leakage, I would start by looking into your companies current approach to testing. Here are some common issues I have seen while working in my career.

Lack of product knowledge. (Alleviate this issue with training your testers on the products that they are testing)
Process review for test cases. (Ensure that test case reviews are happening. Meaning that another person who didn't create the test cases
 reviews them, and ensures they are of good quality)
Quality of testing data in your staging/testing environment. (Always strive to have an environment where you have comparable data to a 
production environment, work with team-members of your company to gain access to what you need)
Tests are limited to "Happy Path" testing. (Review your test cases to ensure there are some "Edge Case" scenarios that are covered in 
testing. Another option that has been extremely helpful in the past for me is by adding a few hours of exploratory/ad-hoc testing to a 
release cycle)
Some testers might just be "Checking" the requirements and not "Testing" them. (Reach out to your testers and make sure they know you
 are not just looking for a spot check of requirements, make sure they are digging deeper into the tests to expose flaws. Test cases are 
a good 
blue print for the tester, but they miss a lot of details that should be implied with quailty QA testing)