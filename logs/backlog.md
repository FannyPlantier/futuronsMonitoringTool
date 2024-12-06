
Futurons is a non-profit organisation focused on speculative design, design fiction, and futures desugn / transition design 

# Requirements analysis

The goal of this monitoring tool is to collect different types of data (audio, video, pictures, texts from various sources) and establish relationships between them.
This tool must be both individual and collaborative, allowing each user to create their own collections while also contributing to others' collections. Data should be automatically imported into the application (e.g., via RSS feeds) or manually added by uploading or creating new content.
At a later stage, the tool should allow users to publish or distribute content across different websites or platforms.


## User categories and roles

There will be 4 categories of users with different statuses and rights :
- Visitor
- Collaborator
- Editor
- Administrator

The user categories determine the rights assigned to each type of user. This means that each user inherits the permissions of the previous category.

<ins> As a visitor, I can : </ins> <br>
    - Consult collections <br>
    - Suggest new content to add to a collection <br>
    
<ins> As a collaborator, I can : </ins> <br>
    - Manage the content automatically import into my account through RSS feeds (I can add it to a collection, keep it in my pending content, delete it) <br>
    - Manage a collection I own or share (create a new collection, add a new keyword, change its status to private or public, invite someone to collaborate) <br>
    - Manage my own contents (create, edit, publish, or delete content. Meaning that new content is initially created at as a draft) <br>
    - Add a content to a collection (either my own or collection I collaborate on) <br>
    - Join someone else's collection (by accepting an invitation) <br>
    - Suggest a new keywords <br>
       
<ins> As an editor, I can : </ins> <br>
    - Manage keywords (create, delete, accept suggestion) <br>
    - Manage all contents, even if I don't own it <br>
    - Create relationships between collections or content <br>

<ins> As an administrator I can : </ins> <br>
    - Manage users (create a new user, manage users rights) <br>
    - Manage the tool <br>
    
