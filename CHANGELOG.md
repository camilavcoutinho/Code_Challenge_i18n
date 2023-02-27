# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).


## [Unreleased]
### Fixed

- Updated the translations on en.json package
- Replaced inventory with stock on en.json package
- New strings added to the pt.json package

## [13.0.9] - 2023-01-03
### Fixed

- Modify pick point field from select to input

## [13.0.8] - 2022-12-23

### Fixed

- English, Portuguese and Spanish translations.

## [13.0.7] - 2022-12-19

## Changed

- Thrown exception when trying to delete store with associated seller.
- Intro new modal when trying to delete store with associated seller.

## [13.0.6] - 2022-12-16

## [13.0.5] - 2022-12-16

## [13.0.4] - 2022-12-12

## [13.0.3] - 2022-12-09

### Fixed

- Save and update store fixes.
- Removed return in store resolver.

## [13.0.2] - 2022-12-09

### Fixed

- Padding correction in infoModal

## [13.0.1] - 2022-12-05

### Fixed

- vtex.splunk-monitoring dependency removal

## [13.0.0] - 2022-11-30

### Changed

- Change vendor to vtex

## [12.0.0] - 2022-11-30

## [11.0.0] - 2022-11-29

### Changed

- Node builder version to 6.x

## [10.3.11] - 2022-11-29

### Changed

- The data was processed before being displayed in registration forms

## [10.3.10] - 2022-11-25

### Added

- In vendors, searching by email.

## [10.3.9] - 2022-11-23

### Changed

- Height and width from modal
- Spacement between lines in modal.
- Size from modal button.
- Scrollbar inside ModalContent.
- Fix alert width in small screens.
- Menu cell in table from Physical Stores.

## [10.3.8] - 2022-11-23

### Fixed

- Don't show items with empty name

## [10.3.7] - 2022-11-23

### Fixed

- Makes neighborhood, city, and state fields mandatory
- Adds validation messages to fields
- Resets the fields filled in by the zip code query before filling them in, avoiding inconsistencies.

## [10.3.6] - 2022-11-23

### Added

- Added check auth token in resolvers.

## [10.3.5] - 2022-11-22

### Changed

- At the search, list results order changed to alphabetical. 

## [10.3.4] - 2022-11-22

## [10.3.3] - 2022-11-21

### Changed

- Change styles of modal of visualize physical store

## [10.3.2] - 2022-11-18

### Fixed

- Inconsistency of the error message in the email field in the seller's registration
- Inconsistency of the error message in the name field in the store registration
- Correction of toast measures in store registration
- Added toast of discarded changes in store edition

## [10.3.1] - 2022-11-18

### Fixed

- Changing the height and width of inputs
- Adding spacing between sessions
  
### Fixed

-Modify style of modals to exclude seller and store

## [10.3.0] - 2022-11-16

### Fixed

- Remove spaces before encode string for search.

## [10.2.3] - 2022-11-11

### Fixed

- Remove skeleton in menu button.
- Fix popover menu styles.
- Fix margins and paddings.
- Change 'Discard' button function in Register Sale.
- Change toast size.

## [10.2.2] - 2022-11-09

### Fixed

- Empty state fix in DataView
- Link fix to Physical Store Register
- Messages changed at empty state from DataView

## [10.2.1] - 2022-11-09

### Changed

- Modification of padding, height and width of modals
- Modifying the height and width of the modal buttons

## [10.2.0] - 2022-11-08

### Added

- Delay warning messages were created for changes in physical stores and sales associates screens


## [10.1.0] - 2022-11-07

### Changed

- Update Admin UI version (134.0).
- Update the dependencies
- Remove messages unnecessary.
- Added new props in Pagination.
- Replace 'useGridState' for 'useTable'.
- Restructure Table with new format.
- Change styles.

## [10.0.2] - 2022-11-04
### Changed

- Remove subsection of configurations

### Changed

- Change logic from filter search
- Add filter popover status

## [10.0.1] - 2022-11-04

### Fixed

- Fix error on encode URI
- Add method for encode URI in search stores and search sales associates

## [10.0.0] - 2022-11-04
### Changed

