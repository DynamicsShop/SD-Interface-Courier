## SD Interface Courier Releases

### 5.0.1

#### Enhancements

- AppSource App - Functionality was added to allow for situations where the errors raised on orders sent for booking are copied to a blob field so the error detail can be viewed.

- AppSource App - A change was made to limit the SD ISV Tenant Subscriptions page to display just our SD ISV AppSource Apps and not other SD PTE Apps.

#### Bug Fixes

- AppSource App - When selecting SD Interface Courier activity pages in the Tell Me/Search in a BCv22 environment, the activity pages were hanging.

- AppSource App - The SD Interface Courier Setup card was hanging in a BCv22 environment if the KPI FastTab was minimised on opening the page. 

### 5.0.0

#### Enhancements

- AppSource App - Direct integration to DPD Domestic for Service Options 1, 2 and 5 was added to SD Interface Courier.

- AppSource App - A Booking Form was created for the DPD Courier Implementation.

- AppSource App - Changes were made to the Courier Service Card to display the necessary fields for DPD integration.

#### Bug Fixes

- AppSource App - An intermittent error that "The changes to the SDY UC Booking Entry record cannot be saved because some information on the page is not up-to-date." was raised when Booking Parcels. This was fixed.  

- AppSource App - The Skip and Archive action in the Booking Pending list was adding the orders to the Archive but entries were being brought back in when the Check for New Entries action was chosen.

- AppSource App - Choosing the Track Booking action in the Booking Shipment list for a parcel booked with DPD raised a HTTP error.

- AppSource App - For DHL Worldwide a fix was made to take the  Sales Line Amount Excluding VAT and divide by the Sales Line Quantity to get a calculated Value Excluding VAT that is displayed on the DHL Worldwide Lines on the DHL Booking Entry Page in the Unit Price Excl. VAT field and is passed to DHL for Commercial Invoices. 

- AppSource App - When adding a new Courier Service and choosing to enable the Courier Service, if consignment details were not entered, a message was raised to prompt of same, and the value in the DPD Basic Token field was then cleared. This was fixed.

- AppSource App - A change was made to the ISV Licence Notification procedure in SD Interface Courier to fix an issue that would raise an error when the language is changed from English to another language.

### 4.0.1

#### Enhancements

- BCv21 App - The Unit Price Excluding VAT was added to the Booking Entry Card for SD Interface Courier's calls to the Courier Services Commercial Invoices API functionality.

- BCv21 App - The Licence Expiry message/notification was updated to display the App Name as part of the message.

- BCv21 App - A page was created to display all the Simply Dynamics Apps and subscription details for the tenant.

- BCv21 App - The Licence Message displayed on first install of SD Interface Courier was changed to prompt the user to activate a free trial.

#### Bug Fixes

- BCv21 App - A fix was made to the code for licence key checks on the SD Interface Courier Role Centre. 

### 4.0.0

#### Enhancements

- BCv20 App - Created a new AL extension app based on latest release of the C/AL code.  

- BCv20 App - A change was made to allow for two email notification points in SD Interface Courier - one at Order Booked and another at Order Shipped. 

- BCv20 App - A new SD Interface Courier Setup table and card were created with import/export definition actions and data retention fields. 

- BCv20 App - The API Request logging code was reworked and improved. 

- BCv20 App - A Courier Service Providers Definition File (json file) was created. 

- BCv20 App - Functionality was created to allow conversion of PDF files to Image files such as png, jpeg etc. 

- BCv20 App - Any remaining courier specific fields were removed from the SD Interface Courier Setup table and placed in courier specific tables. 

- BCv20 App - Some SD Interface Courier tables and fields were renamed. Setup was renamed to Courier Services. 

- BCv20 App - SD Interface Courier was prepared for AppSource submission.  

- BCv20 App - The C/AL Code Base was ported from C/AL to AL BCv17 CU3. 

- BCv20 App - A barcode API was added to the SD Interface Courier Manual Label report. 

- BCv20 App - DHL Paperless Trading was added to the product. 

