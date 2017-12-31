---
layout: stop
class:
  - stop
rel:
  - /rels/stop  
properties:
  name: Path
  description: The API path represents the resource you are working to make available via an API. Think about how you craft this path. Of course you should be considering RESTful principles here, but you should be thinking about how you can make it intuitive, using plain language, and something that represents what you are trying to deliver. These resources are meant for other systems and applications to put to use, but before these applications can make sense of them, a human has to make sense of them. Think about how your path will look to other users, and how it will look to others who aren't familiar with your API, and whether or not it will make sense beyond your internal group.
  image: https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-path-2.png
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
    href: /design/requests/host/
  - rel:
      - next
    href: /design/requests/action/
---
