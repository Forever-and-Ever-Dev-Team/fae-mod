---
name: Release Checklist
about: 'GO THROUGH THIS BEFORE RELEASE '
title: 'Release Checklist (build name) '
labels: Needs attention, documentation
assignees: ''

---

### Pre-Release Checklist (Ideally A Week Ahead)
* [ ] 1) Tell Ronald we are releasing soon

* [ ] 2) Make pr stuff (Youtube vids, twitter posts, Reddit posts, discord posts) 

### Release Checklist (Day Of)
* [ ] 1) Verify all Gitlab issues of milestone for build is in "release - no bugs found" state

* [ ] 2) Making a new commit to change do: 
    * [ ] 2a) the version number (1.8.4) - the version name can be changed via options.rpy 

    * [ ] 2b) disabling the dev commands - set dev_access to False via init_run.rpy 

    * [ ] 2c)Build using latest approved version of Renpy (7.3.5 atm ) following the building guide 
* [ ] 3) Play build to ensure it works and was built correctly and all packages are there
    * [ ] 3a) verify that users jumping from the previous version to the new version have no transition issues  

* [ ] 4) List it as a public tag and add the release notes that will be sent to the public and what milestone this public build this was apart of 


* [ ] 5) Add support documents to build folder (bug report, credits, install institutions) 

* [ ] 6) Zip it and upload it to the official g drive  "public builds" folder

* [ ] 7) Get pr ready for the release
    * [ ] 7a) Release notes

    * [ ] 7b) Twitter post

    * [ ] 7c) Reddit post

    * [ ] 7d) Youtube vid if its releasing with hype

    * [ ] 7e) Tell Ronald we are releasing soon and to get ready to make a vid (he makes vids after release in this plan)

* [ ] 8) Verify with all leads the pr messages are good

* [ ] 9) Plan when to release

* [ ] 10) Release

* [ ] 11) Move all "release- no bugs" tickets to "released"

* [ ] 12) Have coders stand by 6 hours to verify release was good with no errors

* [ ] 13) If no errors add all "released " tickets to "done" and close them 

* [ ] 14) Profit
