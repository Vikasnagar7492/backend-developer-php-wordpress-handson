# Backend Developer (PHP, WordPress) Handson

## Instructions

```
1. Create a new PRIVATE Github repository.  Type in your email in the README in your private repo for understanding.  Add "idteam-at-onecom" as a collaborator.
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
    - Create a main PHP file inside the folder and add the plugin header information.
2. **Register Custom Namespace for REST APIs**
    - Use the  register\_rest\_route function to create a custom namespace.
    - Define the routes for data submission and retrieval.
3. **Implement Authentication Mechanism**
    - create a custom authentication handler (an authentication plugin can be used to reduce development time)
    - Ensure that authentication is required to access the APIs.
4. **Handle Form Submission**
    - Create an endpoint to receive form data from a form/API call
    - Validate the incoming data for required fields and correct format.
5. **Data Validation and Storage**
    - On successful validation, store the data in a custom database table along with required database constraints.
    - Do not use the default $WPDB object for DB queries use custom queries instead. Make sure the queries should be secure.
    - Provide appropriate error messages for validation failures.
6. **Fetch Stored Data**
    - Create an endpoint to fetch the stored data.
    - Ensure that only authenticated requests can access the data.
7. **Testing**
    - Test the endpoints using tools like Postman.
    - Ensure data is correctly validated, stored, and retrieved as per the specifications.
8. **Documentation**
    - Provide clear documentation for the APIs, including endpoint URLs, required parameters, and sample requests and responses.
  
9. **Submission:**
    - **Code Repository**: Push your project to a GitHub repository you own, and add  idteam-at-onecom as a collaborator in that repo.
    - **Live Demo**: Live demo during the panel interview
    - **README**: Include a README file in your repository with:
      - A brief description of your project.
      - Instructions on how to run the project locally.
      - Are there any additional notes or features you implemented?
     
10. **Requirements**
    - Please make an effort to use custom PHP code instead of relying on WordPress built-in functions whenever it's feasible.
    - Auth mechanisms are required like Basic auth/JWT do not use is_user_logged_in()



## FAQs

Q: Where do I have to solve the assignment?

A: Implement it on your local system or use any virtual server on the cloud/VPS, etc. We will need this system again during the panel interview, so do not destroy your work.

Q: Do I have to use a particular operating system?

A: It is up to you to choose operating system of your choice.

Q: Can I make the repository public?

A: No, you should not do that.

Q: Can I purge stuff on my system once changes are pushed to repo?

A: No, you should not do that. If you are selected for the panel interview, then the panel will ask you to show it live.
