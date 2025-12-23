# Tutorial: Use Joule Studio to Create and Deploy a Joule Skill

<mark style="color:purple;background-color:purple;">**Step 1: Create a Joule Skill**</mark>

* Build Lobby ⇒ Create ⇒ Joule Skill ⇒ Enter Project Name and Description
* Once Project created ⇒ Select the Project ⇒ Create ⇒ Joule Skill
* Enter skill name and description
* <mark style="color:$danger;background-color:purple;">**The description is important because Joule will use it to identify the correct skill to select during a conversation.**</mark>
*

    <figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>
*

    <figure><img src=".gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

<mark style="color:purple;background-color:purple;">**Step 2: Define the Input and Output Parameters**</mark>

* Select the trigger ⇒ Side panel will open
* Disable Allow Joule to generate a response. (If we do this then we have to use "Send Message" step to configure the response)
* Skill Inputs ⇒ Configure ⇒ Add inputs
*

    | Name              | Description        | Required |
    | ----------------- | ------------------ | -------- |
    | **`EmployeeID`**  | **`Employee ID`**  | select   |
    | **`Status`**      | **`Status`**       |          |
    | **`CommunityID`** | **`Community ID`** |          |
* Skill Outputs ⇒ Configure ⇒ Add inputs
*

    | Name                | Description         | Type       | Required |
    | ------------------- | ------------------- | ---------- | -------- |
    | **`Badge`**         | **`Badge`**         | **Number** | select   |
    | **`Employee ID`**   | **`Employee ID`**   | **String** | select   |
    | **`Employee Name`** | **`Employee name`** | **String** | select   |
* Save&#x20;
* In Design Console ⇒ We will be able to see the errors

<mark style="color:purple;background-color:purple;">**Step 3: Add First Action**</mark>

* Choose the **+** between **Trigger** and **End**.
*

    <figure><img src=".gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>
* Select the action created earlier
* Select the destination
* Select the destination variables
* In Skill Content we map the fields with the actions

<mark style="color:purple;background-color:purple;">**Step 4: Add 2nd action**</mark>

<mark style="color:purple;background-color:purple;">**Step 5: Define the Send Message**</mark>

* Choose the **+** between the second action and the **End** element.
* Select send message
* Open message editor
* Select message type ⇒ Illustrated message
* Enter text, dynamic fields from skill will be in <>
* We can also select Add button ⇒ Enter URL to be opened on click of the button ⇒ Save

<mark style="color:purple;background-color:purple;">**Step 6: End Configuration**</mark>

<mark style="color:purple;background-color:purple;">**Step 7: Release and Deploy**</mark>

* Release
* Deploy ⇒ Select the environment

<mark style="color:purple;background-color:purple;">**Step 8: Test in Standalone Assistant**</mark>

* Build Lobby ⇒ Control Tower ⇒ Environment ⇒ Joule
* Enter the text here and test
