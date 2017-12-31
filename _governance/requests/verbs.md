---
layout: stop
class:
  - stop
rel:
  - /rels/stop  
properties:
  name: Verbs
  description: HTTP verbs are the cornerstone of communicating using an API. The most common verbs GET, POST, PUT, and DELETE should be well used--don't just use GET. Make things readable, as well as writable. Then make sure and learn about the other verbs like PATCH, and OPTIONS. These verbs won't accomplish everything you are looking to do, but when you combine with your API paths, there are unlimited possibilities of what you can accomplish with your APIs. Use your verbs, and understand why they are an important aspect of your HTTP toolbox.
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
    href: /design/requests/action/
  - rel:
      - next
    href: /design/requests/parameters/
---
