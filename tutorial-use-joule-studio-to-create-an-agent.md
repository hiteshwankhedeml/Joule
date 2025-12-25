# Tutorial: Use Joule Studio to Create an Agent

<mark style="color:purple;background-color:purple;">**Private environments provide safe, isolated spaces for experimenting with Joule agents. They allow you to build, test, and refine your agents and skills without affecting any shared or productive environments**</mark>



<mark style="color:purple;background-color:purple;">**Step 1: Create a Destination**</mark>

* Create and check the destination
* Use the below for creating the destination

```json
{
    "exportTime": "2025-12-01 11:36:21.427356474",
    "destination": {
        "Name": "sample-maintenance-service",
        "Type": "HTTP",
        "Description": "CAP Application",
        "URL": "https://sample-maintenance-srv-sweet-nyala-od.cfapps.us10.hana.ondemand.com/odata/v4/maintenance-order",
        "ProxyType": "Internet",
        "Authentication": "BasicAuthentication",
        "User": "TECHNICAL_USER",
        "Password": "TECHNICAL_PASS"
    }
}
```

<mark style="color:purple;background-color:purple;">**Step 2: Create a Private Environment**</mark>

* Lobby ⇒ Control Tower ⇒ Environments ⇒ In the List Select the Private Environment ⇒ Activate
* Add Destination to the environment

<mark style="color:purple;background-color:purple;">**Step 3: Import Project with Skills**</mark>

* Create or import an project having skills

<mark style="color:purple;background-color:purple;">**Step 4: Create an Agent**</mark>

* Project ⇒ Create ⇒ Joule Agent
* Enter Name and Description
* Create

<mark style="color:purple;background-color:purple;">**Step 5: Configure the Agent Behavior**</mark>

* Add Expertise, Instructions and Additional Context
* Model Settings ⇒ Select Model here
* Tools ⇒ Add Joule Skills here

<mark style="color:purple;background-color:purple;">**Step 6: Test in Private Environment**</mark>

* Choose Test in agent editor
* Select Environment and Destination
* Enter timeline ⇒ In Timeline we can see the entire flow
