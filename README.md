# postman-collections

This repository is a collection of example queries for the Pivotal Tracker v5 API formatted for the Postman rest client.

The Pivotal Tracker v5 API is documented here -- http://www.pivotaltracker.com/help/api/rest/v5

You can get Postman as a Chrome extension from

  https://chrome.google.com/webstore/detail/postman-rest-client/fdmmgilgnpjigdojojpjoooidkmcomcm

or as a packaged app from

  https://chrome.google.com/webstore/detail/postman-rest-client-packa/fhbjgbiflinjbdggehcddcbncdddomop

Once you're in Postman (either the Chrome extension or the packaged app), import the collection by:

1.  Click Import.
2.  Choose Tracker-v5-API-examples.json.postman_collection from where ever you cloned this repository.
3.  Either import as a new collection or overwrite an existing collection.

Postman is well documented, so please refer to the Postman documentation for instructions on how to use collections.

We have also provided an example environment, which includes most of the variables in the queries.  

To import the example environment, go to Manage Environments in Postman and import the environment.  Update the values 
as needed, especially the token.

If you receive an unauthorized response, please update the X-TrackerToken header value or the {{token}} value in the 
example environment with your Tracker API token.  You can find your Tracker API token on your Profile page after 
logging into Tracker.




