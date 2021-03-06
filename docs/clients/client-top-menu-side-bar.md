---
sidebar_position: 1
---

# Top Menu Contents and Sidebar Contents

Client's top menu consists of "Create New Client", "View Audit History", "Edit", "Archive" and "Delete" buttons.

![Alt text](/img/client/client_initial.png?raw=true "Client page with top pop-up menu and no client selected")

Client page with top pop-up menu and no client selected

## Creating a Client

If the "Create New Client" button is clicked, a modal will show up which will ask for the new client's details. The client creation form has four parts, "Info", "Postal Address", "Billing Address" and "Payment Settings". Each part will be covered in the follwing content. There is something important to note here, if there is an asterisk(*) beside the field name it means you must fill relevant data in that field and that field must not be empty.

### Info

There are two types of clients, company and person, that can be entered. 

The main differences in entering data for company and person types are the top three fields. For the company type clients, the top three fields would be "Company Name", "Tax Registered" and "Business Registration Number", and for the person type clients, they are "ID Card Number", "ID photo" and "Date of Birth".

![Alt text](/img/client/client_create_form.png?raw=true "Create Client Form with all accordions closed")

Create Client Form with all accordions closed

![Alt text](/img/client/client_create_form_info_company.png?raw=true "Create Client Form with the top part of info accordion for the company type client")

Create Client Form with the top part of info accordion for the company type client

![Alt text](/img/client/client_create_form_info_person.png?raw=true "Create Client Form with the top part of info accordion for the person type client")

Create Client Form with the top part of info accordion for the person type client

The info part of create client form also contains "Client ID", which is automatically generated after saving, "Salutation", "First Name", "Last Name", "Email", "Mobile", "Created By", "Referred By" and "Date Created", all of which must be filled. "Fax", "Phone" and "Notes", which is for adding any additional information related to the client needed to be entered.

![Alt text](/img/client/client_create_form_info.png?raw=true "Client")

Create Client Form with the lower part of info accordion for the person type client

### Postal Address

The next part of create client form is "Postal Address" which consists of five mandatory fields "Address 1", "City", "State", "Postal Code" and "Country", and an optional field, "Address 2".

![Alt text](/img/client/client_create_form_postal_address.png?raw=true "Client")

Create Client Form with the postal address accordion

### Billing Address

Billing Address can be the same as postal address so if the check box telling "Billing address is same as above" is ticked, postal address does not need to be entered again. If the check box is not checked, you need to provide information for billing address. The fields are the same as postal address part. Both of the scenarios can be seen in the following pictures.

![Alt text](/img/client/client_create_form_billing_address.png?raw=true "Client")

Create Client Form with the billing address accordion

![Alt text](/img/client/client_create_form_billing_address_payment_settings.png?raw=true "Client")

Create Client Form with the billing address accordion

### Payment Settings

Payment Settings has fields such as "Select Payment Terms", "Select Billing Terms" and "Yearly Interest Rate". The options available for "Select Payment Terms" are "7 Days", "15 Days", "30 Days", "45 Days", "60 Days", "90 Days", "Contingent Fee Agreement" and "Due Upon Receipt".

![Alt text](/img/client/client_create_form_payment_settings_payment_term_options.png?raw=true "Client")

Create Client Form's payment setting accordion with payment term options

The options available for "Select Billing Terms" are "Monthly" and "On Case Completion".

![Alt text](/img/client/client_create_form_payment_settings_billing_term_options.png?raw=true "Client")

Create Client Form's payment setting accordion with billing term options

## Viewing audit history

If you click "View Audit History" from the top menu, a list of actions taken on the client's records along with the person who did that will show up. The actions can be creat, update, archive and unarchive.

![Alt text](/img/client/client_view_audit.png?raw=true "Client")

Client's audit history

## Updating a Client

Edit button will be disabled if no client is selected as it appears in the picture of top menu introduction section. If the "Edit" button from the top menu is clicked, a form filled with selected client's details will show up and those fields can be edited and then saved. All the fields of update form are the same as create form so edit form will not be broken down in details in this section.

![Alt text](/img/client/client_update.png?raw=true "Client")

Client update form auto-filled with existing information

## Archiving a Client
Archiving a client does not delete the client permanently. It is more like a soft delete and the archived data, which can be client, case or invoices, can be retrieved back by unarchiving. 

### Showing archived Client list

![Alt text](/img/client/client_side_setting_button.png?raw=true "Client")

Buttons popping up after the setting icon has been clicked from the side bar

![Alt text](/img/client/client_side_setting_show_archived_on.png?raw=true "Client")

Archived clients set to be shown in the list

## Deleting a Client
Unlike archiving, deleting clients cannot be undone.

## Searching through Client list

Keywords typed into the search box are searched through client's details such as note, client id, company name, first name, last name and full name. If the keywords match any of the above mentioned fields, the side client list will only show the related clients.

## Sorting Client list

Default sorting is the sorting of clients by chronological order.

![Alt text](/img/client/client_side_setting_sort_default.png?raw=true "Client")

Client Default Sorting

![Alt text](/img/client/client_side_setting_sort_options.png?raw=true "Client")

List of fields by which clients can be sorted

![Alt text](/img/client/client_side_setting_sort_firstname.png?raw=true "Client")

Sorting by ascending or descending

## Creating a Client from side bar

By clicking the small add icon in the side bar, clients can be created.

![Alt text](/img/client/client_create_add_icon.png?raw=true "Client create icon in side bar")

Client create icon in side bar