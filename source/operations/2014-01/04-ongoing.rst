
Ongoing development
===================

Common problems
---------------

It's always the strings
+++++++++++++++++++++++
A common problem is correctly co-ordinating the database configuration
details between the android uploader and the web app.  The problem is
by far the most common source of use error.  This particular problems
probably dwarfs all the other problems.

Solution: use QR code.
A QR code generator, http://nightscout.github.io/pages/configure/
allows users to type the configuration, verify the syntax, and then
copy and paste the configuration settings into Azure.  This also
allows the android uploader to automatically configure itself by
interpreting a picture of the scanned QR code in the Nightscout app.

This particular feature was discussed on variety of social media,
https://github.com/nightscout/android-uploader/pull/93 and then
integrated through pull request.

Ongoing concerns
----------------

Data privacy and security
+++++++++++++++++++++++++
Most often expressed as feature request:
  
  * User would like to allow school administration access during
    school hours only.


Certain features we are adding require good authentication, and there
are lots of legitimate requests for being able to schedule black out
zones during times of the day.  We've added SSL protection to help
people stay secure, and have implemented alternative transports to
help keep certain credentials safer.  There are a few attempts at
adding authentication, but hesitant to quickly bolt something on and
call it secure.
Support volunteers say this rarely comes up.

How to build a better dosing machine
++++++++++++++++++++++++++++++++++++
A frequent request is for increased, step-wise integration with DIYPs
or similar technologies.

More devices
++++++++++++
Medtronic support.  There is a request for Medtronic support every 2
days.

Accurate reporting
++++++++++++++++++

Adding dialogue to test acceptance/readiness to "donate data."
Need way to submit "events" to FDA, can work on tool to amend/validate
qualified submissions.

