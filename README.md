# SureTriggers and Mocean Integration Documentation

## Contents

1. Login to your SureTriggers account.

2. Go to the `Apps` section visible on the left side.

3. Click on `Create New Connection`

4. Search for Mocean and select it.

5. Give a name to the connection and paste the API key and secret.
![image1](https://github.com/user-attachments/assets/369e2525-619d-4829-a982-79703bccd827)

Step 7: Click on `Connect Mocean`.

![image2](https://github.com/user-attachments/assets/0ab9c545-11b9-49ce-81ca-ba2f0277ed26)

You can view your connection by clicking on the Mocean app visible under `Apps` in SureTriggers. As shown in the above image.

Now that we have connected Mocean and SureTriggers lets jump in and start building.

1. Login to SureTriggers, go to the `Workflows` section and click `Create Workflow` and select `Create from scratch`.

2. Give a name to the workflow and click create.

3. Adding a trigger<br>
Note: We have used Google Form as trigger, but user can choose their own trigger depending on use case
- Click on `Add Trigger`, search for `Google Forms` and select it.
- Under `Select Event` select `New Form Responses`.
- Under `Select Connection` select `Create New Connection`. 
- Choose the Google account from which the form can be accessed.
- Click on `Continue`.
- Create a google form and copy paste the form edit link.<br>
Note: The URL which is visible while creating the form is the edit link.
- Under Test Connection & Data click on `Fetch Data`.
![image](https://github.com/user-attachments/assets/f03a7f4e-9e5a-4a00-a6f8-9c5e39b8660e)
- Click `Save`

4. Add action
- Click on plus button and search for Mocean.

SureTriggers integration with Mocean allows you to:
- Send SMS
- Send code over SMS
- Fetch balance

### Send SMS
- Under `Event` select `Send SMS`.
- Click on `Continue`.
- Enter sender name, receiver number and text message.
- Click on `Continue`.
- Click on `Test Action`, a SMS will be sent to be the receiver phone.
![image](https://github.com/user-attachments/assets/15b3c5d1-0f8e-4148-b659-f7656a1a5bee)
- Click `Save`

