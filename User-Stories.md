[Home](README.md) | [PC-Revival](PC-Revival.md) | [Team Charter](Team-Charter.md) | [User Stories](User-Stories.md) | [Product Backlog](Product-backlog.md) | [Sprint Backlog](Sprint-backlog.md) | [Agile Logbook](Agile-logbook.md)

## User Stories
   
### View available services

As a student, I want to view PC Revival’s available services and estimated prices so that I can decide whether the service fits my needs and budget.

The system displays the main repair and upgrade services.
Every displayed service has a clear description.
Estimated prices are displayed where available.
The user can identify whether a service relates to repair, software support, upgrading or laptop sales.
The service information is readable on common screen sizes.
Tasks
Design the services page.
Create the service-card component.
Add the approved service descriptions.
Add estimated pricing.
Make the layout responsive.
Test the page on desktop and mobile sizes.
### Submit a repair request

As a student, I want to submit a laptop repair request so that PC Revival can assess my device problem.


The user can enter contact details.
The user can describe the laptop and the problem.
Required fields are validated.
The request can be submitted successfully.
The user receives a clear confirmation.
The request is stored for later retrieval.
Tasks
Design the repair-request form.
Add fields for customer and device information.
Implement required-field validation.
Connect the form to the database.
Display success and error messages.
Test valid, incomplete and invalid submissions.
### Track a repair request

As a student, I want to view the status of my repair request so that I know what progress has been made.

A repair request can be found using an appropriate identifier.
The current status is displayed clearly.
Only valid status information is shown.
An informative message appears if a request cannot be found.
Stored request information can be retrieved correctly.
Tasks
Define repair-status values.
Create the status page.
Implement the data-retrieval function.
Display request details and status.
Handle a missing or invalid request.
Test status retrieval.
### Browse refurbished laptops

As a student, I want to browse available refurbished laptops so that I can compare affordable options.

Available laptops are displayed with meaningful details.
Each laptop shows a price.
Availability is visible.
The user can open or view additional product information.
Unavailable products cannot be presented as immediately available.
Tasks
Design the laptop catalogue.
Create a reusable laptop-card component.
Configure laptop inventory data.
Add price and availability indicators.
Add product-detail navigation.
Test the catalogue and product display.
### View laptop details

As a student, I want to view the specifications and condition of a refurbished laptop so that I can determine whether it supports my academic work.

The page displays the model and relevant specifications.
The price and availability are visible.
The condition or refurbishment information is presented.
The user can return to the catalogue.
Missing product information is handled correctly.
Tasks
Create the product-detail layout.
Retrieve the selected product.
Display specifications and price.
Display condition and availability.
Add back navigation.
Test valid and invalid product selections.
### Request a quotation

As a student, I want to request a quotation so that I can understand the likely cost before committing to a repair or upgrade.


The quotation form records customer and device details.
The user can select or describe the required service.
The form validates compulsory information.
A successful request is confirmed.
The quotation request can be retrieved by the team.
Tasks
Design the quotation form.
Add service-selection options.
Add problem-description fields.
Implement validation.
Store the quotation request.
Test submission and retrieval.
### Manage repair requests

As an authorised team member, I want to view and update repair requests so that customers receive accurate progress information.


Authorised users can view submitted repair requests.
A request can be opened individually.
The status can be updated.
Invalid updates are rejected.
Changes are stored and displayed correctly.
Tasks
Create the request-management page.
Display submitted requests.
Add request-detail functionality.
Add status-update controls.
Save status changes.
Test authorised and invalid operations.
### Manage laptop inventory

As an authorised team member, I want to add and update refurbished laptops so that the website shows accurate inventory.

A laptop record can be created.
Existing laptop information can be updated.
Availability can be changed.
Required values are validated.
Changes appear in the customer-facing catalogue.
Tasks
Create the inventory-management form.
Add create and update operations.
Add validation.
Connect the feature to inventory data.
Refresh the catalogue after a change.
Test create, update and availability operations.
### Contact PC Revival

As a visitor, I want to find clear contact information so that I can ask for assistance.

Contact information is easy to locate.
The user can send an enquiry through the available method.
Required enquiry information is validated.
A confirmation message is displayed.
The page does not expose unnecessary personal information.
Tasks
Design the contact section.
Add the enquiry form or approved contact method.
Implement validation.
Add a confirmation response.
Test the contact process.