- Fixed scroll in pages, modals, combobox and filter
- Modal height and width
- Adjust Back Button Measurements
- Spacing between buttons
- Correct entry measurements
- Fix input spacing
- Fix session spacing
## [9.0.3] - 2022-11-03

### Changed

- Phone mask creation
- Refactoring the CEP mask
- Application of masks in the store listing

## [9.0.2] - 2022-10-31

### Fixed 

- Fixed saveOrUpdateVendor with filter syntax error removal.

## [9.0.1] - 2022-10-26

### Fixed

- Fix some styling issues in Sales Associates page
- Height and padding from header
- Page title
- Width and height in "Register sales" button
- Width and height in SearchBar
- Height in filterButton
- Table row height

## [9.0.0] - 2022-10-25

### Fixed
- Fix general cache issues

## [8.1.1] - 2022-10-24

## [8.1.0] - 2022-10-23

### Changed

- The order of the listing of stores and sellers has been changed by adding a filter to the search query to the master data

## [8.0.0] - 2022-10-21

### Changed

- new Major

## [7.6.7] - 2022-10-21

### Added

- billingOptions on Manifest

## [7.6.6] - 2022-10-20

### Fixed

- Add state to editing postal code, to prevent load values on initial render

## [7.6.5] - 2022-10-19

### Fixed

- Fixed edit button navigation of actions menu, in sales associate.
- Physical store error message added in sales associates register

## [7.6.4] - 2022-10-18

### Fixed

- Fix menu(edit and delete) popover bug that had part of the content cut off in the SalesAssociates and PhysicalStores table

## [7.6.3] - 2022-10-18

### Fixed

- Add label to form components

## [7.6.2] - 2022-10-18

### Fixed

- Checking existing store name in backend
- Added store name validation flow in frontend

## [7.6.1] - 2022-10-17

### Fixed

- Added function to validate fields with errors on initial load

## [7.6.0] - 2022-10-17

## Changed

- Create subsections for sales associates and physical stores
- Remove sales associates and physical stores from admin instore settings

## [7.5.1] - 2022-10-06

### Changed

- Add Skeleton postalCode

## [7.5.0] - 2022-10-06

### Changed

- Add zipe code validation
- Integrate checkout api postalCode

## [7.4.8] - 2022-10-05

### Fixed

- Correction of help texts
- Adding validation of at least two characters in physical store registration inputs

## [7.4.7] - 2022-10-04

### Fixed

- Change value null to white spaces in fields.
- Check ifs to set physical store value.
- Store ID encoded in sales association.

## [7.4.5] - 2022-10-03

### Fixed

- Show trade policy name and save id in store register
- List of stores with the names of commercial policies
- Fixes the Country input error message

## [7.4.4] - 2022-10-03

### Fixed

- Add space in empty field

## [7.4.2] - 2022-09-30

### Changed

- Fix redirect link on viewState of empty
- Add refetch function to viewState of error

## [7.4.1] - 2022-09-29

### Fixed

- Fixes design inconsistencies

## [7.4.0] - 2022-09-28

### Added

- Add a search bar to find filters to filter table of vendors

## [7.3.0] - 2022-09-21

### Changed

- Replace store id for store name in Sales Associates Register page
- Change profile seller modal title to "Profile Seller"

## [7.2.2] - 2022-09-20

### Fixed

- Duplicate toast fix when completing seller edit

## [7.2.1] - 2022-09-20

### Changed

- Changed physical store input field in sales associates to combobox type

## [7.2.0] - 2022-09-15

### Added

- Filter vendor by store

## [7.1.0] - 2022-09-12

### Added

- Create edit store page
- Create edit vendor page

## [7.0.3] - 2022-09-08

### Fixed

- Handling the conflict between help and error messages

## [7.0.2] - 2022-09-05

### Changed
- Creating the frontend flow when a seller email already exists in the database
- Remodeling how to handle errors returned by mutation
- Adding an error message to the email input

## [7.0.1] - 2022-08-31

### Changed

- Change field franchise account to TextInput
- Change franchise account to optional field
- Fixed messages

## [7.0.0] - 2022-08-31

### Changed

- Update cache after mutation in Physical Stores page.

## [6.6.0] - 2022-08-30

### Changed

- Updating admin-ui to version 0.133.6
- Update use of Formik to Form

