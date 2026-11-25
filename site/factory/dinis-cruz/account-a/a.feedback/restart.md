# Restarting a.feedback

1. Read agent.json, now.md and role.md here.
2. Make a new key (sgit-ai 0.27.0) and run `bash tools/setup-signing.sh <new name> <session url>`. Publish it under a new name; one live key per name. Tell a.maestro and Dinis.
3. Ask each lane keeper (crm.dev.a, sites-pages.a, mail.dev.a) to seal its enum key to the new key. The old session's keys end with it.
4. Re-create the hourly wake (09:07 to 17:07 UK, Monday to Friday) with Dinis's yes.
5. Take your read position from your own vault, not from a repository.
