---
title: Biomass
permalink: /Biomass
type: Class
subclass-of: https://schema.org/Thing
class-comment: The most generic type of plant, mushroom and animal life.
properties: 
  - 
    property: /ediblePart
    rangeIncludes: 
      - https://schema.org/Text
    comment: A part of the biomass that is edible.
  - 
    property: /poisonousPart
    rangeIncludes: 
      - https://schema.org/Text
    comment: A part of the biomass that is poisonous.
  - 
    property: /venomousPart
    rangeIncludes: 
      - https://schema.org/Text
    comment: A part of the biomass that is venomous.
  - 
    property: /rarity
    rangeIncludes: 
      - /RarityLevel
    comment: The rarity of the biomass.
  - 
    property: /habitat
    rangeIncludes: 
      - https://schema.org/Place
    comment: The habitat of the biomass.
    
super-properties:
  - 
    class: https://schema.org/Thing
    properties: 
      -
        property: https://schema.org/name
        rangeIncludes: 
          - https://schema.org/Text
        comment: The name of the biomass.
      -
        property: https://schema.org/description
        rangeIncludes: 
          - https://schema.org/Text
        comment: A description of the biomass.
      - 
        property: https://schema.org/url
        rangeIncludes: 
          - https://schema.org/URL
        comment: URL of the biomass.
---