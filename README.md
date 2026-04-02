![VDA 278](https://github.com/user-attachments/assets/80d2bffa-ec2d-4f6f-91be-9bc244e9fa63)

# VDA 278 – Emission Test Results
## JSON Subschema according to VDA 231‑301

## Purpose and Scope

This repository provides a **specific JSON subschema for the digital exchange of test results according to VDA 278**,  
*“Thermal Desorption Analysis of Organic Emissions for the Characterization of Non‑Metallic Materials for Automobiles”*.
 - recommendation source: https://webshop.vda.de/VDA/de/vda-278-05-2016
   
The subschema defines a **machine‑readable representation of emission test results** obtained using the VDA 278 method.  
It supports the standardized, transparent, and interoperable exchange of laboratory data along the supply chain.

The subschema is based on the **VDA 231‑301 recommendation** and represents a specialized extension of the generic VDA 231‑301 JSON schema.

---

## Position within VDA 231‑301

Within the VDA 231‑301 ecosystem:
- the **generic schema** defines the common structure for digital test reports,
- this **VDA 278 subschema** specifies the data elements required to represent emission test results generated according to the VDA 278 method.

The subschema ensures that emission test results from different laboratories can be exchanged and processed in a **consistent, system‑independent, and machine‑readable form**.

---

## Relation to the VDA 278 Test Method

VDA 278 defines a **laboratory test method** based on thermal desorption analysis (TDA) for determining:
- total emissions,
- individual substance emissions,
- and characteristic emission parameters of non‑metallic materials.

⚠️ **Important clarification:**
- This repository **does not describe the VDA 278 test procedure itself**.
- It does **not define sampling, test execution, evaluation rules, or limit values**.
- It provides a **technical data structure only** for representing the *results* of a VDA 278 test in digital form.

The authoritative description of the VDA 278 test method is published exclusively by the VDA and is available via the **VDA Webshop**.

---

## Documentation of Emission Results and Measured Values

The subschema specifies the **format in which emission test data shall be documented**.

This includes, for example:
- structured representation of **total emission values**,
- documentation of **individual substances** and their measured quantities,
- clear association of results with test conditions, specimens, and analytical parameters.

By enabling a detailed and structured digital representation of emission test results, the subschema supports a level of transparency and data reuse that goes beyond traditional document‑based reporting.

---

## Typical Use Cases

The VDA 278 subschema supports use cases such as:
- digital exchange of emission test results between laboratories, suppliers, and OEMs
- structured integration of emission data into material databases
- traceable documentation of emission behavior for quality and compliance processes
- automated processing and evaluation of emission data in IT systems

The subschema improves **data consistency, automation, and comparability** across organizations and systems.

---

## Applicability Beyond the Automotive Industry

Although VDA 278 originates from the automotive interior context, **emission testing of materials is relevant across many industries**, for example:
- consumer products
- furniture and interior materials
- construction products
- polymers, foams, adhesives, and textiles

The subschema is therefore **not limited to automotive applications**.  
It can be used wherever emission test results need to be:
- documented,
- exchanged between organizations,
- or integrated into digital quality and compliance workflows.

---

## Example Files

This repository contains example files illustrating the usage of the subschema:
- JSON examples representing VDA 278 test results
- the corresponding JSON Schema definition

These examples are provided for **illustration and implementation support only**.

---

## Important Note

> [!IMPORTANT]
> This subschema provides **structured emission test result data only**.  
> It does **not** perform emission evaluation, regulatory interpretation,
> compliance decisions, or pass/fail assessments.
> Such decisions remain the responsibility of the applicable standards,
> regulations, and processes in which the data is used.

---

## License 

The VDA 231‑301 JSON schemas, including this VDA 278 subschema, are released under the **MIT License**, allowing free use, modification, and distribution.


## Contributing & VDA Process

Contributions are welcome.  

Any changes intended to become part of the official VDA recommendation must follow the formal VDA committee and release process.
This repository hosts a subschema extending the generic VDA 231‑301 JSON schema.

GitHub is used as a platform for collaborative drafting, discussion, and technical refinement.  
Issues and Pull Requests are welcome.

⚠️ Please note:  
Only subschemas that have successfully passed the formal VDA committee and release process may become part of the official VDA 231‑301 recommendation.

Details on contribution rules, governance, and approval processes are described in the organization-wide Contributing Guidelines:  
https://github.com/VDA231-301/.github/blob/main/CONTRIBUTING.md