## [6.5.1] - 2022-08-25

### Fixed

- Making the saveOrUpdateVendor mutation responsible for checking if the email already exists in the database.

## [6.5.0] - 2022-08-24

### Changed

- New query: getTradePolicies
- New client: catalog
- Integration with Catalog API
- Input select trade policies options updated with api

## [6.3.0] - 2022-08-23

### Changed

- New query: getPickupPoints
- New client: Logistics
- Integration with Logistics API
- Input select pickup points options updated with api

## [6.2.2] - 2022-08-17
### Fixed

- Error message fix

## [6.2.0] - 2022-08-17

## Fixed

- Specifies the return of saveOrUpdateVendor mutation

## [6.1.4] - 2022-08-16

### Changed 

- Refact data grid error from vendors and stores

## [6.1.3] - 2022-08-15

### Fixed

- Validates the email and displays an error message.
- Validates the name to have at least two characters.

## [6.1.2] - 2022-08-11

### Changed 

- Refact vendors search bar with pagination

## [6.1.1] - 2022-08-10

### Fixed

- Bugs on collapsible tests

## [6.1.0] - 2022-08-10

### Added

- Implementation of back button from sellers
- Sellers page header action buttons enable control
- Adjustment to discard the store register

## [6.0.0] - 2022-08-10

### Fixed

- Fix project version

## [5.7.0] - 2022-08-10

### Added

- Create mutation saveVendor
- Integrate mutation with Sales Associates Register
- Create confirmation register modal

## [5.6.0] - 2022-08-09

### Changed

- Add search field in stores query
- Add search field in vendors query 
- Refact search bar with pagination
- fix double error message

## [5.4.0] - 2022-08-09

### Added

- Stores page header action buttons enable control
- Implementation of back button from stores
- Implementation of discard button from stores

## [5.2.0] - 2022-08-04

### Fixed

- Fix collapsible card bugs
- Fix Search Bar from settings page

## [5.1.1] - 2022-08-03

### Changed

- Fix store view modal
- Fix hover effect of selects

## [5.1.0] - 2022-08-03

### Changed

- Add filter and paginate boolean an query stores
- Add filter and paginate boolean an query vendors
- Refact MasterData Client
- Refact storeClient
- Refact vendorClient

## [5.0.1] - 2022-08-01

### Changed

- Fix sellers email column name

## [5.0.0] - 2022-07-28

### Changed

- Fix email field for business phone

## [4.2.0] - 2022-07-27

### Added

- New query filter to Stores

## [4.1.0] - 2022-07-27

### Changed

- Fix Status Screen Test not found

## [4.0.0] - 2022-07-27

### Changed

- Refactor getVendors with Relay Spec

## [3.1.0] - 2022-07-27

### Changed

- Fix test on search flow

## [3.0.2] - 2022-07-27

### Changed

- Fix some inconsistencies with prototype

## [3.0.1] - 2022-07-27

### Changed

- Fix bugs on Customer Identification Context
- Swap array for set in initialStateIdentificationTypes from Customer Identification Context

## [1.2.2] - 2022-07-26

### Changed

- Fix search bar
- Fix switch position

## [1.2.1] - 2022-07-21

## [1.2.0] - 2022-07-21

### Changed

- Update admin-ui version

## [1.1.2] - 2022-07-20

### Added

- Add skeleton in listing

## [1.1.1] - 2022-07-20

### Changed

- Fix version

## [1.1.0] - 2022-07-19

### Added

- Create the add seller page

## [1.0.0] - 2022-07-06

### Changed

- Corrigindo release

## [0.116.0] - 2022-07-05

### Changed

- Refactor getStores with Relay Spec

## [0.115.3] - 2022-07-05

### Changed

- Fix bug on Payment Conditions Page
- Update mock of RegisterPhysicalStore

## [0.115.2] - 2022-07-04

### Changed

- Update snapshot tests

## [0.115.1] - 2022-07-01

### Added

- Integrate mutation delete Vendor with button delete
- Remove checkbox for sales associates
- Fix test failures

## [0.114.0] - 2022-06-22

### Added

- add Mutation delete Vendor

### Added

- Create mutation for delete physical store
- Create node client and resolver for delete physical
- Integrate with frontend

