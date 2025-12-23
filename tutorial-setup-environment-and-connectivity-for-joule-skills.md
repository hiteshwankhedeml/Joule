# Tutorial: Setup Environment and Connectivity for Joule Skills

* Access to an SAP BTP tenant configured for Joule and Joule Studio is needed



<mark style="color:purple;background-color:purple;">**Step 1: Create an Environment for Testing Joule Skills**</mark>

* SAP Build Lobby ⇒ Control Tower ⇒ Environment ⇒ Create ⇒ Give Name and Description
* Once created then select the environment and select the Joule Tab
*

    <figure><img src=".gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>
*

<mark style="color:purple;background-color:purple;">**Step 2: Create Destination**</mark>

* BTP Cockpit ⇒ Connectivity ⇒ Connection ⇒ create ⇒ From Scratch
* Enter Name, URL and properties ⇒ Create
*

    | Properties                                       | Value           |
    | ------------------------------------------------ | --------------- |
    | **`sap.processautomation.enabled`**              | **`true`**      |
    | **`sap.applicationdevelopment.actions.enabled`** | **`true`**      |
    | **`sap.build.usage`**                            | **`odata_gen`** |
* Once created then check the connection
*

    <figure><img src=".gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>
*

<mark style="color:purple;background-color:purple;">**Step 3: Associate Destinations with Environments**</mark>

* Build Lobby ⇒ Control Tower ⇒ Destinations ⇒ Add
* Select the destination ⇒ Next ⇒ Select the environment ⇒ Add destination
* Ensure you also select Public environment otherwise you won't be able to see it for testing

Step 4:&#x20;
