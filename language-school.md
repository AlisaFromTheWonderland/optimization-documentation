## Main Page Optimization

| Before Admin | After Admin |
|---|---|
| <img height="100" alt="Screenshot at May 01 12-07-28" src="https://github.com/user-attachments/assets/bb8107bd-a29a-4691-a8bf-a92311a18caf" /> | <img height="100" alt="IMG_2869" src="https://github.com/user-attachments/assets/fcd928a0-df38-4b4c-8dc5-e15dcce9b1db" /> | 
| Simple list of groups with only **group name** and **link to the group** | Structured main page with a **full dashboard-style table** |
| Minimal navigation value: the page works mostly as a **link directory** | Main page works as an **operational control panel** for daily admin tasks |
| Limited visibility of learning process and group details | Added key fields for quick management: **Name, Link, Schedule, Payment, Comment, Quantity, Format, Age, Level, Attendance** |
| No clear separation between different learning formats | Data is grouped by categories such as **Group**, **Individual**, **Waiting** |
| Harder to understand the current status of classes at a glance | Easier visual scanning due to **color coding**, sectioning, and structured rows |
| No centralized view of attendance tools | Added a dedicated **Attendance** column with direct links to forms |
| Weak support for quick coordination and communication | Added **Comment** field for operational notes and context |
| Less convenient for tracking payment status | Added **Payment / Money** column for quick financial visibility |
| Less useful for everyday administrative decisions | One page now supports **schedule control, student tracking, communication, and lesson administration** |
| Spreadsheet structure is closer to a raw storage list | Spreadsheet structure is closer to a **working CRM-style admin page** |


## Group / Student Card Optimization

| Before Admin | After Admin |
|---|---|
| img | img | 
| Payment and attendance were stored in a **simple monthly table** with limited structure | Payment and attendance were reorganized into a **more structured operational card** |
| The sheet mainly showed **student names, lesson dates, and payment date** | The sheet now includes **lesson dates, teacher, tariff, payment block, attendance, absences, warnings, carry-over values, and comments** |
| Payment tracking was simplified to a single block like **“payment date”** | Payment tracking became more detailed with separate logic for **to be paid / paid / method / comments / left from previous month / actual payment** |
| Attendance and payment facts were visually mixed in the same grid | Attendance, payment, and debt/carry-over information are now **logically separated into dedicated sections** |
| It was harder to see the **current month status** at a glance | The updated layout gives faster visibility into **monthly workload, payment status, attendance status, and remaining balances** |
| The old format was closer to a **manual register** | The new format is closer to an **admin dashboard / operational accounting sheet** |
| Limited support for tracking exceptions such as bonuses, free lessons, or transferred balances | Added explicit fields like **free**, **left**, **from previous month**, and comments for operational edge cases |
| Teacher information was either missing or not consistently structured | Teacher information is now integrated directly into the monthly block |
| The sheet gave less support for admin actions during the month | The updated card supports **ongoing administration**, not just historical record keeping |
| It was less scalable for complex formats such as online, offline, group, duo, or individual accounting | The new structure is more adaptable for **different lesson formats and payment scenarios** |

## What Exactly Was Optimized

### 1. Better structure of monthly accounting
The old version focused mostly on lesson dates and basic payment notes.  
The new version introduced a clearer monthly block with:
- lesson schedule
- tariff
- expected payment
- actual payment
- leftover amount
- attendance fact

### 2. Separation of operational data
Previously, payment and attendance details were mixed together visually.  
After optimization, the sheet separates:
- lesson dates
- payment calculations
- actual payments
- absences
- warnings
- transferred balances from previous month

This makes the card easier to read and maintain.

### 3. Faster admin navigation
The updated layout makes it easier for an admin to quickly answer questions like:
- how many lessons took place;
- how much should be paid;
- how much was actually paid;
- whether there is a carry-over from the previous month;
- whether there were absences or special conditions.

### 4. Better support for real-life scenarios
The optimized version supports edge cases much better, for example:
- free / bonus lessons
- partial payment
- carry-over from previous month
- offline / online distinction
- teacher assignment
- attendance fact vs payment fact

### 5. Improved scalability
The old version worked more like a static table.  
The new version is more scalable for:
- group cards
- individual student cards
- duo format
- online and offline lessons
- monthly operational tracking

## Result

The optimization changed the sheet from a **basic lesson-payment register** into a **structured administrative tool** that supports day-to-day management, accounting visibility, and faster operational decisions.
