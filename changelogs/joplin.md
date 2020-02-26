# Joplin Changelog

## v2.5.1
|||
|-|-|
| **Date** | 02/25/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/580 |
| **Latest Commit Hash** | 88a9e0553ad56ce8118b2e4b072b37bb1452721b |
| **Stable?**  | y |

Added:
- Events can be filtered by cancelled in the API [PR #573](https://github.com/cityofaustin/joplin/pull/573)
- Fees on events are hidden when "event is free" is checked [#3874](https://github.com/cityofaustin/techstack/issues/3874)

Changed:
- Copy for event description [#4001](https://github.com/cityofaustin/techstack/issues/4001)


## v2.5
|||
|-|-|
| **Date** | 02/20/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/570 |
| **Latest Commit Hash** | 22e7d50221348e84460e4ce477f8fb7b53843574  |
| **Stable?**  | y |

Added:
 - We now have pytest and pytest Django set up for writing tests in Joplin.[#3986](https://github.com/cityofaustin/techstack/issues/3986)
 - We now are using react-streamfield to manage display of StreamFields in the author interface [#3851](https://github.com/cityofaustin/techstack/issues/3851)

Changed:
- Upgraded Wagtail to 2.8 [#3912](https://github.com/cityofaustin/techstack/issues/3912)
- Made some updates to the Events GraphQL schema to allow for some filtering & ordering [#3817](https://github.com/cityofaustin/techstack/issues/3817)

Fixed:
 - A docker image update caused CircleCI builds to fail, we added some parameters to our database to prevent the fail [#3976](https://github.com/cityofaustin/techstack/issues/3976)
 - A dropdown UI bug we discovered was fixed via a PR to Wagtail which was accepted as part of 2.8 

## v2.4.0
|||
|-|-|
| **Date** | 02/11/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/558 |
| **Latest Commit Hash** | 1a9ae206b0f137cf1db70b9507707e5de3921660  |
| **Stable?**  | y |

Changed:
- Made changes to the way streamfields are parsed and presented in graphql shecma in order to make sure expanded html is sent to the frontend[#3852](https://github.com/cityofaustin/techstack/issues/3852)

## v2.3.1
|||
|-|-|
| **Date** | 02/06/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/553 |
| **Latest Commit Hash** | f06f6ebbdaa96b93bf86748db999887a0d096594  |
| **Stable?**  | y |

Added:
- IA logic for publishing a page [#3823](https://github.com/cityofaustin/techstack/issues/3823)
- Require a streamfield when publishing a page [3816](https://github.com/cityofaustin/techstack/issues/3816)
- Service hours can be the same as location hours [3740](https://github.com/cityofaustin/techstack/issues/3740)
- Automated tests run with our CI builds.

Deprecated:
- No longer allow publishing from content list view as a consequence of [#3823](https://github.com/cityofaustin/techstack/issues/3823)

## v2.3.0
|||
|-|-|
| **Date** | 01/31/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/546 |
| **Latest Commit Hash** | 9abda8ea488e25831b1380b6c3d75317f17e2b75  |
| **Stable?**  | y |

Added:
- Event pages [#3814](https://github.com/cityofaustin/techstack/issues/3814)
  - Including API/Janis connections [3816](https://github.com/cityofaustin/techstack/issues/3816)

## v2.2.3
|||
|-|-|
| **Date** | 01/27/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/539 |
| **Latest Commit Hash** | 2fe999e7cd865cde636a8ad660e61ccd8a290e5f |
| **Stable?**  | y |

Added: 
- Support incremental builds from the Joplin side. [#3692](https://github.com/cityofaustin/techstack/issues/3692)
- Add service hours exceptions on the location page. [#3777](https://github.com/cityofaustin/techstack/issues/3777)

Fixed:
- Fix datadump creation bugs and missing error handling. [#3842](https://github.com/cityofaustin/techstack/issues/3842)
- Fix "View Live" for location pages. [#3743](https://github.com/cityofaustin/techstack/issues/3743)
- Improve local dev performance of Joplin.

## v2.2.2
|||
|-|-|
| **Date** | 01/22/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/531 |
| **Latest Commit Hash** | c57d0a598e0b6199214bdd36557067ea2391aea6 |
| **Stable?**  | y |

Added: 
- View live link for location pages [#3743](https://github.com/cityofaustin/techstack/issues/3743)

Fixed:
- CSS Scoping for tabs restricted to edit page only [#3719](https://github.com/cityofaustin/techstack/issues/3499)
- Make sure create content modal is on search page [#3515](https://github.com/cityofaustin/techstack/issues/3515)

## v2.2.1
|||
|-|-|
| **Date** | 01/09/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/524 |
| **Latest Commit Hash** | 068f586ffc2980aef28478ffc5351a8a0565e4c6  |
| **Stable?**  | y |

Added:
- Fix typo in load_joplin_data [3719](https://github.com/cityofaustin/techstack/issues/3719)

## v2.2.0
|||
|-|-|
| **Date** | 01/09/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/521 |
| **Latest Commit Hash** | fa934d71e79410ec2733031e01df433972e81a62  |
| **Stable?**  | y |

Added:
- Update hours exceptions to support translations
- Add steps with locations to service page steps
- Add location page chooser to contact snippet

## v2.1.2
|||
|-|-|
| **Date** | 01/08/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/520 |
| **Latest Commit Hash** | d13be2d80e80d674eae409b3e4ddf0cd0497928e  |
| **Stable?**  | y |

Added:
- Upgrade to Wagtail 2.7
- Replace Joplin microcopy for content types
- Limit "Make top-level link" to service and info pages

## v2.1.1
|||
|-|-|
| **Date** | 01/06/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/516 |
| **Latest Commit Hash** | 8f4d7e0dfea57f8cb818325567684b1e74e50305  |
| **Stable?**  | y |

Added:
- dept and official docs page style guide urls work

## v2.1.0
|||
|-|-|
| **Date** | 01/03/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/515 |
| **Latest Commit Hash** | 7fc7217f25ffe45e6f213c4ed7e784587d4f708d  |
| **Stable?**  | y |

Added:
- Inserting documents in rich text fields. [3537](https://github.com/cityofaustin/techstack/issues/3537)
- Fixes "location name" bug [3622](https://github.com/cityofaustin/techstack/issues/3622)
- Automated solution for cleaning up Heroku instances [2780](https://github.com/cityofaustin/techstack/issues/2780)
- Version control

## v minus 1
|||
|-|-|
| **Date** | 11/15/2019   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/458 |
| **Latest Commit Hash** | c30ae0c1748a16a7bbada078d81d206a66d93090  |
| **Oldest Compatible Janis** | v minus 1 |
| **Stable?**  | y |

Added:
- New SiteStructure graphql queries

Regression:
- takes a very long time to make graphql queries and build the site

## v minus 2
|||
|-|-|
| **Date** | 11/06/2019   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/452 |
| **Latest Commit Hash** | 36c7524c1c4dc4ad03d5a1a0a53f0172d37ba4ac  |
| **Oldest Compatible Janis** | v minus 2 |
| **Stable?**  | y |
