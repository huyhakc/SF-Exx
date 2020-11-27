# SF-Exx
Task 1:
When creating a contact for an account, automatically trigger an approval process to approve contact (mean auto submit and approve).
After approving successfully, set active flag of contact into true and increase total contacts on Account by 1.
If deactive contact, decrease total contacts on Account by 1.
Task 2:
https://home70-dev-ed--c.visualforce.com/apex/task2
Task 3:
https://home70-dev-ed--c.visualforce.com/apex/task3
Task 4: 
- Use https://workbench.developerforce.com/ to test or using curl command
URI: /services/apexrest/Contact/
The format of request body (json file):
{
"data":
	[
		{
		  "Id" : "0035g000001YDTxAAO",
		  "Birthdate" : "1968-11-04",
		  "Email" : "test1-rose@edge.com",
		  "Title" : "SVP, Procurement",
		  "Department": "Procurement"
		},
		{
		  "Id" : "0035g000001YDTyAAO",
		  "Birthdate" : "1947-08-03",
		  "Email" : "test2-sean@edge.com",
		  "Title" : "CFO",
		  "Department": "Finance"
		}
	]
}
