

Production and process controls
===============================

Only nightscout-contributors who have an ssh key as authorized by
github have commit access.  Most people are expected to fork, commit
to personal branches, and then submit pull requests in public for
discussion, review, testing, before merging into our mainline
development process.  Our mainline development process is best
described by git-flow, where feature development is done on branches,
development being proposed for next release is shared via dev branch,
and when dev branch is ready for release, a release branch is created
and merged into master.

Unit tests are often run on each commit to each branch at every step
of this process, as well as code reviewed by an increasingly skeptical
and wider audience.

.. note::


   For
   http://www.accessdata.fda.gov/scripts/cdrh/cfdocs/cfcfr/CFRSearch.cfm?CFRPart=820&showFR=1&subpartNode=21:8.0.1.1.12.7
