moodle-tool_apcu
================

Changes
-------

### Unreleased

* 2021-02-05 - Move Moodle Plugin CI from Travis CI to Github actions

### v3.10-r1

* 2021-01-09 - Prepare compatibility for Moodle 3.10.
* 2021-01-06 - Change in Moodle release support:
               For the time being, this plugin is maintained for the most recent LTS release of Moodle as well as the most recent major release of Moodle.
               Bugfixes are backported to the LTS release. However, new features and improvements are not necessarily backported to the LTS release.
* 2021-01-06 - Improvement: Declare which major stable version of Moodle this plugin supports (see MDL-59562 for details).

### v3.9-r1

* 2020-09-28 - Prepare compatibility for Moodle 3.9.

### v3.8-r1

* 2020-09-28 - Prepare compatibility for Moodle 3.8.

### v3.7-r2

* 2020-09-29 - Remove the APCu GUI file from the plugin codebase as this is a requirement for approval of the plugin on moodle.org/plugins.
               A download and store mechanism was implemented and runs during installation and upgrade of this plugin. If this mechanism fails, the administrator is informed what he has to do to get the plugin up and running (again).
* 2020-09-28 - Remove hardcoded admin directory in paths.

### v3.7-r1

* 2020-05-03 - Initial version
