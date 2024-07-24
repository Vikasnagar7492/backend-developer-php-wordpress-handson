# Backend Developer (PHP, WordPress) Handson

## Instructions

```
1. Create a new PRIVATE Github repository.  Add "idteam-at-onecom" as collaborator.
2. Read and understand the questions carefully before attempting them.
3. Record your assumptions about anything in a file for interviewers to consider.
4. This is a CONFIDENTIAL material of one.com and should not be shared with anyone else.
```

## Assignment
**Custom Namespace REST APIs with Authentication in WordPress+PHP**

**Objective**

Create a WordPress plugin to set up a custom namespace for REST APIs. Implement an authentication mechanism for these APIs, handle data submission from a third-party form, validate and store the data, and provide endpoints to fetch the stored data.

**Instructions**

1. **Setup WordPress Plugin**
    - Create a new plugin folder in the  wp-content/plugins directory.
    - Inside the folder, create a main PHP file (e.g.,  custom-api-plugin.php ) and add the plugin header information.
2. **Register Custom Namespace for REST APIs**
    - Use the  register\_rest\_route function to create a custom namespace (e.g.,  custom/v1 ).
    - Define the routes for data submission and retrieval.
3. **Implement Authentication Mechanism**
    - Use WordPress's built-in authentication methods or create a custom authentication handler (an authentication plugin can be used to reduce development time)
    - Ensure that authentication is required for accessing the APIs.
4. **Handle Form Submission**
    - Create an endpoint to receive form data from a form
    - Validate the incoming data for required fields and correct format.
5. **Data Validation and Storage**
    - On successful validation, store the data in a custom database table or as custom post types.
    - Provide appropriate error messages for validation failures.
6. **Fetch Stored Data**
    - Create an endpoint to fetch the stored data.
    - Ensure that only authenticated requests can access the data.
7. **Testing**
    - Test the endpoints using tools like Postman.
    - Ensure data is correctly validated, stored, and retrieved as per the specifications.
8. **Documentation**
    - Provide clear documentation for the APIs, including endpoint URLs, required parameters, and sample requests and responses.


## FAQs

Q: Where do I have to solve the assignment?

A: Implement it on your local system or use any virtual server on cloud/VPS, etc. We will need this system again during panel interview, so do not destroy your work.

Q: Do I have to use a particular operating system?

A: It is up to you to choose operating system of your choice.

Q: Can I make the repository public?

A: No, you should not do that.

Q: Can I purge stuff on my system once changes are pushed to repo?

A: No, you should not do that. If you are selected for the panel interview, then the panel will ask you to show it live.
