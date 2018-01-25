# DevelopmentProcess
This document has been produced for all developers working at Gooey, and explains what is expected in regards to project processes.

In regards to coding standards please see Gooey Coding Standards.

---
## Table of contents
- [Pre-development](#pre-development)
- [During-development](#during-development)
- [Post-development](#post-development)
- [Handover](#handover)
- [Standards](#standards)
- [Deadlines](#deadlines)
---

## Pre-development

Before coding commences you should:

- Look through all designs including any for mobile and tablet. This will help you understand how some elements may need to be built (i.e. things may turn into a slider on mobile), thus saving time later.
- Read any brief's and notes in the project folder.
- Set up a project on Codebase and assign yourself, development manager and project manager.
- Request any further designs or assets that you need from the project manager (via Codebase).
- Agree timings with the development manager (log on Codebase, create ticket entitled 'Timings')
- Plan how you are going to tackle the project, any help you may need and from whom and book this time in via development manager (request via Codebase).

---

## During-development

- All questions to development manager or project manager to be logged via Codebase.
- If you become stuck on an element, and need support, in the first instance log a ticket on Codebase with the development manager or the developer you would like to assist. They will then shedule in time to help. Use your descrection with this one, if it's a quick question or a quick fix, no need to log it, but if it's a task that will take some time please log it via codebase.
- If you think you are going to miss your deadline you must let the development manager and project manager know at the earliest opportunity. i.e. On the day it is due is not acceptable.
- If working from home the deadline must be met as agreed during pre-development.

---

## Post-development

When you have finished development, and before you send to the development manager, you must:

### Check work against designs

- Get designs open on one screen, website on the other, and check each page to ensure nothing has been missed.
- Also check that all fonts, font weights, heights, widths, margins, padding, colours have been accurately followed.

### Test

- Ensure the site has been tested in all major browsers, and back to IE10 (unless otherwise specified).
- Ensure you have tested the site in devices (phone and tablet). Use actual devices too.
- Ensure the site passes W3C validation (bar i.e. WordPress elements causing issues, eg. Gravity Forms)
- Ensure the site scores well for speed (Google Speed Test).

### WordPress

- Ensure that the CMS is easy to use and pages can be built easily.
- Ensure the site has a 404 error page.
- Ensure that the htaccess has the below code in it.

```
<Files "xmlrpc.php">
Order Allow,Deny
deny from all
</Files>
```

The project will be QA'd however by adhering to the above there should be minimal QA amends.

---

## Handover

When all the post-development checks are done, and you are 100% happy that the site is ready to go to the client, please send a handover via codebase to the development manager.

- Include all links to the pages you have developed, specifically the pages that we were supplied designs for.
- List all plugins used and technologies.
- Any other notes in regards to the CMS, functionality etc that you think is note-worthy.

---

## Standards

Please do not send anything to be QA'd that is not fit for purpose.

Anything that is sent and does not meet acceptable standards will be sent back without explanation for you to complete in your own time.

All our work should be of a high standard, if not we will loose clients, thus lost revenue.

---

## Deadlines

Deadlines need to be met at all times unless agreed otherwise.

---

### Produced by James Holloway - Gooey (Last updated 25/01/2018)

