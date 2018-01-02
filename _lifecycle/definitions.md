---
layout: stop
class:
  - stop
rel:
  - /rels/stop  
properties:
  name: API Definitions
  header: <p>Defining an API is the first stop along any API journey. When I say definitions, I'm not just talking about OpenAPI (fka Swagger), and specifically definitions for the surface area of your API. I'm talking about defining your idea, your goals, and the standard aspects of doing business with APIs. By API definitions, I mean having a robust toolbox of definitions for everything that is going into your API operations, from standardized dates and currencies, to common data schema, and yes to making sure there is an active OpenAPI definition for every single one of your APIs.</p><p>I'd say that 75% of the companies, organizations, institutions, and government agencies I'm talking with about APIs begin API development by coding. A very costly, and rigid approach to defining a solution to a problem. Many of the groups I know who are using OpenAPI in their operations still rely on it being generated from systems and code, and do not actually hand-define, or hand-craft the definitions for their APIs, which should be being applied across the API transit process, not just for delivering documentation. When it comes to establishing a robust API definition strategy for operations, I recommend starting with a handful of tolls and concepts.</p>
  footer: <p>There are many other tools to assist you in crafting, generating, managing, and evolving the definitions as part of your API operations. API definitions isn't just one stop along this API journey, and I will be exploring ideas for how API definitions can be applied to each stop along this API journey, in a separate line of thought that runs parallel to what I consider to be my API transit basics. These five areas represent what I think are the basics of API definitions for ANY API operations, and should be where any API provider begins their journey--by defining the moving parts of each API, and what it will do from define to deprecation.<p><p>The biggest threat to properly defining APIs is too much automation, and thinking that they only apply to one stop of the API journey. OpenAPI is not just about generating documentation. JSON Schema is not just about completing your OpenAPI definition. Not all APIs are purely JSON, and teams should be multi-lingual when it comes to the definitions they use across the API transit process API definitions are essential to not just delivering your APIs, but also communicating and supporting them, and evolving them as part of your road map. API definitions are essential to a healthy API existence, and without them, things will easily break down for a single API, and be near impossible to deliver APIs consistently at scale across any organization.</p>
  image: https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-definition.png
  links:
    - title: OpenAPI
      url: https://www.openapis.org/
      description: Ensuring there are OpenAPI definitions for ALL APIs and microservices.
    - title: JSON Schema
      url: http://json-schema.org/
      description: Ensuring there are robust JSON schema for all data in use.
    - title: Postman Collections
      url: https://www.getpostman.com/docs/postman/collections/creating_collections
      description: Postman’s proprietary format for defining APIs, which can be translated to and from OpenAPI.
    - title: API Transformer
      url: https://apimatic.io/transformer
      description: Opening up the ability to transform APIs across formats.
    - title: Multi-Format
      url:
      description: Being able to speak XML, JSON, and YAML fluently and seamlessly across groups.
  color: 27AE60
links:
  - rel:
      - self
    href: /lifecycle/definitions/   
  - rel:
      - next
    href: /lifecycle/design/      
---