- BCv20 App - A new All Active cue was added to the Courier Booking Activity page.  

- BCv20 App - The Courier Services Setup Card was reworked. Fields were grouped together. 

- BCv20 App - Changes were made to the Courier Service Communication Details FastTab on the SD Interface Courier Setup page. 

- BCv20 App - The confirmation email used in the SD Interface Courier emailing functionality was changed. 

- BCv20 App - On the Booking Shipment page the caption of the View Sales Order action was changed to Ship Sales Order. 

- BCv20 App - The fields in the Booking Archive page were reordered. A freeze frame was added to the page. 

- BCv20 App - Created a Courier Activity report. 

- BCv20 App - The More Information action was removed from the GLS menu group on the Courier Service Card. 

- BCv20 App - The Completely Shipped field was removed from the Booking History list. 

- BCv20 App - A number of actions were missing from the Booking Archive page. These actions were resurfaced. 

- BCv20 App - The Download DHL Invoice action on the Booking History page was moved to the Tracking menu group as per the layout of actions in the Booking Shipment page. 

- BCv20 App - The Booking Tracking number on the Booking Shipment and Booking History List was reinstated. 

- BCv20 App - A small typo in the Scurri Carriers and Services page was fixed. 

- BCv20 App - In the Courier Service Card the Scurri Services action was placed before the Scurri Warehouse action to reflect order of use during setup. 

- BCv20 App - The Edit DHL Worldwide action text in the DHL XML Service FastTab was removed to keep FastTabs uncluttered.  

- BCv20 App - The User Id field on the Courier Services Card was updated to User ID. 

- BCv20 App - An Post Scurri Configuration was added to the Definition file. 

- BCv20 App - The Service Id field was renamed to Service Entry No. on the SD Interface Courier pages. 

- BCv20 App - The Courier Service Provider column in the SD Interface Couriers Services list was updated to Configuration as per the Courier Services Card. 

- BCv20 App - Minor visual changes were made to the Courier Activity Report. 

- BCv20 App - The SD Interface Courier Activity Report was surfaced on the SD Interface Courier Services List and Card. 

- BCv20 App - The layout of fields in the Service Setup FastTab on the Courier Service Card was changed. 

- BCv20 App - Certain fields were promoted to FastTabs in the Courier Service Setup card. 

- BCv20 App - The External Document No. column was repositioned on the Booking Errors page. 

- BCv20 App - The External Document No. was added to the Booking History page. 

- BCv20 App - The fields in the Booking Shipment page were reordered. 

- BCv20 App - The message displayed when a user chooses to Skip and Archive a Booking Entry was changed. 

- BCv20 App - To keep the pages streamlined any standard notes and link actions were removed from the SD Interface Courier pages. 

- BCv20 App - The Usage Category property was added to the pages for the Tell Me search. 

- BCv20 App - Permission Sets were created for the App. 

- BCv20 App - The latest version of the ISV About Page was added to the App. 

- BCv20 App - The SD Interface Courier objects were renamed to our ISV standards. 

- BCv20 App - A parcel was booked with TEST GLS XML but the email from SD Interface Courier did not contain the Tracking Number. 

- BCv20 App - The message displayed when an order does not fulfil free shipment was updated. 

- BCv20 App - The columns in the SD Interface Courier Email Confirmations List were rearranged. 

- BCv20 App - The Inherit from Company action in the Consignor Details CardPart was recaptioned and placed above the Company field. 

- BCv20 App - The No. field on the Booking Card was recaptioned back to Order No. 

- BCv20 App - For Manual Service Types on the Courier Service Card the mandatory check on the Tracking URL field was removed. 

- BCv20 App - Changes were made to the captions and placement of Actions in the Booking Pending List. 

- BCv20 App - Small typo corrections were made to the Descriptions of Test Courier Service Configurations in the Service Definition file. 

- BCv20 App - Changes were made to Actions and to Action Menu Groups in the SD Courier Service Card. 

- BCv20 App - The name of the Update Services action on the SD Interface Courier Services to Populate Courier Services was changed to be more reflective of what the action does. 

