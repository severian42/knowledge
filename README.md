# Description

Knowledge is a tool for saving, searching, accessing, and exploring all of your favorite websites, documents and files.

![KnowledgeGraph](https://user-images.githubusercontent.com/19367848/206884085-f73affb8-b94e-4039-beb3-b47f76762d8b.gif)

# Download

- [Latest Stable Release](https://github.com/KnowledgeCanvas/knowledge-canvas/releases/latest)
- [All Versions](https://github.com/KnowledgeCanvas/knowledge-canvas/releases)

# Documentation

- [Basics](https://github.com/KnowledgeCanvas/knowledge/wiki/Basics)
- [Shortcut Keys](https://github.com/KnowledgeCanvas/knowledge/wiki/Shortcut-Keys)
- [Development and Build Instructions](https://github.com/KnowledgeCanvas/knowledge-canvas/wiki/Development)
- [Debugging](https://github.com/KnowledgeCanvas/knowledge-canvas/wiki/Debugging)

# Feature Roadmap

The list of features supported by Knowledge is large and growing everyday. Here are a few highlights, both existing and yet to come:

- Elegant Design
  - [x] Over 20 user-selectable themes, including dark and light mode
  - [x] Website icons and thumbnails automatically extracted
  - [x] File icons and thumbnails generated by local OS, so everything looks the way you expect it to
  - [x] Subtle animations and transitions for a silky-smooth experience
  - [x] Built on the latest [PrimeNG](https://www.primefaces.org/primeng/) component library

- Importing Website URLs
  - [x] Copy/Paste
  - [x] Drag/Drop
  - [x] Built-in browser
  - [x] [Chrome extension](https://github.com/KnowledgeCanvas/extensions)
  - [ ] Firefox extension
  - [ ] Extract specific content and HTML blocks
  - [ ] Offline copies
  - [ ] Save as PDF
  
- Importing Files
  - [x] Upload dialog
  - [x] Drag/Drop
  - [x] Automatically scan local directories (in customizable intervals)
  - [ ] Optional [full-text extraction using Tika via Docker](https://github.com/KnowledgeCanvas/docker)
  
- Learning and Organizing
  - [x] Group everything into `Projects` and `Subprojects` (e.g. organize by course, subject, feature, sprint, etc.)
  - [x] Automatically extract icons, thumbnails, and other metadata
  - [x] Add tags and topics
  - [x] Automatically move files to a managed directory
  - [ ] See related imports for quick categorization ([clustering](https://github.com/KnowledgeCanvas/models/blob/main/notebooks/doc2vec.ipynb))
  - [ ] Text summarization using models like DistilBERT and GPT3
  - [ ] Document understanding and question answering [using DoNUT](https://github.com/KnowledgeCanvas/models/blob/main/notebooks/donut.ipynb)
  - [ ] Pre-requisite detection between sets of imports
  - [ ] Connect imports to each other using back-links and other references (e.g. by author, topic, concept, etc.)

- Multiple Views
  - [x] Inbox view - this is where all imports live before being assigned to specific `Projects`
  - [x] Graph view - best for understanding the structure of `Projects` and how imports relate to each other, plus it looks awesome!
  - [x] Table view - best for doing things in bulk (e.g. open 14 different websites at the press of a button)
  - [x] Grid/Card view - best for exploring collections of docs and websites
  - [x] Calendar view - best for retracing your steps and improved learning with "spaced repition"
  - [ ] Browser view - best for understanding how you navigate the web
  - [x] [Shortcut keys](https://github.com/KnowledgeCanvas/knowledge/wiki/Shortcut-Keys) for quickly getting around the app and changing views
  
- Search
  - [x] All imported documents, files, and websites are searchable
  - [x] Choose between Google, Bing, or DuckDuckGo for searching the web with built-in browser
  - [x] Save search results to the Inbox
  - [x] One-click topic search
  - [ ] "Native" search results extracted from your favorite search engine
  - [ ] [Optional Elasticsearch via Docker](https://github.com/KnowledgeCanvas/docker)
  
- Access
  - [x] Works on macOS, Windows, and Linux using Electron 21
  - [x] Open any import in its default application (e.g. websites open in Chrome, PDFs open in Adobe, etc.)
  - [x] Built-in web browser with basic navigation
  - [x] Embedded YouTube player, PDF reader, video player, and image viewer
  - [x] Copy all related data to clipboard
  - [x] Export all related data to CSV or JSON
  - [x] Each import gets its own timeline with creation, access, modification, and due dates
  - [ ] Synchronize across multiple devices
  - [ ] Self-hosted Web UI
  - [ ] Cloud storage plugins
 
- Graph
  - [x] View project structure and relationships
  - [x] Multiple preset layouts
  - [x] Physics-based simulation and layout
  - [x] Search the entire graph and animate results
  - [x] Performance warnings for very large graphs
  - [x] Customize single and double-click actions
  - [ ] Custom learning paths with pre-requisites
  
- Security
  - [x] Everything is stored locally
  - [x] No servers
  - [x] No sign-ups
  - [x] No data collection

# Screenshots

**Inbox**

<img width="1363" alt="image" src="https://user-images.githubusercontent.com/19367848/206948591-bbd79af0-4de6-4b64-b405-38f07cb3ca83.png">

**Projects**

<img width="1363" alt="image" src="https://user-images.githubusercontent.com/19367848/206946695-f806596f-ceb2-4c57-b73e-dadd0d6ca778.png">

**Graph**

<img width="1363" alt="image" src="https://user-images.githubusercontent.com/19367848/206946839-174623c7-54e6-48ef-bc06-6d0d981f124c.png">

**Table**

<img width="1363" alt="image" src="https://user-images.githubusercontent.com/19367848/206946889-885fbd50-cfe7-413b-936e-83a768b5965c.png">

**Grid**

<img width="1363" alt="image" src="https://user-images.githubusercontent.com/19367848/206947070-ad68c626-586e-4e2c-8fbc-1868801e6f51.png">

**Calendar**

<img width="1363" alt="image" src="https://user-images.githubusercontent.com/19367848/206947134-e96e2e92-f9db-4934-bbfb-d09e67ccdfb1.png">

**Details**

<img width="1363" alt="image" src="https://user-images.githubusercontent.com/19367848/206948764-07e019a4-4168-47ba-a600-3dc7d35480e5.png">

**Settings**

<img width="1363" alt="image" src="https://user-images.githubusercontent.com/19367848/206947307-b37da407-bf72-4674-9458-f2e04a7ad5c6.png">

# Disclaimer

*Knowledge* ("this software") is not a consumer product and provides no warranty of any kind. By using this software, you agree that you are doing so at your own risk. The creators of this software are not responsible for loss of data or other damages that may result in its operation. You are welcome to open an issue or a pull request. Contributors and testers are welcome and appreciated.
