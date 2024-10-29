---
marp: true
title: Indico - an event management system
description: An overview of the Indico Project as well as its usage at CERN
theme: indico
paginate: true
_paginate: false
footer: Duarte Galvão, Michel Succar - IT-CA-CTE (CERN)
---
<!-- color: "#6ac9ff" -->
<!-- backgroundColor: "#00293A" -->

<!-- _footer: '' -->
<!-- _backgroundColor: "#0033A0" -->

![bg width:400px](assets/theme/cern.svg)

---

<!-- _footer: '' -->

![width:400px](assets/theme/logo_inverted.svg)
*how's it going? when are we dumping SPMS?*

### Duarte Galvão, Michel Succar (CERN)

#### JACoW Team Meeting 2024

<style scoped>
h3 {
    color: #aaa;
    font-size: 0.8em;
    font-weight: normal;
}
</style>

---

### Adoption at CERN

![height:400px](assets/event_stats_cern.svg)

---

![bg 100%](assets/community_map.png)

*The most popular event management system you never heard about*

&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;

 - **300+ servers**
 - **> 350K users**
 - Initial growth in research, but growing beyond it
   - [indico.un.org](https://indico.un.org)
   - [events.canonical.org](https://events.canonical.com/)
   - [indico.gnome.org](https://indico.gnome.org)
   - [lpc.events](https://lpc.events)

---

### Team

![height:400px drop-shadow:0,5px,10px,rgba(0,0,0,.4)](assets/team.png) ![height:200px drop-shadow:0,5px,10px,rgba(0,0,0,.4)](assets/team_lead.png)

---

### Extensions

 - Video conferencing 📹
 - Payment Systems 💰
 - Automatic conversion to PDF 🖨
 - Search 🔎
 - Storage 💾
 - URL Shortening 👉
 - Internal Workflows (e.g. recording, visitors)

---
<style scoped>
    section {
        justify-content: start;
    }
    h3 {
        margin-top: 3em;
    }
</style>

### Zoom

![bg width:800px drop-shadow:0,5px,10px,rgba(0,0,0,.4)](assets/indico_meeting_header.png)

---
<style scoped>
    section {
        justify-content: start;
    }
    h3 {
        margin-top: 3em;
    }
</style>

### Electronic Payment

![bg width:600px drop-shadow:0,5px,10px,rgba(0,0,0,.4)](assets/indico_meeting_payments.png)

---
<style scoped>
    section {
        justify-content: start;
    }
    h3 {
        margin-top: 3em;
    }
</style>

### Workflows

![bg width:40% drop-shadow:0,5px,10px,rgba(0,0,0,.4)](assets/logistics.png)

---
<style scoped>
    section {
        justify-content: start;
    }
    h3 {
        margin-top: 3em;
    }
</style>

### Access Registration

![bg width:600px drop-shadow:0,5px,10px,rgba(0,0,0,.4)](assets/visitors.png)

---
<style scoped>
    section {
        justify-content: start;
    }
    h3 {
        margin-top: 1em;
    }
</style>

### Recording of Events

![bg height:60% drop-shadow:0,5px,10px,rgba(0,0,0,.4)](assets/webcast.png)

---
<style scoped>
    section {
        justify-content: start;
    }
</style>

### Check-in App (PWA)

![bg width:65% drop-shadow:0,5px,10px,rgba(0,0,0,.4)](assets/checkin_app.png)

---

### Governance
![bg right 80%](assets/gov.png)

 - Clear **Governance Policy** with **roles and bodies**
 - Regular workshops and community events
 - **Consultative board:** CERN, UN and MPP
 - **"Making Indico better for us and everyone else"** e.g. accessibility work by UN
 
![width:300px drop-shadow:0,5px,10px,rgba(0,0,0,.4)](assets/gov_logos.png)
https://github.com/indico/governance

---

### What is JACoW?

---

<!-- _paginate: hold -->

### What is JACoW? (our POV)

![height:500px](assets/architecture.svg)

---

<!-- _paginate: hold -->

### What is JACoW? (our POV)

![height:500px](assets/architecture_target.svg)

---

### Past year's progress

- We went to IPAC24

![bg right](assets/ipac.png)

---

### Past year's progress

- We went to IPAC24
    - and we took notes!

![bg right](assets/ipac_notes.png)

---

### Contributions ACL permission

![bg right 60%](assets/ACL_Permissions.png)

---

### "Go to timeline" button

![](assets/Go_to_timeline.png)

---

### Revision files upload errors

![height:450px](assets/Revision_error_before.png) ![height:450px](assets/Revision_error_after.png)

---

### Refactor ReviewForm

- Judge button on editing revisions
- Switching between actions on the editing timeline erases comment

![](assets/ReviewForm.png)

---

### Upload files on "Approve" judgment

![height:500px](assets/Upload_Files_Approval.png)

---

### More transparency with timeline resets

![](assets/Show_reset_revisions.png)

---

### The Future of Indico

- Greater Accessibility (a11y) 
- UI Improvements and legacy code removal
    - React-based timetable
- User Interfaces
    - Improvements in material editor (e.g. better drag and drop)
    - Responsive interfaces that work OK on mobile
- More user-centric home page
- Version 2 of the REST API: granular scopes, endpoint versioning, OpenAPI support;
- More info in our roadmap (https://getindico.io/roadmap/)

---

### [getindico.io](https://getindico.io)

![mastodon width:40px](assets/theme/mastodon.svg) [@getindico@fosstodon.org](https://fosstodon.org/@getindico)
![twitter width:40px](assets/theme/twitter.png) [@getindico](https://twitter.com/getindico)
![matrix width:30px](assets/theme/matrix.svg) [@#indico:matrix.org](https://app.element.io/#/room/#indico:matrix.org) / indico@libera.chat

![bg right:30% width: 60%](assets/hexsticker.svg)

<style scoped>
p {
    text-align: left;
}
img {
    vertical-align: middle;
}
</style>

---

<!-- _footer: '' -->
<!-- _paginate: false -->

![bg 30%](assets/theme/logo_inverted.svg)
