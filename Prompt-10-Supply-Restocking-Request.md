# Prompt 10 – Supply Restocking Request

## Version 1
Write a request to restock supplies in an aged-care facility.

## Version 2
Write a clear and professional restocking request for supplies that are running low in an aged-care facility. Include the item name, current quantity, required quantity, location, and level of urgency.

## Final Version
You are assisting the administration team in an aged-care facility. Create a short, professional supply restocking request using only the information provided.

Include:
- Item name
- Current quantity, if provided
- Required quantity
- Storage or use location
- Urgency level, if provided
- Any relevant non-clinical notes

Keep the request clear, concise, and suitable for internal staff communication.

Do not add or assume information that has not been provided.

If important information is missing, clearly state that staff confirmation is required.

## Example Input
Item name: Disposable gloves
Current quantity: 3 boxes
Required quantity: 12 boxes
Location: Level 1 supply room
Urgency level: High
Notes: Current stock is expected to run low within two days

## Improvement Notes
Version 1 was too general and did not specify what information was required.

Version 2 added important stock and quantity details.

The final version added a clear structure, aged-care context, instructions to avoid assumptions, and a process for handling missing information.
## Test 1 – Version 1 Output

Supply Restocking Request

Item: Disposable gloves  
Current quantity: 3 boxes  
Required quantity: 12 boxes  
Location: Level 1 supply room  
Urgency: High  

Stock is expected to be low within two days. Please arrange restocking as soon as possible.

## Issues Identified in Version 1

- The prompt was general and did not define a consistent request format.
- It did not specify that the AI should only use the inventory information provided.
- It did not clearly distinguish current stock from requested stock.
- It did not explain what should happen if quantity or location information was missing.

## Test 2 – Final Version Output

Supply Restocking Request

Item: Disposable gloves  
Current Quantity: 3 boxes  
Required Quantity: 12 boxes  
Location: Level 1 supply room  
Urgency: High  
Note: Stock is expected to be low within two days.

Please arrange restocking according to the information provided.

## Final Version Evaluation

- The final prompt produced a clear and actionable supply request.
- It distinguished current stock from required stock.
- It used only the supplied inventory information and did not estimate or invent quantities.
- The structured format supports faster review by administrative or supply staff.
- Inventory levels still require human verification before ordering.

## Audit Log

| Version | Change Made | Observed Effect | Lesson Learned |
|---|---|---|---|
| Version 1 | Used a basic restocking instruction. | The output communicated the request but lacked strong controls. | Clear inventory fields were required. |
| Version 2 | Added current quantity, required quantity, location and urgency. | The output became clearer and easier to action. | Structured fields improve operational efficiency. |
| Final Version | Added use-only-provided-information rules and missing-information handling. | The output became more reliable and avoided unsupported inventory assumptions. | AI can structure requests, but stock verification must remain with staff. |
