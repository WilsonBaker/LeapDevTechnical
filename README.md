# Postman Instructions for Task 2
I have completed Task 2 using Postman collections. In order to run these collections you will need to first either:
- [Download](https://www.postman.com/downloads/) Postman
- Use the [web version](https://www.postman.com/) of Postman
## Import collection and environment
Now you have Postman, you will need to download the two files located in this repository named:
- **CRUD_Tests.postman_collection.json**
- **CrudCrud.postman_environment.json**

You will need to import these two files into Postman, instructions on how to import data files can be found [here](https://learning.postman.com/docs/getting-started/importing-and-exporting/importing-data/)

After importing you should see a new collection and a new environment added.

**Make sure your environment is set to CrudCrud in the top right**

## Re-set environment variable for CrudCrudID
Since the unique ID given by CrudCrud expires after 24 hours, you will need to grab a new one and set it in the environment variables.
Go to the [CrudCrud site](https://crudcrud.com/) and it should provide you with a unique ID
This ID is the string at the end of the URL

So if you loaded the page and copied the URL presented as:
https://crudcrud.com/api/260b1c53645f40339e7468ca6d34815a
Then the ID would be everything that follows after **...api/** (i.e 260b1c53645f40339e7468ca6d34815a)

Now copy and paste that ID into the value for CrudCrudID in the environment you just imported
## Run collection
Once you have the collection downloaded and your environment set correctly, you can run the collection to get the test results.
This is done by using the collection runner. Instructions on that can be found [here](https://learning.postman.com/docs/collections/running-collections/intro-to-collection-runs/)
Using the default settings for collection runner should be sufficient.
