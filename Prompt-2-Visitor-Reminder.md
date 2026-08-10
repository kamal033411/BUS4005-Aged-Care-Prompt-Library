# Prompt 2 – Visitor Reminder Message

## Version 1
Write a reminder message to a resident’s family about an upcoming visit.

## Version 2
Write a polite and friendly reminder to a resident’s family about an upcoming scheduled visit. Include the resident’s name, visit date, visit time, and any relevant visitor instructions.

## Final Version
You are assisting the administration team in an aged-care facility. Write a short, polite, and professional reminder message to a resident’s family about an upcoming scheduled visit.

Use only the information provided.

Include:
- Resident name
- Visit date
- Visit time
- Visitor name, if provided
- Any relevant arrival or visitor instructions

Keep the message warm, respectful, and easy to understand.

Do not include or assume any medical, clinical, or private information about the resident unless it has been specifically provided and is necessary for the message.

If important visit information is missing, clearly indicate that staff confirmation is required.

## Example Input
Resident name: John Parker  
Visit date: 16 August 2026  
Visit time: 2:30 pm  
Visitor name: Sarah Parker  
Instructions: Please check in at reception on arrival.

## Improvement Notes
Version 1 was too broad and did not specify what information the reminder should contain.

Version 2 added important visit details and a clear tone.

The final version added aged-care context, privacy controls, structured information requirements, and instructions for handling missing information.
## Test 1 – Version 1 Output
## Issues Identified in Version 1

- The prompt was very general and did not specify the required structure or tone.
- It did not clearly control which resident information should be included.
- It did not include privacy safeguards.
- It did not explain how missing visit information should be handled.
- 
## Final Version Evaluation

- The final prompt produced a clear and professional family reminder.
- It used only the information provided and avoided unnecessary resident details.
- Privacy controls reduced the risk of including medical, clinical or unrelated private information.
- The required fields improved consistency and made the output easy to review.
- Missing-information instructions provide an additional safeguard before the message is used.
- Human staff review remains necessary before sending the final communication.
- ## Audit Log

| Version | Change Made | Observed Effect | Lesson Learned |
|---|---|---|---|
| Version 1 | Used a basic reminder instruction with minimal guidance. | The output was understandable but the prompt did not control tone, privacy or missing information. | More context and safeguards were required. |
| Version 2 | Added resident and visit details, professional tone and clearer content requirements. | The output became more structured and suitable for family communication. | Explicit required fields improve consistency. |
| Final Version | Added aged-care context, use-only-provided-information rule, privacy constraints and missing-information handling. | The output remained professional while providing stronger control over sensitive information. | Context, constraints and human confirmation improve responsible AI use. |
