---
Created: 2025-09-08
tags:
  - notifications
  - MeetingNotes
Key Speaker: Kurtis Davis
---
Step 1 = dotnet ef migrations add {MigrationName} --project Notifications.Data --startup-project Notifications.Kclife.Net

Step 2 = dotnet ef database update --project Notifications.Data --startup-project Notifications.Kclife.Net

RecipientId = OktaID
