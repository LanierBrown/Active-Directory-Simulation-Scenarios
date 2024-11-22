
![Screenshot 2024-11-17 125808](https://github.com/user-attachments/assets/d6243ef9-85c2-41b3-9ed6-08a93f2ed0c6)
# Active Directory Simulation Scenarios


### 1️⃣ **Creating a New User Account**
   **Scenario**: A new employee has joined the company and needs an account to access systems and resources.

   **Steps**:
   1. Open **Active Directory Users and Computers (ADUC)**.
      
![Screenshot 2024-11-22 124959](https://github.com/user-attachments/assets/d7c76a86-e01e-4f65-93c4-9a98a56ba5bf)

![Screenshot 2024-11-22 125216](https://github.com/user-attachments/assets/d9cebfd1-d683-4842-9d91-6dc729411c04)

      
   3. Navigate to the appropriate **Organizational Unit (OU)** (e.g., "Employees" or "New Hires").

![Screenshot 2024-11-22 135524](https://github.com/user-attachments/assets/9d5c47b9-e71e-4961-b203-2d2aa3901522)

      
   4. Right-click and select **New > User**.
      
![Screenshot 2024-11-22 135754](https://github.com/user-attachments/assets/025e9c1e-890a-4bb2-8bb0-f10e23ac6806)

      
   6. Fill in the user's details:
      - **First Name**, **Last Name**, and **Username** (e.g., `jdoe`).
        
![Screenshot 2024-11-22 135935](https://github.com/user-attachments/assets/f59e20d1-58f1-4707-8e34-87480faffdac)

      
   7. Set a temporary password and check the option for **"User must change password at next logon"**.
      
![Screenshot 2024-11-22 140156](https://github.com/user-attachments/assets/f7417d04-21a8-4358-a92a-48c9caae4faf)

      
   9. Click **Finish** to create the user account.

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
   2. Search for the user by name or username using the **Search bar**.
   3. Right-click the user account and select **Reset Password**.
   4. Enter a new temporary password (must meet your organization’s password policy).
   5. Check the box for **"User must change password at next logon"**.
   6. Communicate the temporary password to the user and instruct them to change it upon logging in.

   **Verification**:
   - Ask the user to log in and confirm they can reset their password.

---

### 3️⃣ **Unlocking a User Account**
   **Scenario**: A user has been locked out of their account due to multiple incorrect login attempts.

   **Steps**:
   1. Open **Active Directory Users and Computers (ADUC)**.
   2. Search for the user account in the **Search bar**.
   3. Right-click the account and select **Properties**.
   4. Navigate to the **Account** tab.
   5. Uncheck the box for **"Account is locked out"** if selected.
   6. Click **OK** to save the changes.


      ## 🎉 Conclusion
These scenarios are foundational for any IT Help Desk technician. Mastering these tasks ensures you can efficiently manage common Active Directory requests.
