# Janis Changelog

## v3.0.4
|||
|-|-|
| **Date** | 05/06/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/765 |
| **Latest Commit Hash** | 693b0f8b4e28525e189c4c422c229d8a59423119 |
| **Stable?**  | y |

Fixed:
- locations showing extraneous commas 
- site structure being queried twice

## v3.0.3
|||
|-|-|
| **Date** | 05/01/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/761 |
| **Latest Commit Hash** | acfb87bcf07a781651585d1e2d78b8f80ae226f5 |
| **Stable?**  | y |

Fixed:
- v3.0.1, v3.0.2, v3.0.3 contain multiple hotfixes to allow production deployments to work for Publisher2.

## v3.0.0
|||
|-|-|
| **Date** | 05/01/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/756 |
| **Latest Commit Hash** | 687e3f601c57d938e2a8b824e5c075998c8969ea |
| **Stable?**  | y/n |

Added:
- Ability to build from Joplin v3 https://github.com/cityofaustin/techstack/issues/4174
- Uses Publisher2 for staging and production.

## v2.9.0
|||
|-|-|
| **Date** | 04/22/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/743 |
| **Latest Commit Hash** | bf549b155241e94deb37128a3b52f85a17a31328 |
| **Stable?**  | y |

Removed:
- Logic for rendering map blocks [#4304](https://github.com/cityofaustin/techstack/issues/4304)


## v2.8.4
|||
|-|-|
| **Date** | 03/20/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/730 |
| **Latest Commit Hash** | 992901d69f3acdc4bfb66dfbc7ff01f46082ead2 |
| **Stable?**  | y |

Added:
- Localization/styling for form can't load fallback message [#3967](https://github.com/cityofaustin/techstack/issues/3967)

## v2.8.3
|||
|-|-|
| **Date** | 03/20/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/729 |
| **Latest Commit Hash** | caed2daff0b722758409842c9ed7b705f9edb18a |
| **Stable?**  | y |

Fixed:
- Broken builds with top level pages [#3899](https://github.com/cityofaustin/techstack/issues/3899)


## v2.8.2
|||
|-|-|
| **Date** | 03/18/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/724 |
| **Latest Commit Hash** | 94a31f6b8b72e30f23ca519e99c79c1c3de4607f |
| **Stable?**  | y |

Added:
- COVID-19 hours alert on location pages [#4158](https://github.com/cityofaustin/techstack/issues/4158)


# Janis Changelog

## v2.8.1
|||
|-|-|
| **Date** | 03/16/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/726 |
| **Latest Commit Hash** | a4dfa82e06091398fe859083239e9a926af0f524 |
| **Stable?**  | y |

Added:
- Covid19 Alert Banner [#4154](https://github.com/cityofaustin/techstack/issues/4154)


## v2.8.0
|||
|-|-|
| **Date** | 03/12/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/723 |
| **Latest Commit Hash** | d631ffb205c01316f9337a03bb13666d1f9e5bc4 |
| **Stable?**  | y |

Added:
- language tag [#3641](https://github.com/cityofaustin/techstack/issues/3641)
- get directions links [#4059](https://github.com/cityofaustin/techstack/issues/4059)
- unpublished page still appears in production [#4042](https://github.com/cityofaustin/techstack/issues/4042)

## v2.7.4
|||
|-|-|
| **Date** | 03/11/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/722 |
| **Latest Commit Hash** | 5967fdfc57d5acd7c25bd10ea5c6113a9debc27e |
| **Stable?**  | y |

Fixed:
- sticky scroll position [#4053](https://github.com/cityofaustin/techstack/issues/4053)


## v2.7.3
|||
|-|-|
| **Date** | 03/9/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/718 |
| **Latest Commit Hash** | 0c6cda3b295aa7fcaa29c2760e8bea240d80ced2 |
| **Stable?**  | y |

Fixed:
- Remove related departments ref [#4096](https://github.com/cityofaustin/techstack/issues/4096)

## v2.7.2
|||
|-|-|
| **Date** | 03/4/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/715 |
| **Latest Commit Hash** | 4b211d9458e391dd3a4515b4b32d640f29bbd68c |
| **Stable?**  | y |
Added:
- Events to the homepage [#3818](https://github.com/cityofaustin/techstack/issues/3818)
Fixed:
- Bug previewing departments [#4090](https://github.com/cityofaustin/techstack/issues/4090)


## v2.7.1
|||
|-|-|
| **Date** | 02/28/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/712 |
| **Latest Commit Hash** | f7b97d625366056016b25dcd9e1fb5f9ff22ef49 |
| **Stable?**  | y |

Fixed:
- Static config fix for event page related departments [PR #711](https://github.com/cityofaustin/janis/pull/711)
- Spacing between content and user feedback on location pages [PR #711](https://github.com/cityofaustin/janis/pull/711)

## v2.7
|||
|-|-|
| **Date** | 02/28/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/710 |
| **Latest Commit Hash** | 71e28f66884953eabe754466df7ddf154ee1b64e |
| **Stable?**  | n |

Changed:
- Support updated joplin department API [#3983](https://github.com/cityofaustin/techstack/issues/3983)


## v2.6.1
|||
|-|-|
| **Date** | 02/27/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/709 |
| **Latest Commit Hash** | 14d8af80bd255b2b2e5fb4f5b488dd766262125e |
| **Stable?**  | y |

Added:
- Localization for location link [#3896](https://github.com/cityofaustin/techstack/issues/3896)

Changed:
- Text in tables is now vertically aligned to the top of the cell [#3757](https://github.com/cityofaustin/techstack/issues/3757)
- Feedback component styles [#3959](https://github.com/cityofaustin/techstack/issues/3959)

Fixed:
- "This page is a part of" link behavior on pages in guides [#3993](https://github.com/cityofaustin/techstack/issues/3993)
- The entire rich text button element is a clickable link now [#3921](https://github.com/cityofaustin/techstack/issues/3921)
- Layout/spacing on steps with locations [#3975](https://github.com/cityofaustin/techstack/issues/3975)


## v2.6
|||
|-|-|
| **Date** | 02/25/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/704 |
| **Latest Commit Hash** | 0b60d24b4b018f9236c99cbbda9e89e2299909a3 |
| **Stable?**  | y |

*note: 2.5 was skipped because of multiple api changes on the Joplin side*

Added:
- Events list view [#3817](https://github.com/cityofaustin/techstack/issues/3817)

Fixed:
- Navigation no longer uses hardcoded themes [#3947](https://github.com/cityofaustin/techstack/issues/3947)
- Padding/margins for steps with options [#3826](https://github.com/cityofaustin/techstack/issues/3826)

## v2.4.2
|||
|-|-|
| **Date** | 02/13/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/693 |
| **Latest Commit Hash** | e9aa0b5a8efce97be40f900fed3b13e80ecd85e9 |
| **Stable?**  | y |

Changed:
- Location page service hours padding/margins matches spec [#3960](https://github.com/cityofaustin/techstack/issues/3960)

## v2.4.1
|||
|-|-|
| **Date** | 02/13/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/691 |
| **Latest Commit Hash** | b5efad419eabd71c739102dbdc2c38e3ae3354d7 |
| **Stable?**  | y |

Added:
- Design and width brackdown for locations components [#3840](https://github.com/cityofaustin/techstack/issues/3840)

Changed:
- Event detail padding/margins match mocks [#3917](https://github.com/cityofaustin/techstack/issues/3917)

## v2.4.0
|||
|-|-|
| **Date** | 02/12/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/687 |
| **Latest Commit Hash** | 79be3329a8b8432f3cff5522229f70643afc4821 |
| **Stable?**  | y |

Changed:
- Made changes to the way steps data is parsed in order to fix a regression error [#3852](https://github.com/cityofaustin/techstack/issues/3852)

Added:
- New logic for handiling hours for a service related to a location [#3740](https://github.com/cityofaustin/techstack/issues/3740)

## v2.3.1
|||
|-|-|
| **Date** | 02/05/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/686 |
| **Latest Commit Hash** | 954c31967a37888db21dd3d8b6510b1121da5ec9 |
| **Stable?**  | y |

Added:
- Formstack forms don’t render [#3792](https://github.com/cityofaustin/janis/pull/680)

## v2.3.0
|||
|-|-|
| **Date** | 01/31/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/683 |
| **Latest Commit Hash** | df5e127813852503c47691afd7ca6ce965b88a03  |
| **Stable?**  | y |

Added:
- Event details page [#3815](https://github.com/cityofaustin/techstack/issues/3815)

## v2.2.4
|||
|-|-|
| **Date** | 01/30/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/681|
| **Latest Commit Hash** | 908d6330a123809b0a646704804dc74d1c174bf8 |
| **Stable?**  | y |

Fixed:
- Feedback form no longer shows on each document on a document list page: [#3825](https://github.com/cityofaustin/techstack/issues/3825)
- The save/resume confirmation page loads on embedded formstack forms now. [#3773](https://github.com/cityofaustin/techstack/issues/3773)

## v2.2.3
|||
|-|-|
| **Date** | 01/22/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/676 |
| **Latest Commit Hash** | 73dfdc249dc8211709d935161e9a34137ea30fed |
| **Stable?**  | y |

Added:
- Guide pages are more screen reader friendly [#3291](https://github.com/cityofaustin/janis/pull/640)
- Seperate render controls for phone and email on location contacts [#3742](https://github.com/cityofaustin/janis/pull/671)
- Displays hours exceptions for related services [#3772](https://github.com/cityofaustin/janis/pull/674)

Changed:
- Removed feedback form from Footer; it now must be added on a page by page basis [#3631](https://github.com/cityofaustin/janis/pull/674)
- Pagination truncates in a user friendly way on mobile [#3585](https://github.com/cityofaustin/janis/pull/666)

Fixed:
- Blank divs on location page related services without phone number info
- Topic cards on topic collection for unpublished topics

## v2.2.2
|||
|-|-|
| **Date** | 01/09/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/669 |
| **Latest Commit Hash** | 31bb7832e61541f6ee000c23db835f3ca0946fcc |
| **Stable?**  | y |

Fixes:
- Broken location page related service urls
- Blank divs on location page related services without phone number info
- Topic cards on topic collection for unpublished topics

## v2.2.1
|||
|-|-|
| **Date** | 01/09/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/665 |
| **Latest Commit Hash** | 5d9c0a65f0d0067c461d4a4fca836d859abc36ca |
| **Stable?**  | y |

Fixes:
- Broken builds when missing phone data on location page related service page contact
- Days showing in service page contact card when they shouldn't

## v2.2.0
|||
|-|-|
| **Date** | 01/09/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/663 |
| **Latest Commit Hash** | 6185b27a3487e80a7d4dd9db6d0a465454e37a87  |
| **Stable?**  | y |

Added:
- Update service page steps to support locations
- Update contact card to support location page data

## v2.1.1
|||
|-|-|
| **Date** | 01/08/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/660 |
| **Latest Commit Hash** | d02a6956808fecc8dbcef2abbf0f69ee074d0558  |
| **Stable?**  | y |

Fixed:
- pages in draft status no longer show up as links on topic pages
- adjusted header padding

## v2.1.0
|||
|-|-|
| **Date** | 01/03/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/656 |
| **Latest Commit Hash** | 23bd37a25ca5532ade9ca066c97ea100733e40f7  |
| **Stable?**  | y |

Added:
- Center pagination component [3586](https://app.zenhub.com/workspaces/techstack-5a78b88e1ce69f3510b678ef/issues/cityofaustin/techstack/3586)

## v minus 1
|||
|-|-|
| **Date** | 10/29/2019   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/584 |
| **Latest Commit Hash** | e4f4869ce0c3fa876959f1de97091e269f0367a8  |
| **Oldest Compatible Joplin** | v minus 1 |
| **Stable?**  | y |

Added:
- New SiteStructure graphql queries

## v minus 2
|||
|-|-|
| **Date** | 11/07/2019   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/584 |
| **Latest Commit Hash** | fe3469172de07efed84b344e6ea5cf24e9587aa5  |
| **Oldest Compatible Joplin** | v minus 2 |
| **Stable?**  | y |

Added:
- New SiteStructure graphql queries

## v2.0.0
|||
|-|-|
| **Date** | 05/28/2019   |

Added:
- Merge OPO microsite version to alpha.austin.gov

Changed:
- Mega menu which includes all themes
- New Navigation: Topic Collection Page > Topic Page > Services
- Globally enhanced visual design
