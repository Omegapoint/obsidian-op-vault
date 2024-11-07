---
template_version: 1.2.0
created_date: 2024-02-14
tags: 
related:
  - "[[000 launchpad]]"
---
# Vault documentation
%% add, change and update this note to reflect how you set up your vault %%

### Folder structure
- `+++` - inbox, the default place for new notes
- `atlas` - main knowledge repository. Most notes will likely end up in the `atlas/notes` folder
- `calendar` - time-based information, like meeting notes and daily notes
- `efforts`  - relating to tasks and projects
- `utilities` - holding template notes and other meta things needed to keep the vault running

### Tags
- project status tags
    - `#effort_status/active `
    - `#effort_status/backlog `
- daily notes
    - `#daily`


### Efforts tracking
Efforts are very lightweight notes, using the template [[new project]] for new notes in the folder `efforts/1 active` and `efforts/3 backlog`. This is managed by the plugin "templater"

Efforts have three states, tracked by tags:

| state                       | tag                                     |
| --------------------------- | --------------------------------------- |
| planned but not started yet | `#effort_status/backlog`                |
| active                      | `#effort_status/active`                 |
| completed                   | untagged, remove all effort_status tags |

Efforts link to a map called `YYYY efforts MOC` using the property `related:`

🆕️ When a project is started
- create or move a note to `efforts/1 active`
- set the tag  `#effort_status/active` (removing `#effort_status/backlog` if needed)
- check that the `related` property links to the map `YYYY efforts MOC`

🆗 When a project is completed
- remove the tag  `#effort_status/active` (no effort_status tag at all)
- move file to folder `efforts/4 archive/YYYY`


### Theme
The colors used are set in the css snippet file `.obsidian/snippets/obsidian.css`. 