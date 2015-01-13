

Process description
===================

* https://github.com/nightscout/process-controls

How quickly are changes or problems addressed
---------------------------------------------

In some cases very quickly, in some cases weeks, months, years may be
required to solve a problem.

In the instance where Dexcom released new firmware, we were able to
release a new patch after 3 days.  In other instances, such as adding
other network protocols, or adding devices, it has taken months of
considerable co-ordinated effort.

How is information on updates distributed
-----------------------------------------

* Facebook
* Twitter
* Play store
* ios app store?


How are updates tracked
-----------------------

While development and release tracking all happens on github, updates,
usage analytics, and deployments are tracked in varying ways.

cgm-remote-monitor
++++++++++++++++++
cgm-remote-monitor usage can be polled by analyzing the "distance"
from a fork's master to the original source's master branch.  When the
distance is zero, the branch is up to date.  The
http://nightscout.github.io/pages/update-fork/ tool suggests updates
automatically.  It's also possible to simply delete the forked repo,
and refork the original code base again, which is what support has
historically recommended.

cgm-pebble
++++++++++
Pebble watchfaces are automatically updated by pebble.  On Android
this happens through the play store, and on Apple it happens when
Apple approves updates.

android-uploader
++++++++++++++++
The github releases page
https://github.com/nightscout/android-uploader/releases has a list of
all releases and release candidates.  The releases are signed with our
developer signing key, and also posted through the Google Play store
for updates.

ios-monitor
+++++++++++
Awaiting approval in from Apple.

chrome-uploader
+++++++++++++++
Distributed as Google Chrome app.

