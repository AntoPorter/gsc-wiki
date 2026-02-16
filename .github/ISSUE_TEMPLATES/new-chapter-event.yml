name: Submit Chapter Event
description: Submit details for a new chapter event to be listed on the Global Security Community
title: "[Chapter Event] "
labels: ["chapter-event", "event-submission"]
assignees: []

body:
  - type: markdown
    attributes:
      value: |
        # Submit a Chapter Event
        
        Thank you for organizing a Global Security Community chapter event! Please fill out this form with all the required information. We will use this information to create the event page and promote it across our community.
        
        **All fields marked with an asterisk (*) are required.**

  - type: markdown
    attributes:
      value: |
        ## Section 1: Chapter Verification

  - type: input
    id: chapter_city
    attributes:
      label: Chapter City *
      description: The city where your chapter is based
      placeholder: Melbourne
    validations:
      required: true

  - type: input
    id: chapter_country
    attributes:
      label: Chapter Country *
      description: The country where your chapter is based
      placeholder: Australia
    validations:
      required: true

  - type: markdown
    attributes:
      value: |
        ## Section 2: Event Core Details

  - type: input
    id: event_title
    attributes:
      label: Event Title *
      description: The name of your event
      placeholder: "Global Security Community Meetup - Melbourne"
    validations:
      required: true

  - type: input
    id: event_date
    attributes:
      label: Event Date *
      description: The date of the event (YYYY-MM-DD format)
      placeholder: "2026-03-15"
    validations:
      required: true

  - type: input
    id: event_time
    attributes:
      label: Event Time *
      description: The start time of the event
      placeholder: "6:00 PM AEDT"
    validations:
      required: true

  - type: dropdown
    id: event_type
    attributes:
      label: Event Type *
      description: What type of event is this?
      options:
        - Meetup
        - Workshop
        - Webinar
        - Conference
        - Training Session
        - Panel Discussion
        - Networking Event
        - Social Event
        - Other
    validations:
      required: true

  - type: textarea
    id: event_description
    attributes:
      label: Event Description *
      description: Brief description of what the event will cover
      placeholder: "This meetup will focus on cloud security best practices and include talks from industry experts..."
    validations:
      required: true

  - type: markdown
    attributes:
      value: |
        ## Section 3: Venue Information

  - type: input
    id: venue_name
    attributes:
      label: Venue Name *
      description: The name of the venue
      placeholder: "Tech Hub Melbourne"
    validations:
      required: true

  - type: textarea
    id: venue_address
    attributes:
      label: Venue Address *
      description: Full address of the venue including street, city, postal code
      placeholder: |
        123 Tech Street
        Melbourne, VIC 3000
        Australia
    validations:
      required: true

  - type: input
    id: expected_attendance
    attributes:
      label: Expected Attendance *
      description: Approximate number of attendees expected
      placeholder: "50"
    validations:
      required: true

  - type: dropdown
    id: event_format
    attributes:
      label: Event Format *
      description: How will the event be delivered?
      options:
        - In-person
        - Hybrid (In-person + Virtual)
        - Virtual/Online
    validations:
      required: true

  - type: checkboxes
    id: accessibility_features
    attributes:
      label: Accessibility Features Available
      description: Select all applicable accessibility features
      options:
        - label: Wheelchair accessible
        - label: Free parking
        - label: Public transit accessible
        - label: ASL interpreter or AUSLAN interpreter
        - label: Live captions
        - label: Dietary accommodations available
        - label: Gender-neutral restrooms

  - type: markdown
    attributes:
      value: |
        ## Section 4: Infrastructure Setup

  - type: input
    id: sessionize_cfp_url
    attributes:
      label: Sessionize CFP URL *
      description: Link to your active Sessionize Call for Papers (CFP)
      placeholder: "https://sessionize.com/your-event-slug"
    validations:
      required: true

  - type: dropdown
    id: ticketing_platform
    attributes:
      label: Ticketing Platform *
      description: Which platform will you use for ticketing?
      options:
        - Eventbrite
        - Humanitix
        - Meetup
        - Ticketmaster
        - Custom website
        - Other
    validations:
      required: true

  - type: input
    id: ticketing_url
    attributes:
      label: Ticketing Registration Link *
      description: URL where people can register and purchase tickets
      placeholder: "https://www.eventbrite.com/e/your-event-id"
    validations:
      required: true

  - type: markdown
    attributes:
      value: |
        ## Section 5: Organization Committee

  - type: input
    id: primary_organizer_name
    attributes:
      label: Primary Organizer Name *
      description: Full name of the primary event organizer
      placeholder: "Jane Smith"
    validations:
      required: true

  - type: input
    id: primary_organizer_email
    attributes:
      label: Primary Organizer Email *
      description: Email address of the primary organizer
      placeholder: "jane@example.com"
    validations:
      required: true

  - type: input
    id: co_organizer_1_name
    attributes:
      label: Co-Organizer 1 Name *
      description: Full name of first co-organizer
      placeholder: "Mark Johnson"
    validations:
      required: true

  - type: input
    id: co_organizer_1_email
    attributes:
      label: Co-Organizer 1 Email *
      description: Email address of first co-organizer
      placeholder: "mark@example.com"
    validations:
      required: true

  - type: input
    id: co_organizer_1_role
    attributes:
      label: Co-Organizer 1 Role *
      description: Role or responsibility of first co-organizer
      placeholder: "Venue coordinator, Speaker liaison, etc."
    validations:
      required: true

  - type: input
    id: co_organizer_2_name
    attributes:
      label: Co-Organizer 2 Name *
      description: Full name of second co-organizer
      placeholder: "Sarah Davis"
    validations:
      required: true

  - type: input
    id: co_organizer_2_email
    attributes:
      label: Co-Organizer 2 Email *
      description: Email address of second co-organizer
      placeholder: "sarah@example.com"
    validations:
      required: true

  - type: input
    id: co_organizer_2_role
    attributes:
      label: Co-Organizer 2 Role *
      description: Role or responsibility of second co-organizer
      placeholder: "Marketing, Social media, Sponsorship, etc."
    validations:
      required: true

  - type: textarea
    id: additional_organizers
    attributes:
      label: Additional Organizers
      description: List any additional organizers with their names, emails, and roles
      placeholder: |
        Tom Wilson - tom@example.com - Volunteer coordinator
        Lisa Chen - lisa@example.com - Technical setup

  - type: markdown
    attributes:
      value: |
        ## Section 6: Agreement & Additional Information

  - type: checkboxes
    id: agreements
    attributes:
      label: Agreements *
      description: Please confirm that you agree to all of the following
      options:
        - label: The chapter event will be non-profit and open to everyone
          required: true
        - label: All attendees must adhere to the Global Security Code of Conduct
          required: true
        - label: Speakers and organizers must be respectful of the community values
          required: true
        - label: I will wait for approval from Global Security Community before promoting the event
          required: true

  - type: textarea
    id: event_page_description
    attributes:
      label: Event Page Description *
      description: Detailed description that will be used for the event page (markdown supported)
      placeholder: |
        ## Event Overview
        Join us for an engaging discussion on...
        
        ## Agenda
        - 6:00 PM - Doors open
        - 6:15 PM - Opening remarks
        - etc.
        
        ## Speakers
        - Speaker Name - Topic
    validations:
      required: true

  - type: textarea
    id: additional_notes
    attributes:
      label: Additional Notes
      description: Any other important information we should know about this event
      placeholder: "Special requirements, sponsorship details, media partners, etc."
