# InterConnecta Development Challenge
InterConnecta's Development challenge for the Junior Developer position. Oriented to test an applicant's experience with HTML, JavaScript, and Data Handling.

## Scenario
You're working with a medium sized, international business located in the US. They already use [Zoho CRM](https://www.zoho.com/crm/) to manage their customers and keep track of new prospect companies. Now that their website has gained more presence, they want to use it to capture new prospects. They receives dozens of requests every week and it is too time consuming to sort through requests that have invalid data.

You're given a plain HTML form generated via [Zoho CRM's Webforms](https://www.zoho.com/crm/web-forms.html). The form is already connected to their system and can receive new requests. Your job is to use web technologies available to guarantee that:
- All required fields are filled in
- Data is entered in the proper format
- Additional information is captured without input of the user

Adapt the form to meet the requirements listed below. The challenges will get more difficult as you progress. You can use any web technology available but keep best practices in mind at all times.

Once testing is completed, any information that makes it into the CRM with an incorrect format will be considered invalid by the customer.

## Form Requirements
1. Make the following fields required:
    + `First Name`
    + `Last Name`
    + `Company`
    + `Email`
    + `Zip Code`
    + `Country`
    + Set default `Country` value to United States
    + `Description`
2. Perform the following form validations:
    + `Email`
        * Allow only valid email address formats (e.g.: my.valid-email_123@example.com)
        * Prevent well known public addresses (e.g.: @hotmail.com, @aol.com, @gmail.com, etc.)
    + If `Industry` = Other
        * Show `Other Industry` field
        * `Other Industry` is required
    + If `Country` = United States
        * `Zip Code` is required
        * `Phone` in US format (i.e.: 999-999-9999)
    + If `Country` != United States
        * Zip Code NOT required
        * Allow `Phone` to be entered in any format
    + If `Industry` != Other
        * Hide `Other Industry` field
3. Prefill hidden information
    + `Source`: Prefill with default value "Web"
    + `Source Detail`: Prefill with web page Title
    + `Source URL`: Prefill with web page URL
    + `Request Date`: Prefill with today's date in mm/dd/yyyy format
    + `Browser User Agent`: Prefill with browser's User Agent
    + `IP Location`: Prefill with user's IP address

## Evaluation Criteria
Additionally, we'll evaluate your work based on the following criteria:
- Programming best practices
- Usage of latest technologies
- Appropriate usage of libraries & frameworks
- Code cleanliness, organization & comments
- Design & presentation