## [0.113.1] - 2022-06-13

### Changed

- Crash bug fix
- Bug fix and conflict between customer customization page modals
- Change the title of the back modal

## [0.113.0] - 2022-06-09

### Added

- Create snapshot test for page register physical store
- Create mock for page register physical store

## [0.112.0] - 2022-06-02

### Added

- Create Container component to pages of registrations
- Create physical stores registration page
- Add Mutation delete for  sales associates
  
## [0.111.0] - 2022-05-31

- Create search bar for Physical Stores

## [0.110.0] - 2022-05-30

### Added

- Create search bar for Sales Associates Register
- Minor tweaks to the Sales Associates Register interface

## [0.109.0] - 2022-05-27

### Added

- Add the new modal in Sales Associates Register
- Implement Skeleton on Sales Associates

## [0.108.0] - 2022-05-27

### Changed

- Update message from home page tweaks
- Update header from home page tweaks
- Implement Skeleton on Physical Stores table 

## [0.107.0] - 2022-05-26

### Added

- Integrate sales associates table with masterdata
- Add context to sales associates register screen
- Add pagination to Data View of sales associates register table

## [0.106.0] - 2022-05-25

### Added

- Create new modal to display Informations
- Add the new modal in Physical Stores Register and Sales Associates Register

## [0.105.0] - 2022-05-23

### Changed

- Add context to Physical Stores Register screen
- Add pagination to Data View of Physical Stores Register table

## [0.103.0] - 2022-05-21

### Changed

- Refactor PaymentConditions.test.tsx to use MockedProvider

## [0.110.0] - 2022-05-30

### Changed

- Refactor getStores with Relay Spec

## [0.102.0] - 2022-05-17

### Added

- Integrate physical stores table with masterdata

## [0.101.3] - 2022-05-16

### Changed

- Refactor component styles

## [0.100.14] - 2022-05-12

### Changed

- Fixed and desabled linters checks and removed check integrity for now

## [0.100.13] - 2022-05-12

### Added

- Chore(ci): basic structure for github actions

## [0.100.12] - 2022-05-10

## [0.100.11] - 2022-05-09

### Removed

- Remove message propagation operator

## [0.100.10] - 2022-05-09

### Changed

- Refactor dataTestID label in the components

## [0.100.9] - 2022-05-07

### Changed

- Refactor render method in Jest tests
- Isolate component styles

## [0.100.8] - 2022-05-05

### Added

- Create new skeleton for Customer Identification

## [0.100.7] - 2022-04-27

### Added

- Create new skeleton for inStore Language

## [0.100.6] - 2022-04-20

### Added

- Create new skeleton for Payment Conditions

## [0.100.5] - 2022-04-20

### Added

- Create new skeleton for Text On Order Print

## [0.100.4] - 2022-04-19

### Added

- Create new skeleton for Inconsistent Stock

## [0.100.3] - 2022-04-18

### Added

- Create new skeleton default

## [0.100.2] - 2022-04-13

### Added

- Refactor data-testid of all components

## [0.100.0] - 2022-04-12

### Added

- Create search bar for configurations

## [0.99.0] - 2022-04-08

### Added

- Create tables for pages of physical stores and sales associates

## [0.98.1] - 2022-04-05

### Changed

- Modified the initialization of the legal entity registration data
- Updated the schema to correct the name of the anonymous user registration configuration

## [0.98.0] - 2022-03-23

### Added

- Create page header for physical stores register and sales associates register

## [0.97.2] - 2022-03-23

### Changed

- Update instore settings schema

## [0.97.1] - 2022-03-22

### Fixed

- Removed useMemo wrong used

## [0.97.0] - 2022-03-22

### Added

- Implemented dataview pattern to Customer Identification Page

## [0.96.3] - 2022-03-18

### Changed

- Align the project code with the prototype.

## [0.96.2] - 2022-03-17

### Changed

- SaveModalDialog refactor

## [0.96.1] - 2022-03-17

### Changed

- Hide registration cards temporarily

## [0.96.0] - 2022-03-15

### Added

- Create cards for physical stores and sales associates

## [0.95.1] - 2022-03-11

### Changed

- Fixed ToastProvider on Index File
- Moved hooks folder to core folder