- BCv20 App - A KPI FastTab was added to the SD Interface Courier Setup Card. 

- BCv20 App - The Default Email Account field in the General FastTab of the SD Interface Courier Setup card was promoted. 

- BCv20 App - Changes were made to the captions and ToolTips in the Email Settings Card. 

- BCv20 App - Fields in the Courier Service Card were renamed for clarity and other minor changes were made to the Courier Services Card. 

- BCv20 App - To differentiate between test and live Service Providers, a change was made to display test Service Providers in red. 

- BCv20 App - The  ISO Country/Region Mapping action on the Courier Services list was removed. 

- BCv20 App - The ToolTip on the Update Services action in the SD Interface Courier Services List was updated. 

- BCv20 App - A small typo on the name of the Page SD Interface Courier Services was fixed. 

- BCv20 App - A field caption and ToolTip were updated on the SD Interface Courier Setup Card. 

- Bcv20 App - A new SD Interface Courier Setup tables was created with default email account and Data Retention FastTab to define how long to keep API Logs, Email Logs, Labels, and PLT Sales Documents stored in the database. 

- BCv20 App - The Product Activation Page was updated to point to the new subscription page URL. 

- BCv20 App - ToolTips were updated to look at our new website. 

- BCv20 App - The latest ISV Licence Controller was added to SD Interface Courier. 

- BCv20 App - The existing C/AL build of SD Interface Courier was converted to AL extensions. 

- BCv20 App - A number of events were published before json file is written to the payload to allow for modifications if needed to book parcels with Couriers through the Scurri API. 

- BCv20 App - The DHL schema was updated to version 10. 

- BCv20 App - The Assisted Setup action was removed from the SD Interface Courier Setup as a Definition File for SD Interface Courier is automatically installed on install of the App. 

- BCv20 App - The Allow HTTPClient Request option for SD Interface Courier is set to on by default on install of the product. 

- BCv20 App - A control addin was added to allow conversion of PDF files to Image files (png,jpeg etc). 

- BCv20 App - Code was reviewed to ensure that our ISV Licence Expiry Date prompts with 5 days to go was not stopping functionality. 

- BCv20 App - Merged changes to fix issue where Terms of Trade was not populating for DHL Worldwide. 

- BCv20 App - SMTP Mail was replaced with the Dynamics 365 Business Central SMTP Connector Module. 

#### Bug Fixes

- BCv20 App - An error was raised when booking a Scurri Fastway parcel. This was due to an issue in the Definition file. This was fixed. 

- BCv20 App - Booking parcels with DHL was not updating the package tracking number on the sales order as per manual and GLS bookings. 

- BCv20 App - In the Booking Pending List choosing Cancel correctly removed the Booking Entry from the list but then all the Booking Entries with all Booking Status were displayed in the Booking Pending list. 

- BCv20 App - If a Manual Courier Service was disabled after Booking Entries were created for the Courier, the Booking Entry was booked but no labels was created. A change was made to raise a message to prevent the user booking a parcel when the Manual Courier Service is disabled.  

- BCv20 App - The Label Type in the Configuration file for Scurri Fastway was changed as an error was raised on download of the label. 

- BCv20 App - Choosing to Cancel Bookings in the Booking Pending list was raising and error. 

- BCv20 App - Choosing the Cancel action in the Booking Pending list for a record created an entry in the Booking History table with a status of cancelled. 

- BCv20 App - Choosing to Skip and Archive one record in the Booking Pending List caused all records in the Booking History to be archived. 

- BCv20 App - For the GLS INT configuration the attached document file was not opening. 

- BCv20 App - An error was raised on the Courier Service Card when choosing the Scurri Carrier Service Code field or the Courier Services field.  

- BCv20 App - Emails were sent on original shipment of the order and then again on ship and invoice of the order. 

- BCv20 App - When the SD Interface Courier Services list was opened, not all the Test Service Configurations were set to a red font. 

