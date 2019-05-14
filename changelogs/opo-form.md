# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

Most relevant repos <!-- keep this up to date if it changes!! -->: 
- [coa-forms](https://github.com/cityofaustin/coa-forms)
- [cityofaustin/us-forms-system](https://github.com/cityofaustin/us-forms-system)
- [form-service-api](https://github.com/cityofaustin/form-service-api)

## 2.1.1 - 2019-5-14

## 2.1.0 - 2019-4-30
### Added
- [coa-forms](https://github.com/cityofaustin/coa-forms): a new, consolidated repo application that uses our fork of us-forms-system
- Now we can make builds for individual branches instead of just production or master
- Forms will now validate phone, zip code, and email address fields
### Changed
- Improved location selector widget: 
    - Refactored to be easier to maintain and extend!
    - Switched to Mapbox reverse geocoder.
    - Reverse Geocode is not triggered when user types in an address using the forward geocoder
- Switched to CircleCI (a better long term option) for integration & builds
### Deprecated
- usfs-components, usfs-schema-blocks, officer-form-chapters, officer-complaint-form, and officer-thanks-form repos are consolidated into coa-forms (see above)
### Fixed
- Location on form is not fed an initial location
- Form data for location is cleared when a user clears the result on the Select Location widget
- Fixed mobile zooming when user taps on calender icon
- Fixed various minor translation issues
- Minor styling issues (e.g. modal box cut off on some mobile browsers)
- Error messages now show up properly on Spanish versions of the form


## OPO Media Push [2.0] - 2019-03-25
### Added 
- New Date Picker. It’s more human-readable and screenreader accessible.
- Warning modal that pops up when you switch languages. This prevents users from accidentally deleting all of their form data.
- Users have the option of entering their email after the form has been submitted. This is an extra touchpoint to reach out to users who did not want to give contact information earlier in the process.

### Changed
- Location Picker (map). It’s now on its own page to draw more focus to it. It also has zoom buttons, and some features that confused users have been removed (e.g. 3-D mode).

### Fixed
- Broken links have been fixed.
- Phone numbers are now links that mobile users can call.
- Various minor styling and copy improvements.
- Various UI/functionality bugs, including translation/localization issues
- Some minor pageload performances
