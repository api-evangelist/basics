---
layout: stop
class:
  - stop
rel:
  - /rels/stop  
properties:
  name: API Deprecation
  header: <p>This is a simple one. All APIs will eventually need to be deprecated. This is how you avoid legacy systems that have been up for over decades. Make sure the life span of each service is discussed as part of its conception, and put some details out about the expected timeline for its existence. Even if this becomes an unknown, at least you thought about it, and hopefully discussed it with others.</p><p>Here are just a few of the common building blocks I'm seeing with API operations that respect their users enough to plan for API deprecation.</p>
  footer: <p>Another valuable concept this process will introduce is the possibility that APIs can be ephemeral and maybe only exist for days, weeks, or months. With CI/CD cycles allowing for daily, weekly, and monthly code pushes, there is no reason that APIs can evolve rapidly, and deprecate just as fast. Make sure deprecation is always discussed, and thought about in context of other legacy systems, and technical debt that exists at the organization.</p></p>API deprecation is inevitable. We might as well start planning for it from day one. Every API definition upon inception should have an API deprecation target date, 12 months, 18 months, or whatever your time frame is. You may have future versions of the API in place, and in some cases extend the life of an API, but having a deprecation strategy shows you are thinking about the future, considering change, as well as considering the impact on your consumers.</p>
  image: https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-deprecation-2.png
  links:
    - title: Releases
      url:
      description: This specification defines the Sunset HTTP response header field, which indicates that a URI is likely to become unresponsive at a specified point in the future.    
    - title: Schedule
      url:
      description: Have a deprecation schedule set for each API. You can always extend, or keep versions of your API beyond the date, but at least set a minimum schedule.
    - title: Communication
      url:
      description: Make sure you have a communication strategy around deprecations. Post to the blog, Tweet out notices, and send emails.
    - title: The Sunset HTTP Header
      url: https://tools.ietf.org/id/draft-wilde-sunset-header-03.html
      description: This specification defines the Sunset HTTP response header field, which indicates that a URI is likely to become unresponsive at a specified point in the future.
  color: 27AE60    
links:
  - rel:
      - self
    href: /lifecycle/deprecation/
  - rel:
      - previous
    href: /lifecycle/training/          
---