- BCv20 App - Fixed an issue where the Customer Company Contact email was being picked up. Now if the Recipient Email on the Courier Service Email Settings is set to Document or Document&Specific pick up the Sell-to Email on the Sales Header. 

- BCv20 App - On resetting a booking error, the Confirmation Email field on the Booking Card was continually being appended to. 

- BCv20 App - After choosing the Reset Error action when an error was raised when booking a parcel, an error is raised on choosing to open the Booking Card to rebook the order. 

- BCv20 - The Skip and Archive function on the Booking Pending page was not moving the booking entry record to the Archive table. 

- BCv20 App - The prompt that a charge should be applied to the order was not being raised when the Test for Courier Charge field was switched on and the parcels were under the Min Free Charge Amount. 

- BCv20 App - An error was raised when choosing the Your Capabilities action in the GLS menu group on the Courier Service Card.  

- BCv20 App - Fully Shipped Sales Orders were still showing in the Booking Shipment List and not moving to Booking History. This was fixed. 

- BCv20 App - Fixed an issue where if an email template did not have an email body defined then the email body was being hardcoded. Now if the email body is not defined, the email is not generated. 

- BCv20 App - The Shipping Instructions entered on the Courier Service Card for a Service Type of Manual were not picked up and displayed on the Manual Courier Booking Card. 

- BCv20 App - In the Consignor Details Card an error was raised when choosing the Page action and then the Next action. 

- BCv20 App - The Product Page link in the About Page was directing to an incorrect page. 

- BCv20 App - The Product Activation page was changed to disable the Activate button unless a Product Key is filled in. This was done to avoid an error being raised when Activate was chosen and the Product Key had no value. 

- BCv20 App - Layout changed and functionality changes were made to the DHL FastTab in the Courier Services Card. 

- BCv20 App - Fixed an issue where SD Interface Courier did not populate the weight field on a Fastway label if the parcel had more than one item. 

### 3.0.6

#### Enhancements

- Added paperless trading for DHL to the product. 

#### Bug Fixes

- Fixed a gross weight error raised during creation of a label for the DHL courier service. 

- A fix was made to resolve an xml error raised when parsing the request. This was due to a element exceeding the maximum length. 

### 3.0.5

#### Enhancements

- A minor modification was made for An Post courier through Scurri. 

- The DHL XML Schema was updated to version 10. 

#### Bug Fixes

- When booking a label for Fastway through Scurri an error was raised that the consignment was not ready for printing. 

### 3.0.3

#### Enhancements

- Created a separate DHL Handling Codeunit for worldwide deliveries.

- Logic updated to handle situations for Fastway when user created multiple parcels from a Sales Order that had only one item.

- A change was made to use the Number of Parcels on the Booking Page for Fastway to determine the amount of labels returned.

- The DHL Billing Info Action on the SD Setup Card is disabled for carriers that are not DHL.

- Added new default fields for worldwide shipping to the specific DHL Setup Page.

- In the Courier Warehouse and Courier Services tables we now allow that a Warehouse and a Service can be set up for any of the Couriers in the product.

- New functionality was added to ensure completely shipped orders on the Booking Shipment page were moved to the Booking History page.

- On the Booking Shipment page the caption on the View Sales Order Action was changed to Ship Sales Order.

- A change was made to remove the Scurri fields from the Setup table and place in a Scurri table.

- Changes were made to Confirmation Email Settings on the Setup Card. The Confirmation Source options were changed to None, SD Courier Mail, Carrier Mail. The Email Settings fields were moved off the Setup Card and placed onto a new page.

- On the SD Courier Setup Card, fields were reordered and renamed. Courier Warehouse and Courier Services Actions were placed on the Courier Card.

- Functionality was added to auto insert existing Shipping Agent Code and Shipping Agent Service combinations into the Setup List by choosing a Refresh Couriers Action.

- Captions were updated and the order of fields changed in the Courier Communication Details FastTab on the SD Courier Setup Page.

- A modification was made to the SD Courier Setup page to move the DHL Billing Info FastTab onto a new page.

- Scurri/NAV mapping tables were created.

- Added Scurri API integration to SD Courier.

