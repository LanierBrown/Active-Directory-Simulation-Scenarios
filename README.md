
![Screenshot 2024-11-17 125808](https://github.com/user-attachments/assets/d6243ef9-85c2-41b3-9ed6-08a93f2ed0c6)
# Active Directory Simulation Scenarios


### 1️⃣ **Creating a New User Account**
   **Scenario**: A new employee has joined the company and needs an account to access systems and resources.

   **Steps**:
   1. Open **Active Directory Users and Computers (ADUC)**.
   2. Navigate to the appropriate **Organizational Unit (OU)** (e.g., "Employees" or "New Hires").
   3. Right-click and select **New > User**.
   4. Fill in the user's details:
      - **First Name**, **Last Name**, and **Username** (e.g., `jdoe`).
   5. Set a temporary password and check the option for **"User must change password at next logon"**.
   6. Click **Finish** to create the user account.

   **Verification**:
   - Ensure the new account appears in the correct OU.
   - Test the credentials with the new user.

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
