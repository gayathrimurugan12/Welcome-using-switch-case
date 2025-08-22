# Aim:
To get a user’s name as input and display a personalized welcome message using a Switch Case activity in UiPath. If the name is "RAM", display "Welcome Mr. Ramachandran"; otherwise, display "Welcome <Given Name>". Different messages can be added for other specific names using the Switch Case.

# Procedure:
1.Open UiPath Studio and create a new Sequence.
2.Use an Input Dialog Activity:
3.Title: Enter Name
4.Label: Please enter your name
5.Add a Switch Activity:
6.TypeArgument: String
7.Define Cases in Switch:
8.Case "RAM" → Use a Message Box Activity: "Welcome Mr. Ramachandran"
9.Default Case → Message Box: "Welcome " + userName
10.Run the Workflow and test with different names to see the corresponding messages.
# output:
<img width="1920" height="1080" alt="Screenshot (39)" src="https://github.com/user-attachments/assets/80dc534f-87cd-42ec-bc74-262e93551555" />
<img width="1920" height="1080" alt="Screenshot (7)" src="https://github.com/user-attachments/assets/0804f398-bd0c-44df-943f-18525cae1468" />
<img width="1920" height="1080" alt="Screenshot (37)" src="https://github.com/user-attachments/assets/2c0e11c9-21db-4bad-88f4-427d9fa14191" />
<img width="1920" height="1080" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/6a473cb2-47d2-4f70-ac9e-61df66df1d86" />
<img width="1920" height="1080" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/6a09a92d-dffd-4c03-b91c-9182890d717f" />
<img width="1920" height="1080" alt="Screenshot (35)" src="https://github.com/user-attachments/assets/3d62486d-61e7-4fd8-9ea4-c6948069c0f9" />







# Result:
The UiPath workflow successfully demonstrates how to take user input and display a personalized message using the Switch Case activity.