## [0.95.0] - 2022-03-10

### Added

- e2e tests for customer identification page

## [0.94.0] - 2022-02-22

### Added

- Modal disable all forms of identification

## [0.93.0] - 2022-02-11

### Removed

- Removed unused code and its dependencies

## [0.92.5] - 2022-02-11

### Changed

- Bad variable names

### Removed

- Unused QRCode messages

## [0.92.3] - 2022-02-07

### Upgraded

- Upgraded packages with security issues

## [0.92.2] - 2022-02-03

### Upgraded

- Upgraded packages with security issues

## [0.92.1] - 2022-02-02

### Removed

- Removed unused i18n messages

## [0.92.0] - 2022-01-28

### Added

- Integrated Customer Indentification interface with backend

## [0.91.12] - 2022-01-26

### Fix

- Fix cypress test at textOnOrderPrint page

## [0.91.11] - 2022-01-25

### Fix

- Fix tokens inconsistency adminUI version

## [0.91.10] - 2022-01-25

### Chore

- Upgraded packages with security issues

## [0.91.3] - 2022-01-19

### Fix

- Select language component issue

## [0.90.3] - 2022-01-03

## [0.91.2] - 2022-01-17

### Removed

- Removed registration settings of settings page

## [0.91.1] - 2022-01-14

### Removed

- Removed unit toast tests

### Chore

- Change array to set of Payment Conditions

## [0.91.0] - 2022-01-13

### Removed

- Removed settings param from getInstoreSettings Query

### Added

- Added masterdata builder

## [0.90.3] - 2022-01-03

### Removed

- Remove vtex tachyons

## [0.90.1] - 2021-12-22

### Fix

- Fix backend content
- MasterData new definitions

### Added

- Add code to get data inside checkout-custom-instore

## [0.90.0] - 2021-12-21

### Added

- Add modals in customer identification

## [0.89.0] - 2021-12-21

### Added

- e2e tests for inStore language setting

## [0.88.0] - 2021-12-16

### Added

- add e2e test about textOnOrderPrint component

## [0.87.0] - 2021-12-15

### Added

- add unit test of some components and refactor some functions

## [0.86.0] - 2021-12-14

### Added

- Instore language setting backend

## [0.85.0] - 2021-12-13

### Added

- Add pre visualization note component

## [0.84.0] - 2021-12-13

### Changed

- Back modal to instore settings page with all features

## [0.83.0] - 2021-12-07

### Changed

- Remove a QR Code option
- Remove radio button
- Add the toggle in legal entity

## [0.82.0] - 2021-12-03

### Added

- Add Drag and Drop functionality to CheckBox buttons

## [0.81.2] - 2021-11-29

### Changed

- Change the language item format
- Replace currentLanguage with LanguageSelectState in InStoreLanguageContext

## [0.81.1] - 2021-11-24

### Fix

- Add smooth scroll to collapsible when click in it

## [0.81.0] - 2021-11-23

### Added

- Back modal to instore settings page

## [0.80.0] - 2021-11-19

### Added

- Context to store state and language update functions

## [0.79.0] - 2021-11-19

### Added

- Connect component with back-end and implement save modal tests

## [0.78.0] - 2021-11-18

### Added

- Save and discard modals added on text-on-order-print component

## [0.77.0] - 2021-11-17

## Added

- Add customer identification anonymous customer card

## [0.76.0] - 2021-11-17

### Added

- Save and discard modals in the inStore language setting

## [0.75.0] - 2021-11-17

## Added

- Add customer identification legal person card

## [0.74.0] - 2021-11-17

### Added

- Initial structure of inStore language setting

## [0.73.0] - 2021-11-11

## Added

- Add customer identification checkbox

## [0.72.0] - 2021-11-10

### Added

- Add Textarea and title in component and messages

## [0.71.1] - 2021-11-08

### Changed

- Cypress tests

## [0.71.0] - 2021-11-08

### Added

- Add Collapsible inside settingsPage component and start TextOnOrderPrint component

## [0.70.0] - 2021-11-08

### Added

- Backend code (monorepo)

## [0.69.0] - 2021-11-03

### Added

- e2e tests for the main flows of US 2

## [0.68.0] - 2021-10-28

### Added

- Add cypress test flow US6

