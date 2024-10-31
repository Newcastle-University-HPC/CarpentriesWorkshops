---
name: New Workshop
about: Use this template creating a new workshop workflow
title: ""
labels: workshop
assignees: 
---

- [ ] Identify Lesson
- [ ] Reserve a room
- [x] _Book catering - N/A since financial restrictions Oct 2024_
- [ ] Add course to HPC roadmap
- [ ] Allocate Instructors / Helpers
- [ ] Create Collaborative Document (As rseteam.ncl@gmail.com, create from template & replace YYYY-MM-DD-NCL)
- [ ] Create workshop website (update _config.yml, index.md, schedule.html)
- [ ] Set up Audience Interaction tool 
- [ ] Check links from **collab doc** and workshop website (maps, schedule, contact emails)
- [ ] Create ocurrence of this workshop in workshops.ncl.ac.uk
  - [ ] update reminder email to request participants bring own cup
- [ ] Add to RSE team website (edit [the csv file](https://github.com/NewcastleRSE/rse-team-website/blob/main/_data/events.csv))
- [ ] Register with Carpentries
- [ ] Check workshop is visible (https://rse.ncldata.dev/events, https://carpentries.org/index.html, https://workshops.ncl.ac.uk/)

### 2 weeks beforehand:
- [ ] Pre-workshop survey reminder emails (send from bookings system https://workshops.ncl.ac.uk/ _or use mail merge from ? email address_)
- [ ] Create / locate PPT with [exercises for the workshop](https://newcastle.sharepoint.com/sites/workshoporganisation/Shared%20Documents/Forms/AllItems.aspx?id=%2Fsites%2Fworkshoporganisation%2FShared%20Documents%2FWorkshop%20Admin%2FExercisesLessons)
- [ ] Ensure the correct instructors and helpers are shown at https://carpentries.org/workshops/#workshop-core
### Shortly beforehand:
- [ ] copy attendees list from workshops.ncl.ac.uk to spreadsheet in [Sharepoint]( https://newcastle.sharepoint.com/:f:/r/sites/workshoporganisation/Shared%20Documents/Workshop%20Admin/Room%20Bookings%20and%20Attendance?csf=1&web=1&e=bOyGg2)
- [ ] Add users to JupyterHub
- [ ] Calendar invites to instructors/helpers from workshoporganisation@group.newcastle.ac.uk
- [ ] Request self-catering tea/coffee from pgrdp (instead of catering)
- [ ] Print 'cheat sheets'
#### on the day
- [ ] Start JupyterHub server
- [ ] mark attendees present in workshops.ncl.ac.uk
- [ ] Stop JupyterHub server


### 3 days afterwards:
- [ ] Attendee list from hackmd.io collab doc to pgrdp@newcastle.ac.uk
- [ ] Remove attendee list from hackmd.io
- [ ] Add no-shows to no-show spreadsheet
- [ ] ? optional ? Post-workshop Survey reminder emails to attendee list
  
  
  
  



## Replacement text for 'Accessability' section in index.md
replace lines 201-227 ({% if online == "false" %} section and para with Carpentries links)

with 188-217 from 2024-09-24-NCL

{% comment %}
ACCESSIBILITY

Modify the block below if there are any barriers to accessibility or
special instructions.
{% endcomment %}
<p id="accessibility">
  <strong>Accessibility:</strong>
{% if online == "false" %}
  We are committed to making this workshop
  accessible to everybody.  For workshops at a physical location, the workshop organizers have checked that:
</p>
<ul>
  <li>The room is wheelchair / scooter accessible.</li>
  <li>Accessible restrooms are available.</li>
</ul>
<p>
  Materials will be provided in advance of the workshop and
  large-print handouts are available if needed by notifying the
  organizers in advance.  If we can help making learning easier for
  you (e.g. sign-language interpreters, lactation facilities) please
  get in touch (using contact details below) and we will
  attempt to provide them.
</p>
{% else %}
  We are dedicated to providing a positive and accessible learning environment for all. Please
  notify the instructors in advance of the workshop if you require any accommodations or if there is
  anything we can do to make this workshop more accessible to you.
</p>
{% endif %}


### Audience interaction tools:  
https://www.mentimeter.com/, https://claper.co/, https://ncl.vevox.com/
