# Gmail Trash Removal
Project is to automate the process of removing trash from Gmail. I had the Trash folder very piled up and this annoys me.

## Setup
Here are the setup steps needed for myself. It is assumed Go has been installed and you are familar with using it.
1. Setup a quickstart <https://developers.google.com/gmail/api/quickstart/go> this should walk through beggining the project. 
2. <https://pkg.go.dev/google.golang.org/api/gmail/v1> should have the needed information to beggin working on the trash removal.
3. Create a private Github repository for it. ( Finished )

## Plan
There needs to be some thought put into planning this out. 

Should be simple enough. Check time. Remove trash.

For the Second step we may have to use HTTP Requests. Not yet seen a natural go method for batchDelete.

### Steps
- First
  Gain the IDs needed.

- Second
  Send the batchDelete request.

### References
Gmail App Icon by moein moradi from Pexels.
