# File Structure
## Home dir and storage

### Home dir
The home dir of the user will be at `/opt/exchange/mailboxes/{username}`.
This is the place where all the mails will be stored.

```
Mailboxes
|- user_1
|   |- .config
|   |- Inbox
|   |   |- Mail 1
|   |   |- Mail 2
|   |
|   |- Deleted
|   |   |- Mail 0
|   |
|   |- Sent
|   |   |- Mail 1
|   |   |- Mail 2
|   |
|   |- Drafts
|   |   |- Mail 
|   |
|   |- Outbox
|  
|
|- user_1
    |- .config
    |- Inbox
    |   |- Mail 1
    |   |- Mail 2
    |
    |- Deleted
    |   |- Mail 0
    |
    |- Sent
    |   |- Mail 1
    |   |- Mail 2
    |
    |- Drafts
    |   |- Mail 1
    |
    |- Outbox

```

### config dir
In this directory there will be a `.config` directory where all the user settings will be stored.

### User Mailboxes
The User Mailbox will be in the Mailboxes directory and will be named after the user.

In this directory there will be a few directories that are predefined by the system.
These are:
- Inbox: The inbox of the user
- Deleted: The deleted mails of the user
- Sent: The sent mails or mails that are in the outbox of the user
- Drafts: The drafts of the user
- Outbox: The outbox of the user

### Outbox
The outbox is the place where all the mails are stored that are not sent yet.
The mails will be moved to the sent folder when they are sent.



