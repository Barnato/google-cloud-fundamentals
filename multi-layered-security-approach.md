# Multi Layered Security Approach

* Limit access to Google data centers, physical security measures.

* Servers have cryptographic signatures to make sure they are booting the correct software.

* Encryption of PC traffic between data centers.

* Google Central Identity Service - username and password and additional evidence based on things like whether they have logged in from the same device before.

* Secure data at rest - encryption in SSDs and hard drives.

* Google Front End - checks incoming network connections for certificates.

* Source code is stored centrally.

* Google limits what libraries developers use to avoid them introducing bugs.

    ![bounty-bugs](/assets/bounty-bugs.png)

    Taken from [securityweek](https://www.securityweek.com/google-paid-out-87-million-bug-bounty-rewards-2021).

* Google runs a vulnerability rewards program.