## [0.67.0] - 2021-10-27

### Changed

- Refactored some components PageHeader and DiscardModalDialog

## [0.66.0] - 2021-10-27

### Added

- inconsistent stock query and mutation

### Changed

- Update payment conditions query and mutation

## [0.65.1] - 2021-10-22

### Added

- alter SWR query
- updateInStoreSettings query

### Changed

- getInStoreSetting return and signature

## [0.65.0] - 2021-10-21

### Added

- Add save, back and discard modals of inconsistent stock page

### Changed

- Fix getInstoreSettings default return

## [0.64.1] - 2021-10-20

### Fix

- Refactor payment conditions code and also create a context

## [0.64.0] - 2021-10-07

### Added

- Add descritive card of inconsistent stock page

## [0.63.1] - 2021-10-11

### Fix

- Fix the test wrapper all payment components with provider

## [0.63.0] - 2021-10-06

### Added

- Inconsistent stock page initial structure

## [0.62.0] - 2021-10-05

### Added

- Added stateScreens in paymentConditions component with tests implemented

## [0.61.1] - 2021-10-05

### Added

- Added Back and Discard Modal back button test

## [0.61.0] - 2021-10-04

### Added

- Add cancel button in disable all conditions modal
- Add unit tests to disable all conditions modal

## [0.60.0] - 2021-10-01

### Added

- Added modal back and discard
- Added modal back and discard tests

## [0.59.1] - 2021-09-29

### Changed

- Update admin-ui version
- Apply Page pattern

## [0.59.0] - 2021-09-28

### Added

- Disable all payment conditions dialog

### Changed

- Remove tooltip component and add alert box
- Fix texts in save changes dialog

## [0.57.2] - 2021-09-23

### Added

- Added test snapshot for modal dialog and save

## [0.57.1] - 2021-09-20

### Fixed

- Fix search component, cleaning code and test the flow search

## [0.57.0] - 2021-09-17

### Added

- Added test for GeneralInStoreContainer

## [0.56.1] - 2021-09-17

### Added

- Add check yarn integrity pre commit hook

## [0.56.0] - 2021-09-16

### Changed

- Update components according to the new version of Admin-ui

## [0.54.1] - 2021-09-15

### Added

- New eslint rule to avoid gigantic code files

### Changed

- Refactoring PaymentConditions and StoreForm components to reduce its file's size

## [0.54.0] - 2021-09-14

### Added

- Added GeneralInStoreContainer component

## [0.53.0] - 2021-09-14

### Added

- Added swr hook to retrieve instore settings periodically from Master Data

## [0.52.0] - 2021-09-14

### Added

- Testing of saving and discarding payment conditions

## [0.51.0] - 2021-09-13

### Added

- Added toast component, unit test about toast component and fix some visual issues

## [0.50.1] - 2021-09-10

### Added

- Eslint rule that disable explicit any type usage

## [0.50.0] - 2021-09-09

### Added

- Add component modal dialog in Payment Conditions screen

## [0.49.5] - 2021-09-08

### Changed

- Mock vtex.render-runtime package during unit tests
- Add component modal dialog to Payment Conditions screen

## [0.49.2] - 2021-09-02

### Changed

- Rename payment methods for payment systems

## [0.49.1] - 2021-09-02

### Removed

- Remove pagination component from payment conditions page

### Changed

- Fix background of the payment conditions page
- Align the payment conditions search bar

## [0.49.0] - 2021-09-01

### Added

- Add graphQL interaction on button paymentSaved
- Integration graphQL, masterData and FrontEnd interaction

## [0.48.0] - 2021-08-24

### Added

- Add tooltip test

## [0.46.0] - 2021-08-20

### Added

- Add card component from settings page

## [0.44.0] - 2021-08-20

### Added

- Add action buttons to the payment conditions page

## [0.43.0] - 2021-08-20

### Added

- Adding the pagination component test

## [0.42.0] - 2021-08-20

### Added

- Add tooltip message for connectors

## [0.41.1] - 2021-08-18

### Changed

- Modication page header payment conditions

## [0.41.0] - 2021-08-17

### Changed

- Refactor search bar to encompass other screens that use it

## [0.40.0] - 2021-08-16

### Added

