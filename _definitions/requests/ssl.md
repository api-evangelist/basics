---
layout: stop
class:
  - stop
rel:
  - /rels/stop  
properties:
  name: SSL
  description: Transport Layer Security (TLS) and its predecessor, Secure Sockets Layer (SSL), both of which are frequently referred to as 'SSL', are cryptographic protocols designed to provide communications security over a computer network. Always support TLS / SSL by default when it comes to API operations, if at all possible.
entities:
  - class:
      - image
    rel:
      - /rels/image
    properties:
      - name: SSL Image
        url: /image/
  - class:
      - video
    rel:
      - /rels/video
    properties:
      - name: SSL Video
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
        value: 'SSL'
      - name: user
        type: hidden
        value: ''        
links:
  - rel:
      - self
    href: /design/requests/ssl/
  - rel:
      - area
    href: /design/area/      
  - rel:
      - line
    href: /design/requests/          
  - rel:
      - next
    href: /design/requests/host/
---