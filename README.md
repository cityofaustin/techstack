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
## ZenHub
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
  - One [_Team_](https://github.com/cityofaustin/techstack/labels?utf8=%E2%9C%93&q=Team+) label - there should be separate issues assigned to each team that speak specifically to the work they will do, e.g. "Design Service Page contact component" for design and "Implement Service Page contact component" for dev, rather than "Service Page contact component" assigned to both disciplines. The exception to this rule is a meeting where both teams will contribute the same amount of time/effort. In this case, assign all teams and the _Meeting_ label.  
  - At least one [_Feature_](https://github.com/cityofaustin/techstack/labels?utf8=%E2%9C%93&q=Feature%3A) or [_Content Type_](https://github.com/cityofaustin/techstack/labels?utf8=%E2%9C%93&q=Content+Type%3A+) label - unless it is _Site Content_ (content to be transitioned onto Austin.gov) or _Project Communication_ (Medium posts, conference presentations, etc.)
  - One [_Size_](https://github.com/cityofaustin/techstack/labels?utf8=%E2%9C%93&q=size%3A) label - relative estimation of effort 
  - An estimate - in order to calculate [velocity](https://github.com/cityofaustin/techstack#workspaces/office-of-design-and-delivery-5a78b88e1ce69f3510b678ef/reports/velocity); estimates translate directly from t-shirt size: XS=1, S=2, M=3, L=5, XL=8 

If completion of an issue is blocked by another issue, add a dependency:

![](/img/dependency.png)

If the blocking issue isn't in Github yet, create it and make sure to add the appropriate _Team_ label and then add the dependency. 

## Logging notable changes
We're going to adopt changelogs for projects that have passed major releases, in order to help track notable changes for clients and other interested parties. 
Roughly following this format: https://keepachangelog.com/en/0.3.0/
Checkout the changelogs folder for more!

### How do I make a good changelog?

Guiding Principles:

- Changelogs are for humans, not machines.
- There should be an entry for every single version.
- The same types of changes should be grouped.
- Versions and sections should be linkable.
- The latest version comes first.
- The release date of each version is displayed.
- Mention whether you follow Semantic Versioning.

Types of changes:

- **Added** for new features.
- **Changed** for changes in existing functionality.
- **Deprecated** for soon-to-be removed features.
- **Removed** for now removed features.
- **Fixed** for any bug fixes.
- **Security** in case of vulnerabilities.
