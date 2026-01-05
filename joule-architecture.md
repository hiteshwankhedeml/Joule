# 🟢 Joule Architecture

* Enriches users query with context before passing it to LLM
* These LLM comes from partners with strict agreement ensuring no customer data is used for modelling
* <mark style="color:purple;background-color:purple;">**LLM returns a grounded response or identifies the need to trigger SAP cloud application scenarios**</mark>&#x20;
  * <mark style="color:purple;background-color:purple;">**Scenario Catalog: This catalog contains metadata of all available scenarios, functions, and skills of SAP cloud application**</mark>
  * <mark style="color:purple;background-color:purple;">**Knowledge Catalog: This contains SAP-knowledge as well as the customer-owned knowledge. This process is based on Retrieval Augmented Generation for enterprise (RAGe) and lets the LLM generate an answer based and grounded on dedicated text that was previously retrieved**</mark>
  * <mark style="color:purple;background-color:purple;">**Joule is aware of the user's context and history**</mark>
* <mark style="color:purple;background-color:purple;">**Joule then interacts with SAP backend as needed**</mark>
* All responses are filtered and returned securely - ensuring data privacy, security and responsible AI
*

    <figure><img src=".gitbook/assets/{F620553D-5139-46DB-A247-030BBDAA7747}.png" alt=""><figcaption></figcaption></figure>
