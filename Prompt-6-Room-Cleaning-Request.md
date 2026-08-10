# Prompt 6 – Room Cleaning Request

## Version 1
Write a room cleaning request for an aged-care resident.

## Version 2
Write a clear and professional cleaning request for a resident’s room that needs extra attention. Include the resident’s name, room number, cleaning issue, date noticed, and any priority information provided.

## Final Version
You are assisting the administration team in an aged-care facility. Create a short, professional room cleaning request using only the information provided.

Include:
- Resident name
- Room number
- Cleaning issue
- Date the issue was noticed
- Priority level, if provided
- Any relevant non-clinical instructions

Keep the request clear, respectful, and suitable for internal staff communication.

Do not include or assume medical information, personal details, or reasons for the cleaning issue that have not been provided.

If important information is missing, clearly state that staff confirmation is required.

## Example Input
Resident name: David Miller
Room number: 24
Cleaning issue: Carpet requires additional cleaning after a drink spill
Date noticed: 22 August 2026
Priority level: Medium
Instructions: Please complete before the resident returns from afternoon activities

## Improvement Notes
Version 1 was too general and did not provide enough information for cleaning staff.

Version 2 added the main room and cleaning details.

The final version added a structured format, privacy controls, respectful language, and instructions for handling missing information.
## Test 1 – Version 1 Output

Room Cleaning Request

Resident: David Miller  
Room: 24  
Cleaning issue: Carpet requires cleaning after a drink spill  
Date: 22 August 2026  
Priority: Medium  

Please clean the carpet before the resident returns from afternoon activities.

## Issues Identified in Version 1

- The prompt did not clearly define a standard cleaning-request structure.
- It did not specify what information should or should not be included.
- It lacked privacy safeguards.
- It did not explain what to do if important cleaning details were missing.

## Test 2 – Final Version Output

Room Cleaning Request

Resident: David Miller  
Room Number: 24  
Cleaning Issue: Carpet requires cleaning following a drink spill  
Date: 22 August 2026  
Priority: Medium  
Instruction: Complete cleaning before the resident returns from afternoon activities.

Please action the cleaning request according to the information above.

## Final Version Evaluation

- The final prompt produced a concise and structured housekeeping request.
- It included the room, issue, priority and relevant timing instruction.
- It avoided adding unnecessary personal or medical information.
- The structured format makes the request easier for housekeeping staff to action.
- Staff confirmation remains necessary where required information is incomplete.

## Audit Log

| Version | Change Made | Observed Effect | Lesson Learned |
|---|---|---|---|
| Version 1 | Used a simple room-cleaning instruction. | The output was understandable but lacked strong structure and privacy controls. | More specific fields and context were needed. |
| Version 2 | Added room number, issue, date and priority. | The output became more useful for housekeeping staff. | Required operational details improve clarity. |
| Final Version | Added aged-care context, privacy constraints and missing-information handling. | The output became more controlled and suitable for administrative use. | Clear constraints help protect resident information while maintaining efficiency. |
