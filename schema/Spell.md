---
title: Spell
permalink: /Spell
type: Class
subclass-of: https://schema.org/Intangible
subclass-chain:
  - https://schema.org/Thing
class-comment: A spell
properties: 
  - 
    property: /element
    rangeIncludes: 
      - /ElementType
    comment: Elemental types of Magic associated with a spell
  - 
    property: /effect
    rangeIncludes: 
      - /EffectType
    comment: Effect types of Magic associated with a spell
super-properties:
  - 
    class: https://schema.org/Thing
    properties: 
      -
        property: https://schema.org/description
        rangeIncludes: 
          - https://schema.org/Text
        comment: A description of the item.
      - 
        property: https://schema.org/url
        rangeIncludes: 
          - https://schema.org/URL
        comment: URL of the item.
    
---