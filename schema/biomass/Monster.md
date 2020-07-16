---
title: Monster
permalink: /Monster
type: Class
subclass-chain:
  - https://schema.org/Thing
subclass-of: /Biomass
class-comment: A monster (alive, dead, or undead).
properties: 
  - 
    property: /diet
    rangeIncludes:
      - /DietType
    comment: The type of diet of the monster
  - 
    property: /weakness
    rangeIncludes: 
      - /ElementType
    comment: A elemental weakness of the monster.
  - 
    property: /resistance
    rangeIncludes: 
      - /ElementType
    comment: A elemental resistance of the monster.
  - 
    property: /threatLevel
    rangeIncludes: 
      - /GuildRank
    comment: The threat level of monster.
super-properties:
  - class: /Biomass
    properties:
      - 
        property: /ediblePart
        rangeIncludes: 
          - https://schema.org/Text
        comment: A part of the monster that is is edible.
      - 
        property: /poisonousPart
        rangeIncludes: 
          - https://schema.org/Text
        comment: A part of the monster that is is poisonous.
      - 
        property: /venomousPart
        rangeIncludes: 
          - https://schema.org/Text
        comment: A part of the monster that is is venomous.
      - 
        property: /rarity
        rangeIncludes: 
          - /RarityLevel
        comment: The rarity of the monster.
      - 
        property: /habitat
        rangeIncludes: 
          - https://schema.org/Place
        comment: The habitat the monster.
  - 
    class: https://schema.org/Thing
    properties: 
      -
        property: https://schema.org/name
        rangeIncludes: 
          - https://schema.org/Text
        comment: The name of the monster.
      -
        property: https://schema.org/description
        rangeIncludes: 
          - https://schema.org/Text
        comment: A description of the monster.
      - 
        property: https://schema.org/url
        rangeIncludes: 
          - https://schema.org/URL
        comment: URL of the monster.
---