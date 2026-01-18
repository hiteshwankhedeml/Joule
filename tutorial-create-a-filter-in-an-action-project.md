# 🟢 Tutorial: Create a Filter in an Action Project

<mark style="color:purple;background-color:purple;">**Step 1: Copy action project for BusinessPartner service**</mark>

* Build Lobby ⇒ Connectors ⇒ Actions
* Select the Project ⇒ Save as New Project ⇒ Enter name and description
* In the Input fields ⇒ Select Add New Fields ⇒ Key = FirstName
* &#x20;<mark style="color:purple;background-color:purple;">**In the Filters enter FirstName**</mark>
* Test
* Release ⇒ Publish
*

    <figure><img src=".gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

<mark style="color:purple;background-color:purple;">**Step 2: Create a Joule Skill**</mark>

* Build Lobby ⇒ Create ⇒ New Project ⇒ Joule Skill
* Enter name and description ⇒ Create ⇒ Joule Skill
* Trigger ⇒ Side Panel ⇒ Enable Joule to generate a response
* Parameters ⇒ Skill Inputs ⇒ Configure
* Add ⇒ First Name ⇒ Required
*

    <figure><img src=".gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>
* Output:
*

    <figure><img src=".gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

<mark style="color:purple;background-color:purple;">**Step 3: Add Action to Joule Skill**</mark>

* Choose the **+**.
* Add Call Actions
* Select the action copied earlier
* Select destination
* Skill content ⇒ Field mapping

<mark style="color:purple;background-color:purple;">**Step 4: Configure End**</mark>

* End element
* Skill Content ⇒ Choose the employee list

<mark style="color:purple;background-color:purple;">**Step 5: Release and Deploy**</mark>

* Release
* Deploy

<mark style="color:purple;background-color:purple;">**Step 6: Test Joule skill**</mark>

* Choose the Joule tab from the Environment

