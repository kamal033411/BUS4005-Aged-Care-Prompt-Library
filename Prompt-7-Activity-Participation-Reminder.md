# Prompt 7 – Activity Participation Reminder

## Version 1
Write a reminder for residents about an upcoming group activity.

## Version 2
Write a friendly reminder for aged-care residents about an upcoming activity. Include the activity name, date, time, location, and any simple instructions.

## Final Version
You are assisting the administration team in an aged-care facility. Write a short, friendly, and respectful reminder for residents about an upcoming group activity.

Use only the information provided.

Include:
- Activity name
- Date
- Time
- Location
- Any simple participation instructions
- Any items residents should bring, if provided

Keep the message easy to understand, positive, and suitable for an aged-care environment.

Do not include or assume medical, personal, or mobility information about any resident.

If important activity information is missing, clearly state that staff confirmation is required.

## Example Input
Activity name: Garden Morning
Date: 24 August 2026
Time: 10:30 am
Location: Courtyard
Instructions: Please arrive 10 minutes early
Items to bring: Hat, if available

## Improvement Notes
Version 1 was too general and did not provide enough event details.

Version 2 added the main activity information.

The final version added a clear aged-care context, simple language, privacy controls, and instructions for missing information.
## Test 1 – Version 1 Output

Activity Reminder

You are invited to attend Garden Morning.

Date: 24 August 2026  
Time: 10:30 am  
Location: Courtyard  

Please arrive 10 minutes early and bring a hat if available.

We hope you enjoy the activity.

## Issues Identified in Version 1

- The prompt did not clearly specify the intended tone or structure.
- It did not include safeguards against assumptions about resident mobility or health.
- It did not explain how missing activity details should be handled.
- The output format could vary between different users or activities.

## Test 2 – Final Version Output

Activity Participation Reminder

Activity: Garden Morning  
Date: 24 August 2026  
Time: 10:30 am  
Location: Courtyard  

Please arrive 10 minutes early. Bring a hat if available.

We look forward to your participation.

## Final Version Evaluation

- The final prompt produced a friendly and easy-to-understand reminder.
- It included all supplied activity details in a consistent format.
- It did not make assumptions about the resident's health, mobility or ability to participate.
- The use-only-provided-information rule reduces unsupported additions.
- Staff review remains important before the reminder is distributed.

## Audit Log

| Version | Change Made | Observed Effect | Lesson Learned |
|---|---|---|---|
| Version 1 | Used a general instruction to create an activity reminder. | The output was friendly but had limited control over structure and assumptions. | Clearer requirements and safeguards were needed. |
| Version 2 | Added activity name, date, time, location and instructions. | The output became more structured and useful. | Specifying required fields improves consistency. |
| Final Version | Added aged-care context, restrictions on health and mobility assumptions, and missing-information handling. | The output became safer and more controlled. | Prompt constraints are important when communication involves residents. |
