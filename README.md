# Austin.gov 
The City of Austin's [Office of Design and Delivery](http://odd.austintexas.io/) is in the process of rebuilding the City’s website to improve delivery of our services to Austin residents. The new site, [Austin.gov](http://alpha.austin.gov/), is an evolving platform that will grow, adapt, and improve with user needs.

This repo is used for centralized project management of the project for the following teams:
  - [Content](https://github.com/cityofaustin/techstack#boards?labels=team%3A%20content)
  - [Design + Research](https://github.com/cityofaustin/techstack#boards?labels=team%3A%20design%2Fresearch&repos=118780243)
  - [Dev](https://github.com/cityofaustin/techstack#boards?labels=team%3A%20dev)
  - [Product](https://github.com/cityofaustin/techstack#boards?labels=team%3A%20product)

This includes work related to:
  - [Janis](https://github.com/cityofaustin/janis) - Austin.gov's resident-facing interface for service delivery
  - [Joplin](https://github.com/cityofaustin/joplin) - Austin.gov's staff-facing interface for content creation and maintenance
  - [Animal Services Foster Form Prototype](https://github.com/cityofaustin/prototypeform)  
  - [Forms Service API](https://github.com/cityofaustin/form-service-api) - API to connect the US Forms System to external applications and services
  - [Forms Service Deploy](https://github.com/cityofaustin/form-service-deploy) -  Tool to deploy forms using shared components 
  - [Form Large File Upload](https://github.com/cityofaustin/form-service-large-file-upload) - Large file uploader for the Form Service API
  - [USFS Components](https://github.com/cityofaustin/usfs-components) - Custom components for the US Forms System 
  - [USFS Schema blocks](https://github.com/cityofaustin/usfs-schema-blocks) - Sets of commonly used questions for the US Forms System
  - Office of Police Oversight: [Complaint Form](https://github.com/cityofaustin/officer-complaint-form), [Praise Form](https://github.com/cityofaustin/officer-thank-form), [Form Chapters](https://github.com/cityofaustin/officer-form-chapters)  

Our team is using Zenhub for agile project management. In order to view our Kanban board (aka Trello-style), you need to download the [Zenhub extension](https://www.zenhub.com/extension) for your browser. See our guide to how we use Zenhub [here](https://docs.google.com/presentation/d/1HUC70Tlf41XKe_ESRJMWcPlpTdpiKeld_lTRNoLC7Y4/edit#slide=id.p). 

![](/img/zenhub_board.png)

## Adding an issue
There are several issue templates available to start with:
 - [Bug report](https://github.com/cityofaustin/techstack/issues/new?template=bug_report.md)
 - [Feature request](https://github.com/cityofaustin/techstack/issues/new?template=feature_request.md)
 - [Meeting](https://github.com/cityofaustin/techstack/issues/new?template=meeting.md)
 
If none of these suit your needs, [create a regular issue](https://github.com/cityofaustin/techstack/issues/new) and we'll sort it out. 

## Grooming

In preparation for every Sprint Planning, the backlog of issues needs to be groomed. Issues that are likely to be pulled into one of the next few sprints should have
  - One and only one _Team_ label - unless it is a meeting
  - At least one _Feature_ or _Content Type_ label
  - T-shirt size

If completion of an issue is blocked by another issue, add a dependency:

![](/img/dependency.png)

If the blocking issue isn't in Github yet, create it and make sure to add the appropriate _Team_ label and then add the dependency. 