#### Bug Fixes

- Fixed an error that was raised when booking a DHL package.

- Fixed an issue where if a setup record was deleted from the Courier Setup the records in Booking Pending were not removed.

### 3.0.2

#### Enhancements

- Replaced MLX.dll with http requests.

- Minor visual changes were made to some SD Utilities Courier pages.

- The weight field calculation was changed to round to 2 decimal places.

- The Shipment Date on the SD Utilities Courier Booking Update pages was changed to default to today's date if specified on the Courier Setup.

- Updated the No. of Parcels on the Booking Update Pages to default to 1.

- The colour on the cues on the Courier Activity Panel were set.

- For ease of user input, the Special Instructions field was moved to appear as the last field on all Booking Update pages.

- Made a change on the DHL Booking Update page to default the Extra Insurance option to the value specified on the Courier Setup Card.

- The order of fields in the Courier Charges FastTab on the Courier Setup Card was changed.

- The Group Captions in API Settings FastTab on the Courier Setup Card were updated.

- When Booking a Manual Courier an unsupported .Net Framework Error was raised in the Web Client. 

- A change was made to print to Zebra printers from the DHL Booking Update page.

- A change was made to allow for bookings for DHL Worldwide Shipping.

- The reference field on the DHL Labels is now populated from the Sales Order External Document number.

- Additional fields were added to the DHL labels.

#### Bug Fixes

- An issue was fixed were for multi shipments of the one order, the last package tracking number was being stamped on all shipments.

- An issue was fixed where the Booking Update page was choosing the first Shipping Agent Code for the Courier in the Courier Setup List if the Shipping Agent Code was the same but the Shipping Agent Service Code was different.

- Change the Shipping Agent Service Code to not-editable on the Booking Update pages.

- Fixed an issue where a message was not displaying if a courier charge was due.

- A fix was made to the Manual label to save as PDF and not TXT.

- Fixed an issue where the freight charge inserted on the sales order line was not being converted to the sales order's currency.

### 3.0.1

#### Enhancements

- Added functionality to allow users cancel a GLS booking via the GLS API when the Reset to Waiting Action is chosen.

- A new field, Add Insurance, was added to the Courier Setup Card. The value of this field is now auto-populated on the DHL Booking Update page.

- Made a change to populate all the Ship To Contact details on the Booking Pages from the Sales Header.

- In standard NAV, when the default Sell To Address is chosen as the Ship To Address, the Ship To Code is not populated on the order and therefore the email address on the Ship To Code is not populated. A change was made to display the contact email address on the Booking Update page in this instance.

- Added the View/Print Booking Labels Action to the Booking History and Booking Archive pages.

- The Shipment Date on the Booking Update pages was changed to editable.

- The bespoke .NET calls to the DHL API were changed to standard NAV dlls and code.

- The reference field on the DHL Labels is now populated from the Sales Order External Document number.

#### Bug Fixes

- Made a fix to the DHL labels where labels were downloading by default as pdf.

- Fixed an issue with labels saving to the default folder for GLS labels.

### 3.0.0

#### Enhancements

- The Sales Order Completely Shipped field was surfaced on the Booking pages.

- Visual changes were made to the DHL Booking Update page.

- A change was made so that when an order is completely shipped, the booking entry should move to the Booking History Cue. 

- Added functionality to the Manual Update page to allow users enter the special instructions to print on the label.

- Stamped the name and version of the objects with our new naming conventions.

- Made a change to allow users to save labels directly to a printer folder from the Bookin Update page.

- Changed Gross Weight calculations on Booking Update Pages to default to a calc off a total of the gross weight by quantity (base) on the order lines.

- Changes were made to the DHL Booking Update Page.

- Changes were made to the content of the Shipment Confirmation email for GLS Bookings.

- Added functionality to insert a Courier Charge on the Sales Order Line.

- Removed the Delivery Time field from the DHL Courier Update Page and the Booking Entry table.

- Changes were made to the content of the Shipment Confirmation email for Manual Bookings.

- Changes were made to the DHL Courier Update Page to visually mark the mandatory fields.

