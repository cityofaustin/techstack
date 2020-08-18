# Joplin Changelog

## v3.7.1
|||
|-|-|
| **Date** | 08/18/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/798 |
| **Latest Commit Hash** | 74e13f882d463ee80f01b96cff658a3837a5440f |
| **Stable?**  | y |

Added:
- Translation reports are now sent via automated emails [#4695](https://github.com/cityofaustin/techstack/issues/5695)
Updated:
- Wagtail upgraded to v2.9.3, upgraded other packages with security vulenerabilities [#4375](https://github.com/cityofaustin/techstack/issues/4375)

## v3.7.0
|||
|-|-|
| **Date** | 08/18/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/795 |
| **Latest Commit Hash** | 24aba57839f5bff00e74a86215d78bfe67df7fb0 |
| **Stable?**  | y |

Added:
- News list items so Janis can show news on department pages [#4404]

## v3.6.0
|||
|-|-|
| **Date** | 08/11/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/793 |
| **Latest Commit Hash** | 24aba57839f5bff00e74a86215d78bfe67df7fb0 |
| **Stable?**  | y |

Added:
- New User welcome email messages [#4397](https://github.com/cityofaustin/techstack/issues/4397)
- Links can be addded to OfficialDocumentCollection description [#4747](https://github.com/cityofaustin/techstack/issues/4747)
- Links can be addded to Location hours [#4758](https://github.com/cityofaustin/techstack/issues/4758)
- "Body" field for OfficialDocumentPage [#4641](https://github.com/cityofaustin/techstack/issues/4641)

## v3.5.0
|||
|-|-|
| **Date** | 07/29/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/787 |
| **Latest Commit Hash** | 3d905d7c85134d9344e650c597c9486f5be982b |
| **Stable?**  | y |

Added:
- Adds the department resolver to OfficialDocumentPages and OfficialDocumentPages to preview [#4591](https://github.com/cityofaustin/techstack/issues/4591)

## v3.4.3
|||
|-|-|
| **Date** | 07/28/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/785 |
| **Latest Commit Hash** | d9f1f0b7c716921a1e1444429d43ec12ead64443 |
| **Stable?**  | y |

Changed:
- Enable password reset [#4402](https://github.com/cityofaustin/techstack/issues/4402)

## v3.4.2
|||
|-|-|
| **Date** | 07/27/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/784 |
| **Latest Commit Hash** | cb8cca8d8429c2066c21b92075f9ee35b0fa7045 |
| **Stable?**  | y |

Changed:
- Removes SEO tab and move slug field to edit page [#4581](https://github.com/cityofaustin/techstack/issues/4581)

## v3.4.1
|||
|-|-|
| **Date** | 07/26/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/783 |
| **Latest Commit Hash** | 21cebacaa26753776a6ddee60155a176905f2b24 |
| **Stable?**  | y |

Changed:
- Removes old OfficialDocumentPage and OfficialDocumentPageDocument models [#4602](https://github.com/cityofaustin/techstack/issues/4602)

## v3.4.0
|||
|-|-|
| **Date** | 07/17/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/779 |
| **Latest Commit Hash** | 21cebacaa26753776a6ddee60155a176905f2b24 |
| **Stable?**  | y |

Added:
- Previews for new Official Documents Collection [#4621](https://github.com/cityofaustin/techstack/issues/4621)
- Automated sync_data script
- remove CMS_DOCS environment variable, document url address information is handled by Joplin

## v3.3.0
|||
|-|-|
| **Date** | 07/13/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/775 |
| **Latest Commit Hash** | dd974de47638ff0b388391f2a5c561fe8335a61b |
| **Stable?**  | y |

Added:
- New Models: Official Document Collections and Official Document Pages (https://github.com/cityofaustin/joplin/pull/771)

Changed:
- Make publish succeeded endpoint asynchronous (https://github.com/cityofaustin/joplin/pull/774)

## v3.2.14
|||
|-|-|
| **Date** | 07/08/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/770 |
| **Latest Commit Hash** | 0dcc0ad4022cb1b2a6bd25ed587f15e2fd4cf72a |
| **Stable?**  | y |

Fixed:
- Styleguide URLs were changed [#4600](https://github.com/cityofaustin/techstack/issues/4600)

## v3.2.13
|||
|-|-|
| **Date** | 07/03/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/766 |
| **Latest Commit Hash** | c1dfe98b485b5801a6db593c4fc00fb5063d41cc |
| **Stable?**  | y |

Fixed:
- Spanish top pages 404 [#4503](https://github.com/cityofaustin/techstack/issues/4503)

## v3.2.12
|||
|-|-|
| **Date** | 06/26/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/761 |
| **Latest Commit Hash** | 26850e725244ea9abbe9a4ce5eed520c48cf8915 |
| **Stable?**  | y |

Fixed:
- Page unpublishing statuses display correctly https://github.com/cityofaustin/techstack/issues/4559

## v3.2.11
|||
|-|-|
| **Date** | 06/24/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/758 |
| **Latest Commit Hash** | dfbe3226b6766afede3837d4908836245e65c8b8 |
| **Stable?**  | y |

Added:
- Make a report containing newly published pages that need translations cityofaustin/techstack#4495

Fixed:
- Bugs with template.env and make_pycharm_vars

Removed:
- .idea/RunConfigurations/*

## v3.2.10
|||
|-|-|
| **Date** | 06/24/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/757 |
| **Latest Commit Hash** | 2d9f76e1baeb22da34d8073127440f3bca58604b |
| **Stable?**  | y |

Fixed:
- Fixed bugs with publish notification banner https://github.com/cityofaustin/techstack/issues/4541

## v3.2.9
|||
|-|-|
| **Date** | 06/23/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/753 |
| **Latest Commit Hash** | c03d92cfdb8e98f8d143a90fc1c77e3173ab5055 |
| **Stable?**  | y |

Added:
- Postgres v12 support on local builds
- Improved documentation for template.env env variables

## v3.2.8
|||
|-|-|
| **Date** | 06/22/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/751 |
| **Latest Commit Hash** | 2e7a550c2aa4430cf86d60ba1f528e225ef35185 |
| **Stable?**  | y |


Added:
- Publishing/Unpublishing notification https://github.com/cityofaustin/techstack/issues/4356
- PRs use postgres v12
- Fixtures have revisions and are set as "published" if they are "live".

## v3.2.7
|||
|-|-|
| **Date** | 06/15/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/748 |
| **Latest Commit Hash** | 5f0acdd8d7cbaeefab941ba968be6dc08a8adde7 |
| **Stable?**  | y |


Added:
- Prevent authors from seeing link to add Topics or Topic Collections in Create Content Modal
https://github.com/cityofaustin/techstack/issues/4400


## v3.2.6
|||
|-|-|
| **Date** | 06/11/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/745 |
| **Latest Commit Hash** | c36eb93cdc261bc564ce1f5ab24a84f9b11d05aa |
| **Stable?**  | y |


Added:
- Group permission fixtures are loaded for editors and moderators groups
https://github.com/cityofaustin/techstack/issues/4383

## v3.2.5
|||
|-|-|
| **Date** | 06/09/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/743 |
| **Latest Commit Hash** | c7de6fd5f010d3ba9edaec764e2a9ff8db54a71f |
| **Stable?**  | y |


Added:
- Moderators and Editors are prevented from viewing pages outside their departments https://github.com/cityofaustin/techstack/issues/4099


## v3.2.4
|||
|-|-|
| **Date** | 06/06/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/741 |
| **Latest Commit Hash** | 768a955f27eaaaa7d41772a807fef313a4bb80e2c |
| **Stable?**  | y |


Added:
- Moderators and Editors are limited to only view pages within their departments in Joplin search view https://github.com/cityofaustin/techstack/issues/4097



## v3.2.3
|||
|-|-|
| **Date** | 06/01/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/738 |
| **Latest Commit Hash** | 77dde577fc57b740544262e43cfaf79266511c7d |
| **Stable?**  | y |

Fixed:
- We were getting spanish slugs even though janis doesn't support them yet https://github.com/cityofaustin/techstack/issues/4449

Added:
- Tests around page creation permissions https://github.com/cityofaustin/techstack/issues/4098


## v3.2.2
|||
|-|-|
| **Date** | 05/20/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/729 |
| **Latest Commit Hash** | 4f3c66fc7d3665eb2cdcc041d4afedcafef99518 |
| **Stable?**  | y |

Fixed:
- Fixed a few errors that would pop up if parts of forms werent filled out. https://github.com/cityofaustin/techstack/issues/4380

## v3.2.1
|||
|-|-|
| **Date** | 05/18/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/730 |
| **Latest Commit Hash** | 113638e58c8c51c027e2ceec8edccaebe7b1c26f |
| **Stable?**  | y |

Fixed:
- Users can now edit their own information. https://github.com/cityofaustin/techstack/issues/4371

## v3.2.0
|||
|-|-|
| **Date** | 05/15/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/727 |
| **Latest Commit Hash** | 3b71bfcb17379050d0265b606511fc50dddfe939 |
| **Stable?**  | y |

Added:
- News pages. https://github.com/cityofaustin/techstack/issues/4355

## v3.1.0
|||
|-|-|
| **Date** | 05/13/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/725 |
| **Latest Commit Hash** | 825ed19ab52d10bcac7816b0180a26e2de29d97c |
| **Stable?**  | y |

Added:
- Related events to Information, Service and Location pages. https://github.com/cityofaustin/techstack/issues/4214 and https://github.com/cityofaustin/techstack/issues/4215


## v3.0.1
|||
|-|-|
| **Date** | 05/01/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/720 |
| **Latest Commit Hash** | 745bc1fd95cebe90c76acba9018017673cae9876 |
| **Stable?**  | y |

Fixed:
- How to temporarily remove automated Production backups from circleci in order for v3 to be pushed to a database-less production environment.


## v3.0.0
|||
|-|-|
| **Date** | 05/01/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/719 |
| **Latest Commit Hash** | 7eefce9dd560b89ff91f3e5d001268e4070acfc9 |
| **Stable?**  | y |

Refactored:
- Most of the things https://github.com/cityofaustin/techstack/issues/4174

Added:
- Added PageImporter to move pages between v2 to v3 environments
- Added unit tests


## v2.9.0
|||
|-|-|
| **Date** | 04/22/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/702 |
| **Latest Commit Hash** | 49b15f98716d59c57695f67d5622ba29bf82d4a3 |
| **Stable?**  | y |

Added:
- Page revision API goodies to support importer

Removed:
- Mapblock logic from API to support importer [#4304](https://github.com/cityofaustin/techstack/issues/4304)


## v2.8.3
|||
|-|-|
| **Date** | 04/08/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/655 |
| **Latest Commit Hash** | 05099cee63e99f52cd38c51e7635a2d3a7b0ea3b |
| **Stable?**  | y |

Added:
- Hotfix to fix user resolvers [#4256](https://github.com/cityofaustin/techstack/issues/4256)

## v2.8.2
|||
|-|-|
| **Date** | 04/08/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/653 |
| **Latest Commit Hash** | fbf985bf2eeda6156d0e4bd7a65208775608e631 |
| **Stable?**  | y |

Added:
- Add authenticated resolver for page owners [#4256](https://github.com/cityofaustin/techstack/issues/4256)

## v2.8.1
|||
|-|-|
| **Date** | 03/24/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/619 |
| **Latest Commit Hash** | 2e26d557295ba3d0d3533e276a6e654fa74c3d1d |
| **Stable?**  | y |

Added:
- Ability to localize documents [#4076](https://github.com/cityofaustin/techstack/issues/4076)

## v2.8.0
|||
|-|-|
| **Date** | 03/12/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/605 |
| **Latest Commit Hash** | 490cdad217d73b0d5b1b97cea43bdac7a5816ae8 |
| **Stable?**  | y |

Added:
- Changes to schema to resolve if a top page is live, also only add live pages to site structure [#4042](https://github.com/cityofaustin/techstack/issues/4042)

## v2.7.3
|||
|-|-|
| **Date** | 03/09/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/603 |
| **Latest Commit Hash** | 017ecc8b6e73b0f9b08c7a326c9512b50cc444e7 |
| **Stable?**  | y |

Added:
- Joplin UI: Application Banner & Primary Navigation [#4016](https://github.com/cityofaustin/techstack/issues/4016)

## v2.7.2
|||
|-|-|
| **Date** | 03/06/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/601 |
| **Latest Commit Hash** | 887b06f2f3b67db06b122b2cba122242c23a08fa |
| **Stable?**  | y |

Fixed:
- update the tests to remove outdated model references (PR #600)

## v2.7.2
|||
|-|-|
| **Date** | 03/06/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/599 |
| **Latest Commit Hash** | 78043b3d7de9c02100286c94dd1bd636b97537f9 |
| **Stable?**  | n |

Fixed:
- Migration Test script [#4083](https://github.com/cityofaustin/techstack/issues/4083)
- Add Special hours to translations [#4063](https://github.com/cityofaustin/techstack/issues/4063)

Added:
- Location to style guide [#3995](https://github.com/cityofaustin/techstack/issues/3995)
- Tests with factories [#3987](https://github.com/cityofaustin/techstack/issues/3987)

## v2.7.1
|||
|-|-|
| **Date** | 03/02/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/593 |
| **Latest Commit Hash** | b1bb5cf747dedc64ee00131c2854e211c121b4a5 |
| **Stable?**  | y |

Fixed:
- Department publish preflight fixed for official documents page [#4075](https://github.com/cityofaustin/techstack/issues/4075)

Added:
- [#3818](https://github.com/cityofaustin/techstack/issues/3818)
- [#3942](https://github.com/cityofaustin/techstack/issues/3942)
- [#3989](https://github.com/cityofaustin/techstack/issues/3989)

## v2.7.0
|||
|-|-|
| **Date** | 02/28/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/590 |
| **Latest Commit Hash** | 4587d93d520967fac1bb60a702a8ff269733c076 |
| **Stable?**  | y |

Added:
- Departments (as part of permissions) [#3813](https://github.com/cityofaustin/techstack/issues/3813)

Changed:
- The way we associate pages with departments [PR #557](https://github.com/cityofaustin/joplin/pull/557)

## v2.6.1
|||
|-|-|
| **Date** | 02/27/2020   |
| **PR link**  | https://github.com/cityofaustin/joplin/pull/588 |
| **Latest Commit Hash** | b87f1a7c0f50c34dee79421f0962c803bbd46cb7 |
| **Stable?**  | y |

Changed:
- Default ordering of pages on search/list view is now by most recently edited [#3974](https://github.com/cityofaustin/techstack/issues/3974)
- Limit events to one location [#3858](https://github.com/cityofaustin/techstack/issues/3858)
- Performance improvements [PR 585](https://github.com/cityofaustin/joplin/pull/585), [PR 529](https://github.com/cityofaustin/joplin/pull/529)

Fixed:
- Labels on snippets [#3977](https://github.com/cityofaustin/techstack/issues/3977)

## v2.6
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
