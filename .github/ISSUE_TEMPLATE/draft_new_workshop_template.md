---
name: New Workshop
about: Use this template creating a new workshop workflow
title: ""
labels: workshop
assignees: 
---

- [ ] Identify Lesson
- [ ] Reserve a room
- [ ] Book catering
- [ ] Add course to HPC roadmap (?)
- [ ] Allocate Instructors / Helpers
- [ ] Create Collaborative Document
- [ ] Create workshop website (update _config.yml, index.md, schedule.html)
- [ ] Check links from collab doc and workshop website (maps, schedule, contact emails)
- [ ] Create entry in workshops.ncl.ac.uk
- [ ] Add to RSE team website (edit https://github.com/NewcastleRSE/rse-team-website/blob/main/_data/events.csv)
- [ ] Register with Carpentries
- [ ] Check workshop is visible (https://rse.ncldata.dev/events, https://carpentries.org/index.html, https://workshops.ncl.ac.uk/)
### 2 weeks beforehand:
- [ ] Pre-workshop survey reminder emails (send from bookings system https://workshops.ncl.ac.uk/)
### Shortly beforehand:
- [ ] Add users to JupyterHub
- [ ] Start JupyterHub server
- [ ] Stop JupyterHub server
### 3 days afterwards:
- [ ] Post-workshop Survey reminder emails

Replacement text for 'Accessability' section in index.md
-
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