- Re-ordered the FastTabs on the SD Courier Setup Card.

- Added new functionality to allow for bookings for multiple shipments on the one order.

- Made a change to refresh the Page when the Book Package action on the Booking Pending page was completed.

- Changed the primary key on the SD Courier Zip Code to allow users enter multiple address descriptions for the same Courier Zip Code.

- Updated Captions on the Role Centre Page, the Label Types page and the Booking Shipment Page.

- Changed functionality to stamp the Package Tracking No on the Sales Order Shipment.

- Visual changes were made to the SD Courier Update Manual page.

- Changed the wording of the message presented when the user chooses to skip and archive a pending booking entry to make the process clearer.

- The order of the FastTabs in the Courier Setup Card was changed.

- Visual changes were made to the Courier Communications FastTab in the Courier Setup Card.

- Updated the Caption on the Courier Booking Activity page.

- Made a change to the functionality of the Skip and Archive Action on the Booking Pending List.

- Made a change to stamp the Posted Sales Shipment Package Tracking No. for DHL, GLS and Manual bookings.

- Visual and layout changes were made to the Courier Update GLS page.

- Changes were made so updates made to the Sales Order would be reflected on the fields in the Booking Pending list.

- GLS Courier Zip Codes and functionality were added to the GLS Booking Update Page.

- Visual and layout changes were made to the Role Centre.

- The font used in the labels is included in the release files.

- Visual changes were made to the Manual Booking Page.

- Made a change to archive booking entries when the sales order is transformed to a posted sales invoice.

- The SD Courier Label Table was created. 

- Visual and layout changes were made to the SD Utilities Courier Setup Card.

- Visual changes were made to the SD Utilities Courier Setup List.

- Changes were made to the courier charges - the functionality was changed to allow for an option to either insert a charge line on the sales order, or, to display a message without inserting a charge line.

- Created functionality to generate a Shipment Notification Email.

- Functionality was developed to archive the booking entries.

- Separate pages were created per SD Courier Entries status.

- The column sequences on the SD Courier Entries pages were tidied up.

- The "Reset to Pending" Action was renamed to "Reset to Awaiting Booking".

- The "Cancel Booking" Action was renamed to "Skip and Archive" to reflect exactly what the Action does.

- Visual and layout changes were made to the Booking Update Page.

- Changes were made to ISO County Mapping.

- The Post Code Match was renamed to Courier Zip Code.

- A new table for the Label Types was created and surfaced on the Setup Page.

- Created a Label Report for Manual Bookings.

- Re-ordered fields on the Setup Page.

- Page and Table Captions were updated to the name of the page.

- Changes were made to the Activity Panel surfaced on the Role Centre.

- Visual changes and improvements were made to the Booking Update page.

- Visual changes and improvements were made to the Courier Setup page.

- Made a change to allow calculation of weight based on sales lines.

- Changes were made to the GLS Courier Zip Code table and page to make it generic.

- Functionality was added to the product to allow for Manual Bookings.

- Created separate Booking Update Pages for the individual couriers and made the page flow logical.

- Reviewed and refactored pages.

- Made a change to allow multiple parcels on a GLS booking to return multiple labels.

- Created functionality to transfer booking entries to an archive table once booking is cancelled or complete.

- Changes were made to the Role Centre Activity Cues and their related pages.

- Removed FTP and CSV Options from the setup card and the code.

- Reordered and renamed product objects.

- Updated the actions in the ribbon on the SD Courier Booking Overview page.

- Visual changes were made to the SD Courier Setup Card.

- Created functionality to call the GLS API.

- Made a change to the Shipping Time on the SD Courier Setup to default to the value of the Shipping Agent Service Code.

- Changed the SD Courier Setup List page to un-editable.

- Added an Action to run inbound files on the SD Courier Role Center and SD Courier Booking Overview pages.

- Visual changes were made on the SD Courier Setup Card around the grouping of FTP fields.

- The character length of the Post Code field in the SD Courier Post Code Match table was increased.

