## SD Interface Courier Releases

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

