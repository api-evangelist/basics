---
layout: stop
class:
  - stop
rel:
  - /rels/stop  
properties:
  name: Action
  description: Allow for standard actions to be taken across resource, but also reflect how APIs will be experienced, providing meaningful action to be taken around any API.
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
    href: /design/requests/path/
  - rel:
      - area
    href: /design/area/     
  - rel:
      - line
    href: /design/requests/          
  - rel:
      - previous
    href: /design/requests/path/
  - rel:
      - next
    href: /design/requests/verbs/
---