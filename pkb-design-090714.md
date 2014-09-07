---
layout: page
title: Design Guidelines for Personal Knowledgebase
permalink: /pkb-design-090714/
---


See: 
- [Designing a Personal Knowledgebase](http://www.acuriousmix.com/2014/09/03/designing-a-personal-knowledgebase/)
- [Personal Knowledgebase Design Guidelines](http://wiki.learnstream.org/wiki/guide:personal_knowledge_base)

## Defining the Problem

- I do a lot of learning, but I don't have a good way to capture what I learn. I feel that my efforts are wasted.
- Lots of different tools that address parts of my workflow (see Prior Tools), but they're disjointed. And they don't talk to each other.
- Can't share what I learn with other people.

## Guiding Principles

- **Minimize friction at every step**: Prefer one-click solutions. Enable ubiquitous access and editing to the PKB on one's computer. Utilize key board shortcuts often.
- **Automate as much as possible**: Take out as much work as possible for organization. Priortize idiosyncratic and highly personal organization, but leave the mechanical parts to the computer.
- **Minimize maintenance**: if the PKB takes too much work to maintain, it will fall into disuse.
- **Be flexible**: Workflows change with time. As much as possible, the PKB should be flexible enough to change with ones workflow over time.
- **Openness**: Let others see our work and interact with it. But, allow for selective control of openness. Authors should be able to decide whether some content is public and whether some is private.

## Prior Tools
- Standard Wiki: Page structure with extensive hyperlinking.
- Omnioutliner: Advanced outliner. Has moveability function. 
- Devonthink: Easy and ubiquitous capture. Internal hyperlinking. Automates some part of organization. Has AI to suggest new features.
- Workflowy: Web based moveable outliner. 
- Smallest Federated Wiki: Allows for movement of information nuggets within the broswer. Has version control. Can curate from other people's Wikis. 


## Inputs

### Resources

#### What goes into the PKB?

- Websites
- Other web content
    - Social media feeds (Twitter, Facebook)
    - RSS feeds
    - Live web data (embded)
    - Emails
- Text files
- Extracted text from PDF documents
- Extracted notes and highlights from Kindle
- Videos (either the files themselves)
- Pictures (images) 

#### Where do the the resources live?

As much as possible, resources should reside within the PKB. So PDFs, text files, videos, and other files should be housed in the PKB. Content that resides outside of the PKB, such as websites, social media feeds, etc. will be linked to. Alternatively, this content can be captured (web archive, PDF clip, etc.) to create a permanent record in the PKB. 


## Structure of the PKB

**Entities**

- **Pages**: Like Wiki topic pages. A single, continuous presentation of information. Comprised of info-blocks. 
- **Info-blocks**: The most granular units of information in the PKB. At the heart, the PKB is a big compilation of many info-blocks. An info-block could be a single propositional statement or a series of related statments (paragraph). The size is up to the user. Analogous to a bullet in outliners like [Workflowy](www.workflowy.com) or [OmniOutliner](www.omnigroup.com/omnioutliner)
- **Assets**: PDF, image, video, audio, web clip, other file type

**Relationships**

**Links**
All entities in the PKBs are related via links. Every asset has a URL. Every info-block has a URL and every page has a URL. Pages can contain links and be linked themselves to other entities. Info-blocks can contain links internally as well be linked to other info-blocks or pages or assets. 

## Functions/Features

### Input

- Files: Move (drag and drop/select) files to move into the PKB
- Clip web pages (either scrape the content, or just link to page)
- Markup PDFs and export highlight/annotations (either in Skim or in browser)
- Text input

### Organization

- **Metadata annotation**: Add (1) tags and (2) free annotation and (3) categories to all entities: pages, info-blocks, assets. Metadata annotation can be added either at the time of selection (e.g. at the moment a highlight is made in a PDF) or after extraction (within a temporary holding container for new entities that have entered the PKB)
- **Moveable blocks**: All info-blocks can be moved within the PKB by: (1) drag and drop, (2) specific assignment (i.e. send to...). Pages can be moved as well within their own hierarchical structures (parent page, child page, sibling page, etc.)
- **Grouping**: Enable grouping of entities in folders/directories
- **Automated sorting**: Allocate resources and info-blocks to specific pages or folders based on pre-determined criteria. For example, if a new web clip comes into the PKB entitled "Every Skill a Coder Needs in a Tech Startup", this clip would be relevant to the pages in our PKB called _Startups_, _Programming_ and _Technology_. The smart automation would send/link this clip to all of those pages. 

### Usability

- **Search content**: standard search abilities
- **Browse**: browse content (e.g. by tag, by category, etc). Also, ways to visualize relationships? Network graphs of linkages between entities?
- **Accessibility**: PKB viewed in a browser window. Can be edited and viewed quickly via keyboard calls (Alfred?).

### Tracking
- Keep a versioning history (a la Github)
- Learning tracking (all of this is *optional*)
    - Keep time and entry for learning
        - If I'm reading an article in browser, start a time. Take the name and url of the site. Record it automatically.
        - Quick entry for learning done offline (like Toggl)
- Learning Goal Tracking (optional): Set learning goals. Associate activity with goals. Example, if my goal is to "Learn Python" and I spend 20 minutes reading about Python, that should be tracked as activity toward my goal. 

### Outputs and Output Features

- Blog integration: Send to my blog for comment.
- Public pages: I want people to be able to see my Wiki pages
- Cloning: like Smallest Federated Wiki or Github. People can re-use my info-blocks, or even whole pages.
- Publishing. Web server syncing (Dokuwiki, Evernote). Static page generation (Jekyll, Hakyll/pandoc). Ebook publication (Pollen).
- Integration with offline publishing apps: send to Scrivnever, OmniOutliner, SublimeText, etc. 
- Integration with Spaced Repetition programs ([Anki], [Memorang](www.memorangapp.com)): Send selected info-blocks directly to SR software so as to reinforce memory of very high yield bits.