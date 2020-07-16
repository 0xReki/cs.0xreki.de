---
title: Plant
permalink: /Plant
type: Class
subclass-chain:
  - https://schema.org/Thing
subclass-of: /Biomass
class-comment: A plant. Vegetabilia, covers both Plantae and Fungi.
properties: 
super-properties:
  - class: /plant
    properties:
      - 
        property: /ediblePart
        rangeIncludes: 
          - https://schema.org/Text
        comment: A part of the plant that is edible.
      - 
        property: /poisonousPart
        rangeIncludes: 
          - https://schema.org/Text
        comment: A part of the plant that is poisonous.
      - 
        property: /venomousPart
        rangeIncludes: 
          - https://schema.org/Text
        comment: A part of the plant that is venomous.
      - 
        property: /rarity
        rangeIncludes: 
          - /RarityLevel
        comment: The rarity of the plant.
      - 
        property: /habitat
        rangeIncludes: 
          - https://schema.org/Place
        comment: The habitat the plant.
  - 
    class: https://schema.org/Thing
    properties: 
      -
        property: https://schema.org/name
        rangeIncludes: 
          - https://schema.org/Text
        comment: The name of the plant.
      -
        property: https://schema.org/description
        rangeIncludes: 
          - https://schema.org/Text
        comment: A description of the plant.
      - 
        property: https://schema.org/url
        rangeIncludes: 
          - https://schema.org/URL
        comment: URL of the plant.
---