- Added drilldowns to the SD Courier Update Page for ease of use.

- Added Track Booking functionality for GLS as per DHL.

- Removed default printer files from the Courier setup - these were legacy fields used in conjunction with csv files.

- Added an Action "Check for New Entries" in the SD Courier Booking Overview page.

- In the SD Courier Update Page, drill downs were added to the ISO Country Mapping and Post Code Match fields.

- Added checks for mandatory fields in the SD Courier Update Page.

- Visual changes were made to the SD Courier ISO Country Region Page.

- Visual changes were made to the SD Courier ISO Country Region page.

- Visual changes were made to the SD Courier Post Code Match Page.

- Visual and layout changes were made to the SD Courier Booking Overview page.

- The standard NAV Notes and Links were removed from the SD Courier Pages.

- In the SD Courier Setup Card, the Shipping Agent Service Name were not auto displaying when the Shipping Agent Service Code was selected.

- In the SD Courier Setup Card, the Courier Handling Codeunit Name was not auto displaying when the Courier Handling Codeunit was entered.

- In the SD Courier Setup Card, the Courier Handling Codeunits were limited to Codeunits in the SD Courier range.

- Visual and layout changes were made to the SD Courier Setup Card.

- Created a Role Centre for SD Utilities Courier.

- Renumbered the SD Utilities Courier Items to an assigned Microsoft range.

- Streamlined existing functionality and pages.

- Made certain mandatory fields generic on the courier setup table.

- Created a generic Zip Code Match table and page.

- Created a GLS integration handling Codeunit.

#### Bug Fixes

- Fixed an issue where for GLS labels if users choose to print label from the Booking Update page or from the Booking Shipment page an error is raised and the user can't print the label. 

- Fixed an issue where the phone number on the Sales Order was not populated on the Booking Update pages.

- Fixed an issue where the code was not checking the value of the Print Label After Booking option of the SD Utilities Courier Setup Card and the label was printing directly after the courier was booked.

- Fixed an issue where Shipping Confirmation Emails were not working.

- Fixed an issue where booking shipment entries for fully shipped and invoiced sales orders were not moving to the Booking History.

- Fixed an issue where for multiple shipments from the same order, the package tracking number of the latest shipment was stamped on all shipments related to the one order

- Fixed an issue where an Order that was not completly shipped was moved to Booking History.

- Fixed an issue where, the system was always selecting the first Shipping Agent Service Code in the setup when Booking the Courier.

- Fixed an issue for Manual Bookings - for multi shipments, the last package tracking number was being stamped on all shipments.

- Fixed an issue where Sales Orders that were fully shipped remained in the Booking Shipment cue.

- Fixed an issue moving Entries from Booking Shipment to Booking History and Booking Archive.

- Fixed an issue where the Courier Booking No was not being stamped on the Sales Header.

- Fixed an issue with stamping tracking numbers on the sales header when booking a GLS Courier.

- Fixed an issue where choosing View/Print Booking Labels on a manual courier booking did not show any labels.

- Fixed various issues that were raised when booking a Manual Courier.

- Fixed an issue where a Post Code length error was raised when the Booking Entry page was opened.

- Fixed an issue where the Tracking Number was not showing on Shipment Confirmation emails for Manual Bookings.

- Fixed an issue where the Manual Shipment Instructions displayed on the Courier Setup Card did not appear on the Manual Booking Update page.

- Fixed an error that was raised when the SD Courier History Page was opened.

- Fixed an issue where, in the SD Courier Update Page, the codeunit assigned to check data entered is not dependent on the Shipping Agent Code.

- Fixed a bug where updating a Shipping Agent Code on the Courier Booking Entry using the SD Courier Update page did not reset the Shipping Agent Service Code.

- Fixes were made to errors raised when booking a courier for DHL.

- Fixed compile errors in codeunits.

### 2.0.0

#### Enhancements

- Initial build release of SD Utilities Courier.

- Created a standard build of SD Utilities Courier.

- Renumbered some of the pages.

### 1.0.0

#### Enhancements

- Initial build of objects.

