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
*two decades of history, many more to come*

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

![bg left 90% drop-shadow:0,5px,10px,rgba(0,0,0,.4)](assets/indico_main_page.png)

### ![width:200px](assets/theme/logo_inverted.svg)

 - **Event Management** System
 - **Collaborative effort** - MIT License
 - Core Developed at **CERN**
 - With contributions from the **United Nations**, **Max-Planck Institute for Physics** and many others!
 - **70+ developers** over the years

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

<style scoped>
section {
    color: #fff;
    text-shadow: 0 0 10px #000;
}
a {
    color: #bbb;
}
ul {
    background-color: rgba(0,0,0,0.2);
}
</style>

---

![width:500px](assets/un_pres_3.png)
![width:500px](assets/un_pres_1.png) ![width:500px](assets/un_pres_2.png)

---


![bg left 50%](assets/vase.svg)

### History

 - **1999** - **CDS Agenda**
 - **2002** - **EU Project**
 - **2004** - Indico in **Production**
 - **2007** - **Room Booking**
 - **2008** - **Interface overhaul**
 - **2013** - First **Workshop**
 - **2015** - The **UN** starts using it
 - **2017** - Indico 2.0 (**rewrite**)
 - **2021** - Indico 3.0 (**Python 3**)
 - **2023** - **1 Million Events** surpassed at CERN 🎉
 - **2024** - **20 years!**

<style scoped>
section {
    font-size: 1.7em;
}
</style>

---

![width:700px](assets/fp5.png)

https://cordis.europa.eu/project/id/IST-2001-34306

---

### Team

![height:400px drop-shadow:0,5px,10px,rgba(0,0,0,.4)](assets/team.png) ![height:200px drop-shadow:0,5px,10px,rgba(0,0,0,.4)](assets/team_lead.png)

---

### CERN

- **~17.000** people on campus <!-- 2022 stats -->
- **~230** meeting rooms
- **100.000+** events/year
  * **1.000.000+** events total
- (Distributed) Meetings
- Conferences, workshops

![bg left](assets/cern_science_gateway_above.png)

---

### Adoption at CERN


![height:400px](assets/event_stats_cern.svg)

---

![](assets/event_types.svg)

---
<style scoped>
    section {
        justify-content: start;
    }
</style>

![bg 80% drop-shadow:0,5px,10px,rgba(0,0,0,.4)](assets/indico_rb.png)

---

### Philosophy

 - "General purpose" **core**
 - Extension through **plugins** 🧩
 - **Themes** 🎨 (customization)

![bg left](assets/cogs.jpg)

---
![bg right](assets/hood.jpg)

### Under the Hood

 - Python 3 🐍
 - PostgreSQL 🐘
 - Flask
 - Celery
 - SQLAlchemy
 - React
 - Semantic UI React
 - *among many others!*

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
    h3 {
        margin-top: 1em;
    }
</style>

### Hot desking

![bg width:60% drop-shadow:0,5px,10px,rgba(0,0,0,.4)](assets/burotel.png)

---
<style scoped>
    section {
        justify-content: start;
    }
</style>

### Themes / Customization

![bg width:55% drop-shadow:0,5px,10px,rgba(0,0,0,.4)](assets/ilcagenda.png)

---
<style scoped>
    section {
        justify-content: start;
    }
</style>

### Themes / Customization

![bg width:50% drop-shadow:0,5px,10px,rgba(0,0,0,.4)](assets/meeting.png)

---
<style scoped>
    section {
        justify-content: start;
    }
</style>

### Themes / Customization

![bg width:50% drop-shadow:0,5px,10px,rgba(0,0,0,.4)](assets/conference.png)

---
<style scoped>
    section {
        justify-content: start;
    }
</style>

### Check-in App (PWA)

![bg width:65% drop-shadow:0,5px,10px,rgba(0,0,0,.4)](assets/checkin_app.png)

---
<style scoped>
    ul > li > ul {
        font-size: 0.8em;
    }

    ul > li > ul > li {
        margin-bottom: 0;
    }

    ul > li {
        margin-bottom: 1em;
    }
</style>

### How to get Indico?

 * 🏃🏻 **Option 1: run it yourself**
    - **Pros:** full control, data sovereignty/privacy, cheap (if you have internal IT know-how)
    - **Cons:** may become expensive if there is no know-how
 * 🖥️ **Option 2: get someone to run it on your own infrastructure**
    - **Pros:** full control, data sovereignty/privacy, cheap (if you have your own IT infrastructure)
    - **Cons:** you still need to have your own IT infrastructure
 * ☁️ **Option 3: get someone to host/run it for you (cloud)**
    - **Pros:** most likely cheaper than running your own IT
    - **Cons:** data sovereignty/privacy

---
### Some known providers
 - Mythic Beasts
 - S2Innovation
 - unconventional.dev (CERN spin-off)

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

### Contributions permission

![bg right 60%](assets/ACL_Permissions.png)

---

### UI/UX improvements

![height:300px](assets/Revision_error_before.png) ![height:300px](assets/Revision_error_after.png)

![height:200px](assets/search_external.png)

---

### Improvements on Reviewing

- Judge button on editing revisions
- Switching between actions on the editing timeline erases comment
- Green-dot with new files

![height:150px](assets/ReviewForm.png) ![height:300px](assets/Upload_Files_Approval.png)

---

### More transparency on QA Fails

![](assets/Show_reset_revisions.png)

---

### Multiple affiliations

![height:220px](assets/multiple_affiliations_1.png) ![height:220px](assets/multiple_affiliations_2.png)
![height:220px](assets/multiple_affiliations_3.png)

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

<!-- _footer: '' -->

![bg 120%](assets/indico_workshop_35.jpg)

### Come to our workshop!

*Date TBA; sometime in March*

&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;

<style scoped>
section {
    text-shadow: 0 0 10px #fff;
}
h3, em {
    color: #000;
    background-color: rgba(0,0,0,0.2);
}
</style>

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
