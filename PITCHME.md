---
marp: true
title: Indico-JACoW Collaboration
description: An overview of the Indico-JACoW collaboration
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
*Indico-JACoW Collaboration*

### Michel Succar - IT-CA-CTE (CERN)

#### BoD Meeting *(25th March 2025)*

<style scoped>
h3 {
    color: #aaa;
    font-size: 0.8em;
    font-weight: normal;
}
</style>

---

### Removed the usage of Username entirely when logging in

![height:500px](assets/Login_JACoW.png)

---

### Multiple Affiliations

<style>
  .affiliation-container {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .affiliation-text {
    flex: 1;
  }
  .affiliation-image {
    flex: 1;
    text-align: right;
  }
  .affiliation-image img {
    width: 95%; /* Adjust the size as needed */
    max-width: 600px;
  }
</style>

<div class="affiliation-container">
  <div class="affiliation-text">
    <ul>
      <li>Affiliation selection when submitting will now only allow selecting institutions from the <a href="https://ror.org/">ROR repository</a></li>
      <ul>
        <li>For requesting the addition of new institutions a <a href="https://ror.org/registry/">submission to ROR</a> is needed</li>
        <li>Nicolas Delerue reported some missing fields related to affiliations when selecting institutions (e.g. country code)</li>
      </ul>
    </ul>
  </div>
  <div class="affiliation-image">
    <img src="assets/MUltiple_Affiliations_Message.png" alt="Multiple Affiliations Message">
  </div>
</div>

---

### Integration with new mailing list service (Brevo) 🚧

![height:400px](assets/Indico_mailing_lists.png) ![height:400px](assets/Brevo_mailing_lists.png)


---

### Login-in issues

- Minor complications during Sunday night and Monday morning with some logging that has already been solved
- Reported errors on multiple requests for password reset (Most likely a User side error)

---
<!-- _footer: 'Pictured: me presenting to all of the active SPMS developers @ Music City Center, Nashville, TN, USA' -->
<!-- _paginate: false -->

![bg 100%](assets/finale.jpg)
![height:200px](assets/theme/logo_inverted.svg)
