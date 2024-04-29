---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Welcome...
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: markdown
    id: research
    content:
        title: "Research"
        text: |-
            {{< readfile file="/research/research.md" markdown="true" >}}

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Feel free to reach out me:
      # Contact (add or remove contact options as necessary)
      email: t.stahl@econ.uni-frankfurt.de
      phone: +49 (69) 798-34801
      #appointment_url: 'https://calendly.com'
      address:
        street: Theodor-W.-Adorno-Platz 4
        city: Frankfurt am Main
        #region: CA
        postcode: '60323'
        country: Germany
        country_code: DE
      directions: Enter RuW building, hold right and take the elevator or stairs to office 4.222 on the fourth floor.
      #office_hours:
       # - 'Monday 10:00 to 13:00'
       # - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '50.12888'
        longitude: '8.66459'  
      contact_links:
#        - icon: twitter
#          icon_pack: fab
#          name: DM Me
#          link: 'https://twitter.com/Twitter'
#        - icon: skype
#          icon_pack: fab
#          name: Skype Me
#          link: 'skype:echo123?call'
#        - icon: video
#          icon_pack: fas
#          name: Zoom Me
#          link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true

---
