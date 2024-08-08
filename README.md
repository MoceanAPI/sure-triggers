# SureTriggers and Mocean Integration Documentation

## Contents
- [Connect SureTriggers and Mocean](#connect-suretriggers-and-mocean)
- [Creating workflow](#creating-workflow)
- [Adding a trigger](#adding-a-trigger)
- [Adding an action](#adding-an-action)
  - [Send SMS](#send-sms)
  - [Send Code over SMS](#send-code-over-sms)
  - [Fetch Balance](#fetch-balance) 

### Connect SureTriggers and Mocean
1. Login to your SureTriggers account.

2. Go to the `Apps` section visible on the left side.

3. Click on `Create New Connection`

4. Search for Mocean and select it.

5. Give a name to the connection and paste the API key and secret.
![image1](https://github.com/user-attachments/assets/369e2525-619d-4829-a982-79703bccd827)

6. Click on `Connect Mocean`.

![image2](https://github.com/user-attachments/assets/0ab9c545-11b9-49ce-81ca-ba2f0277ed26)

You can view your connection by clicking on the Mocean app visible under `Apps` in SureTriggers. As shown in the above image.

### Creating workflow
1. Login to SureTriggers, go to the `Workflows` section and click `Create Workflow` and select `Create from scratch`.

2. Give a name to the workflow and click create.

### Adding a trigger
Note: We have used Google Form as trigger, but user can choose their own trigger depending on use case
1. Click on `Add Trigger`, search for `Google Forms` and select it.
   
2. Under `Select Event` select `New Form Responses`.
  
3. Under `Select Connection` select `Create New Connection`.

4. Choose the Google account from which the form can be accessed.

5. Click on `Continue`.

6. Create a google form and copy paste the form edit link.<br>
Note: The URL which is visible while creating the form is the edit link.

7. Under Test Connection & Data click on `Fetch Data`.
![image](https://github.com/user-attachments/assets/f03a7f4e-9e5a-4a00-a6f8-9c5e39b8660e)

8. Click `Save`

### Adding an action
1. Click on plus button and search for Mocean.

SureTriggers integration with Mocean allows you to:
- Send SMS
- Send Code over SMS
- Fetch balance

#### Send SMS
- Under `Event` select `Send SMS`.
- Click on `Continue`.
- Enter sender name, receiver number and text message.
- Click on `Continue`.
- Click on `Test Action`, a SMS will be sent to be the receiver phone.
![image](https://github.com/user-attachments/assets/15b3c5d1-0f8e-4148-b659-f7656a1a5bee)
- Click `Save`
- Click on `Publish`, to change status to `Active`.

![image](https://github.com/user-attachments/assets/a06958b3-a32c-45c0-a828-7e801720d37e)

#### Send Code over SMS
- Under `Event` select `Send Code over SMS`.
- Click on `Continue`.
- Enter brand name, receiver number, sender name, code length and pin validity.
- Click on `Continue`.
- Click on `Test Action`, a code will be sent to be the receiver phone.
- Click `Save`
- Click on `Publish`, to change status to `Active`.
![image](https://github.com/user-attachments/assets/e98ee4f0-adbd-46ad-8476-afdca010997b)

#### Fetch Balance
- Under `Event` select `Fetch Balance`.
- Click on `Continue`.
- Click on `Test Action`, it will return your account balance.
![image](https://github.com/user-attachments/assets/2b1e90fb-d517-4899-a318-d43383fbe0c4)
- Click `Save`
- Click on `Publish`, to change status to `Active`.
![image](https://github.com/user-attachments/assets/c7d0e91d-e5b5-45a0-9eab-b5a5e46a6bda)




