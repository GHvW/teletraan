# teletraan

Teletraan helps you manage your library.

Really, its just a tagging system, but hopefully that helps


### Database Schema

##### tag
- name (user_id + name should be pk? name should be unique for user_id?)
- user_id (fk person.id)

##### person
- discord_id
- username

##### archive
- id
- channel (channel it was linked in)
- description (link, note, directory path, whatever helps you get to where you need to get)
- person_id (person who requested archival)
