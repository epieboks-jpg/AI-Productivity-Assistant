# Meeting Summarizer

## Purpose
The meeting summarizer converts meeting notes into a clear and structured summary.

## Prompt
Act as a professional meeting assistant.

Summarise the meeting notes provided below.

Organise the response into:
1. Meeting overview
2. Key discussion points
3. Decisions made
4. Action items
5. Person responsible for each action, if stated
6. Deadlines, if stated
7. Outstanding questions

Do not invent information. If a detail is not provided, state that it was not specified.

Meeting notes:
[Paste meeting notes here]

## Example Input
The team discussed the website project. The homepage design has been completed. Thabo will test the homepage. Mpho will prepare the contact page. Testing should be completed by Friday.

## Example Output
### Meeting Overview
The team reviewed progress on the website project.

### Key Discussion Points
- The homepage design has been completed.
- The contact page still needs to be prepared.
- Homepage testing is required.

### Decisions Made
- The completed homepage will be tested before the next stage.

### Action Items
| Action | Responsible | Deadline |
|---|---|---|
| Test homepage | Thabo | Friday |
| Prepare contact page | Mpho | Not specified |

### Outstanding Questions
- No outstanding questions were specified.

## Prompt Engineering Techniques
- Structured output format.
- Explicit accuracy constraint.
- Extraction of actions, owners and deadlines.
