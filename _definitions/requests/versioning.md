---
layout: stop
class:
  - stop
rel:
  - /rels/stop  
properties:
  name: Versioning
  description: Establish, and stick to a common versioning strategy, and use throughout API evolutions. Consider putting all versioning information within headers.
entities:
  - class:
      - image
    rel:
      - /rels/image
    properties:
      - name: path Image
        url: /image/
  - class:
      - video
    rel:
      - /rels/video
    properties:
      - name: path Video
        url: /video/
        embed: <embed>
    links:
      - rel:
          - self
        href: http://api.x.io/customers/pj123
actions:
  - name: view-item
    title: View Item
    method: POST
    href: /stop/view/
    type: application/x-www-form-urlencoded
    fields:
      - name: name
        type: hidden
        value: 'path'
      - name: user
        type: hidden
        value: ''        
links:
  - rel:
      - self
    href: /design/requests/versioning/
  - rel:
      - area
    href: /design/area/      
  - rel:
      - line
    href: /design/requests/          
  - rel:
      - previous
    href: /design/requests/body/
  - rel:
      - next
    href: /design/requests/pagination/
---