#tables

##　users
- email (string,not null,  )
- encrypted_password (string,not null)
- name (string,not null)
- profile (text,not null)
- occupation (text,not null)
- position (text,not null)

## prototypes
- title (string,not null)
- catch_copy (text,not null)
- concept (text,not null)
- user (references,not null,user_id)

## comments
- content (text,not null)
- prototype (references,not null,prototype_id)
- user (references,not null,user_id)
