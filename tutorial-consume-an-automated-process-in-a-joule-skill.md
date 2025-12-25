# 🟢 Tutorial: Consume an Automated Process in a Joule Skill

<mark style="color:purple;background-color:purple;">**Step 1: Create a Project for the Automated Process**</mark>

* Build Lobby ⇒ Create ⇒ Automated Process ⇒ Process
* Name and Description
* Save

<mark style="color:purple;background-color:purple;">**Step 2: Create an Automated Process**</mark>

* Select the Project created
* Create ⇒ Process ⇒ Enter name and description
* Side Panel ⇒ Variables
* Add Input ⇒ First Name, Last Name, Employee Id, BadgeStatus
* Choose the **+** before the **End** element.
* Select ⇒ Email
* Open Mail Body Editor ⇒ Enter the mail body, bind the dynamic variables

<mark style="color:purple;background-color:purple;">**Step 3: Release, Deploy and Publish the Process**</mark>

* Release ⇒ Deploy ⇒ Publish

<mark style="color:purple;background-color:purple;">**Step 4: Create a Joule Studio Project**</mark>

<mark style="color:purple;background-color:purple;">**Step 5: Create a Joule Skill and Configure Inputs**</mark>

* Create Joule Skill
* Do not allow Joule to generate a response
* Configure parameters

<mark style="color:purple;background-color:purple;">**Step 6: Configure Email Process**</mark>

* Choose the **+** between **Trigger** and **End**.
* Select Run Process
* Select the Process selected earlier
* Do fields mapping

<mark style="color:purple;background-color:purple;">**Step 7: Configure Send Message**</mark>

* Configure illustrated message

<mark style="color:purple;background-color:purple;">**Step 8: Release and Deploy the Joule Skill**</mark>

<mark style="color:purple;background-color:purple;">**Step 9: Test Joule Skills**</mark>

* Check Joule in Environment
* You can check if the process has been called by going to Monitoring > Process and Workflow Instances.
*

    <figure><img src=".gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>
