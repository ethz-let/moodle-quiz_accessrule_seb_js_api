# moodle-quiz_accessrule_seb_js_api
Moodle SEB plugin enhanced with JS API

SEB plugin with JS API mentioned in MDL-72188 and cherry picked from https://github.com/catalyst/moodle/tree/MDL-72188-master_seb_js_integration_SITE_STABLE 

Note: As those changes are considered as enhancements, they won't be applied to 3.10, 3.11 and 4.0. But you can always cherry pick those changes to your local branches. The best way is to use the latest code published in the tracker https://tracker.moodle.org/browse/MDL-72188 and then cherry pick the latest commit (s) e.g. git cherry-pick cd7c66d638d92bdc4acd918463bf376917baf105
Please note that changes in 4.0 should not affect the functionality we are changing as part of MDL-72188. So you'd better of to keep your 3.11 as is to check if it works the same way when using JS api in 4.0.
Version.php is updated to support moodle version 3.9 and forward. 
