---
name: Add new content type
about: Checklist of technical things that need to happen for a new content type to exist on alpha

---

## Janis
- [ ] new pages/views?
- [ ] new components for representing data inside those pages?
    - [ ] any existing components that would be appropriate to re-use or refactor to re-use? (maybe document a descion as a        code comment either way)
- [ ] add stuff for previews code
    - [ ] does the preview page have all the same stuff on it as a 'real' page (can we test for this in the future?)
- [ ] what sort of contexual nav stuff is needed?
- [ ] create a new query, add to static config
- [ ] add stuff to cleanData to modify the data as its sent as needed (why do we actually do this again? <3 ) 
- [ ] make sure localization works (there are sometimes lots of places where you have to do little things to make this work        atm) 

## Joplin
- [ ] New page model
    - [ ] decide where the page model lives in relation to other models (new default is as its own django app)
    - [ ] model fields of the page to match technical design
    - [ ] model associated relations for the page model
    - [ ] previews stuff? 
    - [ ] any custom css/js for ui for this model?
    - [ ] any code patterns or other models it can borrow from?
    - [ ] custom save/publish requirements
    - [ ] any model validation needed?
    - [ ] what about form validation?
    - [ ] make sure migrations are created, ideally squash or delete and remake your migrations before PR
- [ ] add to create content modal
- [ ] register in translations.py
- [ ] verify/document IA, make sure janis_url on JanisPage will accomodate it (same thing needs to happen in siteStructure atm)
- [ ] set up model in API schema
    - [ ] use either DjangoObjectType or make custom resolvers _as needed_ (if a custom resolver is written, we should probably           add a test so we know if it needs to change, esp if the model changes)
    - [ ] add to siteStructure
    - [ ] verify that data sent is what janis needs/wants, that html is expanded, that formatting or parsing load on janis will           be minimal
    - [ ] set up schema objects for all relations to the content type as well
    - [ ] expose a new query endpoint (atm best advice is to follow existing patterns until we refactor the schema)


## DevOps? (publisher, etc?)

## Misc
