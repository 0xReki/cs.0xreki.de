---
title: Person
permalink: /Person
type: Class
subclass-of: https://schema.org/Person
subclass-chain:
  - https://schema.org/Thing
class-comment: A person (alive, dead, undead, or fictional).
properties: 
  - 
    property: /adventurerRank
    rangeIncludes: 
      - /GuildRank
    comment: The adventurer guild rank level of a person.
  - 
    property: /race
    rangeIncludes: 
      - https://schema.org/Text
    comment: The race of the person, e.g. Ailuranthrope.
super-properties:
  - 
    class: https://schema.org/Person
    properties:
      - 
        property: https://schema.org/gender
        rangeIncludes: 
          - https://schema.org/GenderType
          - https://schema.org/Text
        comment: Gender of the person.
      - 
        property: https://schema.org/height
        rangeIncludes: 
          - https://schema.org/Distance
          - https://schema.org/QuantitativeValue
        comment: The height of the person.
      - 
        property: https://schema.org/homeLocation
        rangeIncludes: 
          - https://schema.org/Place
        comment: A contact location for the person's residence.
      - 
        property: https://schema.org/jobTitle
        rangeIncludes: 
          - https://schema.org/DefinedTerm
          - https://schema.org/Text
        comment: The job title of the person.
  - 
    class: https://schema.org/Thing
    properties: 
      -
        property: https://schema.org/description
        rangeIncludes: 
          - https://schema.org/Text
        comment: A description of the person.
      - 
        property: https://schema.org/url
        rangeIncludes: 
          - https://schema.org/URL
        comment: URL of the person.
---