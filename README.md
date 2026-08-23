# Ex--10-IAM-working-overview

### Name: Naveen Kumar S

### Reg No: 212224040214

### Aim

**\*\*To explore and configure AWS Identity and Access Management (IAM) users, groups, and policies, and to verify permissions for accessing Amazon S3 and Amazon EC2 resources.\*\***

### Procedure

1\. Start the AWS Lab and open the **\*\*AWS Management Console\*\***.

2\. Open **\*\*IAM → Users\*\*** and verify \`user-1\`, \`user-2\`, and \`user-3\`.

3\. Open **\*\*User groups\*\*** and verify the groups **\*\*S3-Support, EC2-Support, and EC2-Admin\*\*** and their attached policies.

4\. Add:

\* \`user-1\` → **\*\*S3-Support\*\***

\* \`user-2\` → **\*\*EC2-Support\*\***

\* \`user-3\` → **\*\*EC2-Admin\*\***

5\. Open the IAM **\*\*Sign-in URL\*\*** and sign in as each user using the given lab credentials.

6\. Test \`user-1\`: verify **\*\*S3 read-only access\*\*** and confirm **\*\*EC2 access is denied\*\***.

7\. Test \`user-2\`: verify **\*\*EC2 read-only access\*\*** and confirm that stopping the \`LabHost\` instance is denied; verify **\*\*S3 access is denied\*\***.

8\. Test \`user-3\`: open **\*\*EC2\*\***, select \`LabHost\`, and **\*\*stop the instance\*\*** successfully.

9\. Submit the lab and check the **\*\*Grades/Submission Report\*\***.

10\. End the lab after completing all tasks.

### Output

**IAM Users**

<img width="1889" height="884" alt="Screenshot 2026-08-23 225716" src="https://github.com/user-attachments/assets/b1f8320f-a65f-43c7-afa6-02ed805ae2b6" />




**EC2-Admin Policy**

<img width="1880" height="908" alt="Screenshot 2026-08-23 230344" src="https://github.com/user-attachments/assets/6800c3ab-3dad-487f-b327-6fec3320c3ef" />




**EC2-Support Policy**
<img width="1919" height="913" alt="Screenshot 2026-08-23 230407" src="https://github.com/user-attachments/assets/90410e45-3e97-4ba8-b111-666e8ff78aed" />




**S3-Support Policy**

<img width="1903" height="871" alt="Screenshot 2026-08-23 230450" src="https://github.com/user-attachments/assets/e458a8fd-7ac9-4fb4-8572-ff4c730b8479" />




**user-1 Added to S3-Support**

<img width="1917" height="921" alt="Screenshot 2026-08-23 230714" src="https://github.com/user-attachments/assets/5c9151aa-9484-4121-be0c-a1524ccdcd0a" />




**user-2 Added to EC2-Support**

<img width="1916" height="921" alt="Screenshot 2026-08-23 230825" src="https://github.com/user-attachments/assets/804715ee-239d-4625-9eab-c57da09ce097" />




**user-3 Added to EC2-Admin**

<img width="1909" height="925" alt="Screenshot 2026-08-23 230958" src="https://github.com/user-attachments/assets/8f9791de-7183-411b-9d3d-407feecf4e8d" />




**S3 Access Using user-1**

<img width="1908" height="996" alt="Screenshot 2026-08-23 231716" src="https://github.com/user-attachments/assets/e253fe90-eee0-4922-848f-4ca816b9de10" />




**EC2 Access Denied for user-1**

<img width="1919" height="940" alt="Screenshot 2026-08-23 231907" src="https://github.com/user-attachments/assets/7545a73a-45b5-4888-9a13-56280b813a8c" />




**EC2 Read-Only Access Using user-2**

<img width="1881" height="943" alt="Screenshot 2026-08-23 232143" src="https://github.com/user-attachments/assets/4ba92313-0936-49f8-bd7a-25d5fffa8537" />




**EC2 Stop Permission Denied for user-2**

<img width="1916" height="945" alt="Screenshot 2026-08-23 232157" src="https://github.com/user-attachments/assets/fc134572-e059-47e6-9ad7-8563c315604a" />




**EC2 Instance Successfully Stopped Using user-3**

<img width="1906" height="936" alt="Screenshot 2026-08-23 232525" src="https://github.com/user-attachments/assets/b7a7715a-755e-4d36-91a8-10810618ff33" />


### Result

The IAM users were successfully assigned to their respective groups, and the required permissions were verified. \`user-1\` received S3 read-only access, \`user-2\` received EC2 read-only access, and \`user-3\` received EC2 administrative access to start/stop instances. Thus, IAM users, groups, policies, and permissions were successfully explored and tested.
