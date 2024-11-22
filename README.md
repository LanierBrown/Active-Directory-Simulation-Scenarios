
![Screenshot 2024-11-17 125808](https://github.com/user-attachments/assets/d6243ef9-85c2-41b3-9ed6-08a93f2ed0c6)
# Active Directory Simulation Scenarios


### 1️⃣ **Creating a New User Account**
   **Scenario**: A new employee has joined the company and needs an account to access systems and resources.

   **Steps**:
   1. Open **Active Directory Users and Computers (ADUC)**.
      
![Screenshot 2024-11-22 124959](https://github.com/user-attachments/assets/d7c76a86-e01e-4f65-93c4-9a98a56ba5bf)
  - Active Directory can be opened through the service manager under (Tools) 

![Screenshot 2024-11-22 125216](https://github.com/user-attachments/assets/d9cebfd1-d683-4842-9d91-6dc729411c04)
  - Active Directory can also be opened through the search bar, next to the Windows button
      
   2. Navigate to the appropriate **Organizational Unit (OU)** (e.g., "Employees" or "New Hires").

![Screenshot 2024-11-22 135524](https://github.com/user-attachments/assets/9d5c47b9-e71e-4961-b203-2d2aa3901522)

      
   3. Right-click and select **New > User**.
      
![Screenshot 2024-11-22 135754](https://github.com/user-attachments/assets/025e9c1e-890a-4bb2-8bb0-f10e23ac6806)

      
   4. Fill in the user's details:
      - **First Name**, **Last Name**, and **Username** (e.g., `jdoe`).
        
![Screenshot 2024-11-22 135935](https://github.com/user-attachments/assets/f59e20d1-58f1-4707-8e34-87480faffdac)

      
   5. Set a temporary password and check the option for **"User must change password at next logon"**.
      
![Screenshot 2024-11-22 140156](https://github.com/user-attachments/assets/f7417d04-21a8-4358-a92a-48c9caae4faf)

      
   6. Click **Finish** to create the user account.

![Screenshot 2024-11-22 140247](https://github.com/user-attachments/assets/900e7346-b2aa-45f8-b77f-d1003fb45305)


   **Verification**:
   - Ensure the new account appears in the correct OU.
     
![Screenshot 2024-11-22 140414](https://github.com/user-attachments/assets/dd186d46-a9b9-4f92-975c-17de09851239)

    
   - Test the credentials with the new user.
     
![Screenshot 2024-11-22 140606](https://github.com/user-attachments/assets/7c1343c2-d7d6-4a84-a4b5-5506ebbde15d)

![Screenshot 2024-11-22 140752](https://github.com/user-attachments/assets/10daaaec-33fd-4ba6-ad71-91b845db62d9)

---

### 2️⃣ **Resetting a User's Password**
   **Scenario**: A user has forgotten their password and is locked out of their account.

   **Steps**:
   1. Open **Active Directory Users and Computers (ADUC)**.
      
      ![Screenshot 2024-11-22 125216](https://github.com/user-attachments/assets/c6302055-9049-40fb-bee7-dd9bebd8d886)

      
   2. Search for the user by name or username using the **Search bar**.
      
![Screenshot 2024-11-22 140414](https://github.com/user-attachments/assets/51592366-ddeb-4019-aa4b-2f0475d24e10)

    
   3. Right-click the user account and select **Reset Password**.
      
![Screenshot 2024-11-22 142551](https://github.com/user-attachments/assets/cd18fb92-43ce-4359-bda0-69b62d207413)

    
   4. Enter a new temporary password (must meet your organization’s password policy).
      
![Screenshot 2024-11-22 142717](https://github.com/user-attachments/assets/4659100f-e6ad-401e-8a35-9b3f1eda443f)


   5. Check the box for **"User must change password at next logon"**.
       
![Screenshot 2024-11-22 142749](https://github.com/user-attachments/assets/5f754ac1-1c4f-45e6-890b-7e95a0d83426)

      
   6. Communicate the temporary password to the user and instruct them to change it upon logging in.

   **Verification**:
   - Ask the user to log in and confirm they can reset their password.

![Screenshot 2024-11-22 144323](https://github.com/user-attachments/assets/9b7f80a2-299b-44da-8684-045d78919d5d)
  - Sending a text message would not be the first point of contact. We want to contact the Client through The Ticketing System, Email, or even Phone Calls if they are open and available to speak.

---

### 3️⃣ **Adding a User to a Security Group**
   **Scenario**: A user needs access to a shared folder or application, which requires membership in a specific security group.

   **Steps**:
   1. Open **Active Directory Users and Computers (ADUC)**.
      
![Screenshot 2024-11-22 124959](https://github.com/user-attachments/assets/bcdd38c8-669b-4805-9dc4-a93ac634c68f)

      
   3. Search for the user by name or username using the **Search bar**.
      
![Screenshot 2024-11-22 150127](https://github.com/user-attachments/assets/a6f6f934-33e3-46af-b252-d8cf4d9e6f00)

      
   5. Double-click the user account to open their properties.

      ![Screenshot 2024-11-22 150328](https://github.com/user-attachments/assets/a5f0b069-eeb7-46ad-ab20-4a60538c4f17)

   6. Navigate to the **Member Of** tab.

      ![Screenshot 2024-11-22 150435](https://github.com/user-attachments/assets/14383120-ee16-4065-8237-bf3f52dc1f5d)

   7. Click **Add** and search for the required security group (e.g., "Finance Team" or "HR Access").

       ![Screenshot 2024-11-22 150514](https://github.com/user-attachments/assets/d788ad8e-a7a1-46a4-8e8a-4e7bce5456a1)

   8. Select the group and click **OK** to add the user to it.
      
![Screenshot 2024-11-22 150656](https://github.com/user-attachments/assets/7ee4f31d-3780-4873-bbe8-d3a050578088)

       
   9. Confirm the group now appears in the **Member Of** list and click **OK** to save.

       ![Screenshot 2024-11-22 151549](https://github.com/user-attachments/assets/36676fbe-2195-42f4-8d15-56a7806ae43e)


   **Verification**:
   - Inform the user their access should now be available.
   - Test access to the shared folder or application, if possible.

     

---


      ## 🎉 Conclusion
These scenarios are foundational for any IT Help Desk technician. Mastering these tasks ensures you can efficiently manage common Active Directory requests.
