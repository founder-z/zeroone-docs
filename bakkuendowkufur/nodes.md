# Nodes

Zero One contains custom n8n with 3 additional nodes, which allows you to write custom business logic depending on data inside Zero One.

### ZeroOne Trigger

Zero one trigger - is custom webhook trigger, which handles JWT verification and defines input/output schema which then can be used in Frontend workflows

![](<../.gitbook/assets/image (1).png>)![](<../.gitbook/assets/image (2).png>)

#### Input

Input is json schema which allows you specify expected HTTP Request Body structure and validate each request to correspond the described JSON schema. Input Schema does not describe transformation, but validation

{% hint style="warning" %}
Input gets validated on each request
{% endhint %}

#### Output

Input is json schema which allows you specify expected HTTP Response Body structure. By specifying specifying Output you allow Zero One interpret tyoes and suggest appropriate values in Expression Input

{% hint style="warning" %}
Ouput does validate or transform the response body, its meant to be used for typehints Zero One Expression Inputs
{% endhint %}

### ZeroOne Database Node

ZeroOne Database Node - allows you to read/update/insert/delete data from Zero One database

![](../.gitbook/assets/image.png)

