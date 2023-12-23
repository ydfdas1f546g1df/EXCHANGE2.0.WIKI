# User Management

## general

The users are based of the unix users  
This makes the howl process of user management very easy.  
Because of:
1. We don't need to create a new user management system.
2. We can set rights and groups very easily.
3. We can use the file structure for storing all the Mails.

## Naming conventions

All the unix Users get a `m_` prefix to define them as a Mail user.

**example:**  
If a user is called `Peter Schneider` his unix username would be `m_peter.schneider`.


## Mailbox rights

The rights of the mailboxes are based on the unix rights.

for example, if someone needs to have access to the mailbox of `m_peter.schneider` he needs to be in the group `m_peter.schneider` of the unix user `m_peter.schneider`.
