---
name: Forms Regression Test
about: Use this template to set up a regression test for a Form

---

**Describe the bug**
<!--- here we list out the expected functionality as a checklist --->

Here are them features to test:
- [ ] /introduction
  - [ ] Do the accordion buttons work?
- [ ] /what-happened
  - [ ] Are "Required" fields required? (Can you not proceed until you've filled out an answer?)
  - [ ] DatePicker
    - [ ] Can you enter a date?
    - [ ] Does it autocorrect if you try to enter a future date?
    - [ ] Does it autocorrect if you try to enter a date that doesn't exist (like February 31st)?
    - [ ] Is the date entered reflected in the calendar?
    - [ ] Is the date selected in the calendar reflected in the input boxes?
  - [ ] TimePicker
    - [ ] Can you enter a time?
    - [ ] Are you prevented from entering a fake time?
  - [ ] Received a Ticket
    - [ ] Enter the name of your device+Browser as the name of ticket. That way we can trace the email response back to you if there was a problem.
- [ ] /where-happened
  - [ ] Are "Required" fields required? (Can you not proceed until you've filled out an answer?)
  - [ ] LocationPicker
    - [ ] Can you set a location by entering the "Four Seasons"?
    - [ ] Can you set a location by entering "800 Guadalupe"?
    - [ ] Can you set a location by dragging the icon somewhere?
    - [ ] If you clear/x out the location, does the page prevent you from going forward?
- [ ] /share-evidence
  - [ ] Gosh darn it, its still called /share-evidence, didn't we change that already?
  - [ ] Can you upload a picture?
  - [ ] Can you upload a *second* picture?
- [ ] /officer-details
  - [ ] Can you enter all information about 2 officers?
- [ ] /witness-details
  - [ ] Can you enter all information about 2 witnesses?
- [ ] /about-you
  - [ ] Can you enter all information about 1 yourself?
  - [ ] Maybe do like 1 or 2 runs (out of the 4 forms) where you don't enter your information here, but wait until the final email submission form to see if that works.
- [ ] /review-and-submit
  - [ ] Is all your information there?
- [ ] /confirmation
  - [ ] See if that email input thing works for the runs where you didn't enter personal information.
- [ ] Check your email
  - [ ] Did you get an email with your confirmation number?
  - [ ] Does the copy of your report have all the stuff you entered in it?
  - [ ] If not, double check with Sergio, because I think he's still getting all of our staging emails.
- [ ] Modal
  - [ ] Does the modal pop up when you try to switch languages when you've entered data?
  - [ ] Does it let you switch to another language if you say "Yes"?
- [ ] Spanish Form Considerations
  - [ ] Is it in Spanish? (Did all of our text translations work?)



Sprint-specific considerations to kinda watch out for:
<!--- list related issues here, add checkboxes as needed --->
- [ ] <!--- link to related issue --->
  - <!-- description to test -->
<!--- eg. 
- [ ] https://github.com/cityofaustin/techstack/issues/1743
  - Covered by regression testing. Basically make sure the file uploader on /share-evidence works.
--->
