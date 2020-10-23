# Janis Changelog

## v3.12.0
|||
|-|-|
| **Date** | 10/23/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/889 |
| **Latest Commit Hash** | ea39580ac7d8ebb4029f46d3dec91f090a77c570 |
| **Stable?**  | y |

Added:
- Date filtering on Official Document Collections [#4849](https://github.com/cityofaustin/techstack/issues/4849)
- Live API keyword search for SearchPage and Official Document Collections [#5052](https://github.com/cityofaustin/techstack/issues/5052)
- A single scripts/start.sh to handle all react-static builds for all environments

## v3.11.0
|||
|-|-|
| **Date** | 10/21/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/888 |
| **Latest Commit Hash** | 0862f70055dee6d8ebed6d77c7c27400e212a68a |
| **Stable?**  | y |

Added:
- Send user name and password to authenticate graphql requests [#4763](https://github.com/cityofaustin/techstack/issues/4763)

## v3.10.2
|||
|-|-|
| **Date** | 10/21/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/885 |
| **Latest Commit Hash** | 0862f70055dee6d8ebed6d77c7c27400e212a68a |
| **Stable?**  | y |

Added:
- Official doc collection: display total number of documents: [#4847](https://github.com/cityofaustin/techstack/issues/4847)
- Change microcopy on topic pages: [#4671](https://github.com/cityofaustin/techstack/issues/4671)

## v3.10.1
|||
|-|-|
| **Date** | 10/15/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/881 |
| **Latest Commit Hash** | 01afca424bdf74efd42cd360dec6561650ec6b1f |
| **Stable?**  | y |

Added:
- Dates on Official Documents [#4772](https://github.com/cityofaustin/techstack/issues/4772)
- Body on Official Documents [#4787](https://github.com/cityofaustin/techstack/issues/4787)

## v3.10.0
|||
|-|-|
| **Date** | 10/13/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/879 |
| **Latest Commit Hash** | 01afca424bdf74efd42cd360dec6561650ec6b1f |
| **Stable?**  | y |

Added:
- Query for content manageable homepage

Fixed: 
- Issue with site build process ending before promises have resolved
- Error message in build process when loading style cannot be found

## v3.9.3
|||
|-|-|
| **Date** | 10/02/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/868 |
| **Latest Commit Hash** | 01afca424bdf74efd42cd360dec6561650ec6b1f |
| **Stable?**  | y |

Fixed:
- Home Page "View all Events" button: [#5023](https://github.com/cityofaustin/techstack/issues/5023)

## v3.9.2
|||
|-|-|
| **Date** | 09/30/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/863 |
| **Latest Commit Hash** | 39ba10840be97279d58d52ef993a887272095048 |
| **Stable?**  | y |

Changed:
- Global nav: remaining styling: [#4830](https://github.com/cityofaustin/techstack/issues/4830)

## v3.9.1
|||
|-|-|
| **Date** | 09/22/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/858 |
| **Latest Commit Hash** | db96af7b77c8ee12bdb7d4ea5f5ce79159ba6221 |
| **Stable?**  | y |

Changed:
- New Banner Image: [#4893](https://github.com/cityofaustin/techstack/issues/4893)

## v3.9.0
|||
|-|-|
| **Date** | 09/14/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/856 |
| **Latest Commit Hash** | 642522cf60e8e979d8aab836ba61185317bac766 |
| **Stable?**  | y |

Changed:
- searchIndexBuilder refactor. The searchIndex is now in a format that can be sent to Elasticsearch. [#4776](https://github.com/cityofaustin/techstack/issues/4776)

## v3.8.0
|||
|-|-|
| **Date** | 08/31/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/849 |
| **Latest Commit Hash** | 820b868078f5993a74ed264e354b78e34b988714 |
| **Stable?**  | y |

Added:
- Official Document Page summary fields are rich text fields, this update changes the component to handle html from joplin [#4872](https://github.com/cityofaustin/techstack/issues/4872)


## v3.7.1
|||
|-|-|
| **Date** | 08/28/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/848 |
| **Latest Commit Hash** | 14987338a5d0ab099cc73ae164a5fcdeb785fc9d |
| **Stable?**  | y |

Added:
- Clean data - Official Document Pages in search results [#4618](https://github.com/cityofaustin/techstack/issues/4681)
- Style - Official Document Pages in search results [#4861](https://github.com/cityofaustin/techstack/issues/4861)

Fixed: 
- Search bar input doesn't clear after user press the back button in the browser [#4704](https://github.com/cityofaustin/techstack/issues/4704)

## v3.7.0
|||
|-|-|
| **Date** | 08/18/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/841 |
| **Latest Commit Hash** | 93e14463a6ee89fb1adf92498462bfd4a8e99d1c |
| **Stable?**  | y |

Added:
- News list items on department pages [#4404](https://github.com/cityofaustin/techstack/issues/4404)
- Nav2 Dropdown [#4648](https://github.com/cityofaustin/techstack/issues/4648)
- WIP banner [#3992](https://github.com/cityofaustin/techstack/issues/3992)

Fixed: 

- Missing airport and 311 links [#4737](https://github.com/cityofaustin/techstack/issues/4737)

## v3.6.1
|||
|-|-|
| **Date** | 08/14/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/839 |
| **Latest Commit Hash** | d39e0bec89fe019dd0250e0b1c702b8ed0eac581 |
| **Stable?**  | y |

Fixed:
- Bug where searching for only a number was breaking [#4698](https://github.com/cityofaustin/techstack/issues/4698)

## v3.6.0
|||
|-|-|
| **Date** | 08/11/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/836 |
| **Latest Commit Hash** | 6dd56a8736568aa41650ca546aeb92f4bca6831f |
| **Stable?**  | y |

Added:
- Links can be addded to OfficialDocumentCollection description [#4747](https://github.com/cityofaustin/techstack/issues/4747)
- Links can be addded to Location hours [#4758](https://github.com/cityofaustin/techstack/issues/4758)

## v3.5.1
|||
|-|-|
| **Date** | 07/31/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/827 |
| **Latest Commit Hash** | 22834016b022db420fc118a8e4e1bf7d5c02dda5 |
| **Stable?**  | y |

Added: 
- Update Janis "😃 Getting Started" Section [#4634](https://github.com/cityofaustin/techstack/issues/4634)

Fixes: 
- Use smaller seal image on Janis [#4660](https://github.com/cityofaustin/techstack/issues/4660)

## v3.5.0
|||
|-|-|
| **Date** | 07/28/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/830 |
| **Latest Commit Hash** | 8d96572c7caf19617b4de3e3133ebe02a2b75ec6 |
| **Stable?**  | y |


Added:
- Official Document Pages are their own pages and can be previewed [#4591](https://github.com/cityofaustin/techstack/issues/4591)

## v3.4.3
|||
|-|-|
| **Date** | 07/24/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/828 |
| **Latest Commit Hash** | 8d96572c7caf19617b4de3e3133ebe02a2b75ec6 |
| **Stable?**  | y |


Fixed:
- Social Media Links [#4689](https://github.com/cityofaustin/techstack/issues/4689)

## v3.4.2
|||
|-|-|
| **Date** | 07/23/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/827 |
| **Latest Commit Hash** | 3a74c544feec4a5a7220816369fc3f76ba1a1a7b |
| **Stable?**  | y |

Added: 
- 🤝 4392 nav2: Header and Themes Buttons dev criteria [#4392](https://github.com/cityofaustin/techstack/issues/4392)
- Search enhancement: enter (keypress) to submit search query [#4510](https://github.com/cityofaustin/techstack/issues/4510)
- 🎨 Contextual navigation background color [#4393](https://github.com/cityofaustin/techstack/issues/4393)

Fixed:
- Global alert: responsive CSS tweak [#4156](https://github.com/cityofaustin/techstack/issues/4510)

## v3.4.1
|||
|-|-|
| **Date** | 07/21/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/824 |
| **Latest Commit Hash** | 5b73a21d2d5da93333e54a62d94015e3eb291c1d |
| **Stable?**  | y |

Fixed:
- Removed ineffective compression-webpack-plugin [#4611](https://github.com/cityofaustin/techstack/issues/4611)
- Moved bulk pickup message in trashy app [#4327](https://github.com/cityofaustin/techstack/issues/4327)

## v3.4.0
|||
|-|-|
| **Date** | 07/17/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/821 |
| **Latest Commit Hash** | dba31faec370b55eb46baa36cc7df26735a7b5a8 |
| **Stable?**  | y |

Added:
- Previews for new Official Documents Collection [#4621](https://github.com/cityofaustin/techstack/issues/4621)
- remove CMS_DOCS environment variable, document url address information is handled by Joplin
- `config.devtool = false` in node.api.js to fix dev server errors

## v3.3.1
|||
|-|-|
| **Date** | 07/14/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/816 |
| **Latest Commit Hash** | 8de3a3e132a3818e9c6c6fc4c419061636a8042c |
| **Stable?**  | y |

Added:
- gzip compression for Janis builds [#4611](https://github.com/cityofaustin/techstack/issues/4611)


## v3.3.0
|||
|-|-|
| **Date** | 07/13/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/815 |
| **Latest Commit Hash** | a30464d8e1ad6622b1e50772230f317918558494 |
| **Stable?**  | y |

Updated:
- Updated static.config to handle the schema changes in joplin 3.3.0 (https://github.com/cityofaustin/janis/pull/797)


## v3.2.8
|||
|-|-|
| **Date** | 07/08/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/812 |
| **Latest Commit Hash** | 718822cab229e5d138acc361fedc84a863891506 |
| **Stable?**  | y |

Fixed:
- Allow language switching in Previews: [#4596](https://github.com/cityofaustin/techstack/issues/4596)

## v3.2.7
|||
|-|-|
| **Date** | 07/03/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/810 |
| **Latest Commit Hash** | ec5c9f8eb81e3fa9b807386e42d6f17d5a782f4e |
| **Stable?**  | y |

Fixed:
- Location page padding for related service hours with contact: [#4411](https://github.com/cityofaustin/techstack/issues/4411)

## v3.2.6
|||
|-|-|
| **Date** | 06/26/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/805 |
| **Latest Commit Hash** | 419eda2590963b9f356a1368b6edf77ade5c7655 |
| **Stable?**  | y |

Added:
- Filling out and fixing Spanish microcopy: [#4459](https://github.com/cityofaustin/techstack/issues/4459)


## v3.2.5
|||
|-|-|
| **Date** | 06/11/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/788 |
| **Latest Commit Hash** | caf7b08fb5d8aaa805e8e48212062688ff9cf3bb |
| **Stable?**  | y |

Added:
- Spanish translation for "0" search results page: [#4423](https://github.com/cityofaustin/techstack/issues/4423)

## v3.2.4
|||
|-|-|
| **Date** | 06/03/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/788 |
| **Latest Commit Hash** | 5fe5dc6ac6f6d225d3374b3b18553064a11a1f92 |
| **Stable?**  | y |

Added:
- Search Page Pagination [#4358](https://github.com/cityofaustin/techstack/issues/4358)
- Search Page Navigation Icon [#4283](https://github.com/cityofaustin/techstack/issues/4283)

## v3.2.3
|||
|-|-|
| **Date** | 06/02/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/787 |
| **Latest Commit Hash** | 9daff223aa08c6e785b4157e890334e9b1e3a1ca |
| **Stable?**  | y |

Fixed:
- Button on Service Page Option [#4450](https://github.com/cityofaustin/techstack/issues/4450)

## v3.2.2
|||
|-|-|
| **Date** | 05/27/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/782 |
| **Latest Commit Hash** | 8f3187b09792ce43b0709907fa4eab0719ed0ae3 |
| **Stable?**  | y |

Added:
- Search Page [#4285](https://github.com/cityofaustin/techstack/issues/4285)
- Spanish Translations [#4286](https://github.com/cityofaustin/techstack/issues/4286)


## v3.2.1
|||
|-|-|
| **Date** | 05/21/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/780 |
| **Latest Commit Hash** | d80f73caec18ddbe7552d4cb785bb97cf51ea174 |
| **Stable?**  | y |

Changed:
- Query fewer pages at once during builds [#4422](https://github.com/cityofaustin/techstack/issues/4422)



## v3.2.0
|||
|-|-|
| **Date** | 05/15/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/777 |
| **Latest Commit Hash** | 2135d4dc70792d0a70d0a2fcb7ddd63e761de0b0 |
| **Stable?**  | y |

Added:
- News pages [#4355](https://github.com/cityofaustin/techstack/issues/4355)


## v3.1.3
|||
|-|-|
| **Date** | 05/15/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/776 |
| **Latest Commit Hash** | 313cddc8c4c655bcd78e5abe72a036e8787a70d9 |
| **Stable?**  | y |

Updated:
- Location page styles [#4241](https://github.com/cityofaustin/techstack/issues/4241), [#4242](https://github.com/cityofaustin/techstack/issues/4242)

## v3.1.2
|||
|-|-|
| **Date** | 05/15/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/775 |
| **Latest Commit Hash** | b7ac2587f14e057d45f479a438ff3b5228c68add |
| **Stable?**  | y |

Updated:
- H1 color https://github.com/cityofaustin/techstack/issues/4162

## v3.1.1
|||
|-|-|
| **Date** | 05/14/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/772 |
| **Latest Commit Hash** | 87cec58af36601bc3dd21a15c5b4084948d4d872 |
| **Stable?**  | y |

Fixed:
- Bug with page instance specific data https://github.com/cityofaustin/janis/pull/770

## v3.1.0
|||
|-|-|
| **Date** | 05/13/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/769 |
| **Latest Commit Hash** | a8055d5ae2e3db8e7aa7a866f3434421ce8758fe |
| **Stable?**  | y |

Added:
- Related events on Service, Information and Location pages: https://github.com/cityofaustin/techstack/issues/4235

## v3.0.5
|||
|-|-|
| **Date** | 05/11/2020   |
| **PR link**  | https://github.com/cityofaustin/janis/pull/767 |
| **Latest Commit Hash** | 65d3d66c15e51ed384483020051def73bf1d71af |
| **Stable?**  | y |

Added:
- Janis Search: site index generation on build: https://github.com/cityofaustin/techstack/issues/4284


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
