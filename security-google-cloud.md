# Security Google Cloud

* Networking equipment and server boards in Google data centers is designed by Google.

* Hardware security chips in servers.

* Secure boot stack - ensure boot from correct software stack.

* Example: Cryptographic signatures over the BIOS.

* Access to data-centers is limited to a few Google employees.

* Remote Procedure Call traffic is encrypted.

* User Identity Layer - goes beyond username and password, and asks additional info based on log in.

* Storage services - encryption at rest.

* U2F - security compatibility key.

* Stringent software development practices:
    * central source control.
    * two party review of code.

*  U2Fuse - to guard against phishing attacks.

* Bug vulnerability rewards program.

    ![google-data-center.png](assets/google-data-center.png)

    Image taken from [opensistemas > google data center security 6 layers deep](https://opensistemas.com/en/google-data-center-security-6-layers-deep/)