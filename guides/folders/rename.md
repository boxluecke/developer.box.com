---
rank: 3
related_endpoints:
  - put_folders_id
related_guides:
  - folders/update
required_guides: []
related_resources:
  - folder
alias_paths: []
cId: folders
scId: null
id: folders/rename
isIndex: false
---

# Rename a folder

To rename a folder in Box you will need to provide our API with a new `name` for
the folder.

<Samples id='put_folders_id' variant='rename' >

</Samples>

<Message type='notice'>

# Name restrictions

There are some restrictions to the file name. Names containing non-printable
ASCII characters, forward and backward slashes (`/`, `\`), as well as names
with trailing spaces are prohibited.

Additionally, the special names `.` and `..` are reserved names and therefore
also prohibited.

</Message>