- Adding the checkbox component to the payment terms and test unit

## [0.39.0] - 2021-08-12

- Add Search Bar

## [0.38.0] - 2021-08-11

### Added

- Add Splunk configuration

## [0.36.0] - 2021-08-11

### Added

- Pagination component in PaymentMethodsContent

## [0.35.0] - 2021-08-06

### Added

- Add tests to inStore settings page

### Changed

- Fix inStore item in the settings menu

## [0.33.4] - 2021-08-04

## Added

- Remove simple warnings
- Update tsconfig file

## [0.33.2] - 2021-08-04

### Changed

- App Vendor

## [0.33.1] - 2021-08-03

### Changed

- Cypress tests login strategy

## [0.33.0] - 2021-08-03

### Added

- PaymentsCondtions page with table

## [0.32.0] - 2021-07-30

### Added

- inStore settings page

### Changed

- inStore item in the settings menu within the Storefront section
- Route of access to inStore settings page

## [0.31.0] - 2021-07-27

### Changed

- Update folders structure

## [0.30.2] - 2021-07-21

### Changed

- Bump AdminUI version and change statefulTable to the statelessTable

## [0.30.1] - 2021-07-19

### Changed

- Replace term vendor by sales associate

## [0.30.0] - 2021-07-16

### Added

- cypress test

### Removed

- Unit test from pre-commit hook

## [0.29.1] - 2021-07-01

### Removed

- `navigation.json`

## [0.29.0] - 2021-06-29

### Changed

- Make the `navigation.json` empty in order to hide the menu's instore label

## [0.26.0] - 2021-06-23

### Added

- Update Pagination Component with admin-ui version

## [0.25.0] - 2021-06-17

### Added

- Added snapshot test about StoresContent and VendorsContent component

## [0.24.0] - 2021-06-15

### Changed

- Migrate Tabs component to admin-ui version

## [0.23.1] - 2021-06-11

### Added

- Documentation on how to test locally
- ButtonWithIcon test

### Changed

- Refactored ButtonWithIcon component

## [0.23.0] - 2021-06-10

### Added

- Search component test

### Changed

- Migrate Search component to admin-ui

## [0.22.0] - 2021-06-10

### Added

- Migrate Input on VendorsForm and create a generic Component

## [0.21.1] - 2021-06-08

### Fixed

- Fix Address Function Bug and function address test

## [0.21.0] - 2021-06-07

### Added

- Menu Actions component
- Modal Dialog component
- Toast component

### Changed

- Refactoring utils

## [0.19.1] - 2021-06-03

### Fixed

- Fix Input Component Bug

## [0.19.0] - 2021-06-02

### Added

- Select component test

### Changed

- Migrate Select component to admin-ui version

## [0.18.0] - 2021-05-28

### Changed

- Migrate table component to admin-ui version
- Refactored the Table component component code

## [0.17.0] - 2021-05-27

### Changed

- Migrate Button with icon component

## [0.15.0] - 2021-05-25

- Use Spinner component from admin-ui

## [0.12.0] - 2021-05-19

### Changed

- Migrate Input component

### Added

- Input component tests

## [0.11.3] - 2021-05-12

### Changed

- ToggleButton component

### Added

- ToggleButton test

## [0.11.2] - 2021-05-12

### Changed

- Finish the card component configuration and fix some visual issues

## [0.11.1] - 2021-05-12

### Changed

- Lint and format commands
- Upgraded admin-ui package

## [0.10.0] - 2021-05-07

### Changed

- Migration box component styleguide to card component admin-ui

## [0.9.0] - 2021-05-07

### Added

- RadioGroup component test

### Changed

- RadioGroup component

## [0.8.0] - 2021-05-07

### Added

- CheckBoxButton component test

### Changed

- CheckBoxButton component
- Migration ConfigurationPage from Admin-UI

## [0.7.1] - 2021-05-05

### Removed

- Removed TextInput file

## [0.7.0] - 2021-03-22

### Added

- Initial test environment setup

## [0.6.0]

### Added

- Store form's country input field validation

### Changed

- Store form's country input field

## [0.4.0]

### Added

- Stores and Vendors page

### Added

- Stores CRUD operations to the graphql api
- Vendors CRUD operations to the graphql api