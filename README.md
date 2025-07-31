# awesome-sync-engines

Local-first databases, CRDTs, sync engines

### Sync Platforms & Backends-as-a-Service (BaaS)

- **[PartyKit](https://www.partykit.io/)** - An open-source platform for deploying real-time, multiplayer applications. It uses small, stateful servers ("parties") that run at the edge and integrates with existing hosting providers. [GitHub](https://github.com/partykit/partykit)
- **[Convex](https://www.convex.dev/)** - An open-source reactive database with a full-stack TypeScript experience. It guarantees that the UI is always in sync with the database state in real time. [GitHub](https://github.com/get-convex/convex-backend)
- **[InstantDB](https://www.instantdb.com/)** - A modern Firebase alternative providing a real-time database directly to the frontend, with automatic optimistic updates and robust offline support. [GitHub](https://github.com/instantdb/instant)
- **[Liveblocks](https://liveblocks.io/)** - A suite of APIs and pre-built components for adding collaborative experiences like live presence, comments, and multiplayer cursors to products. [GitHub](https://github.com/liveblocks/liveblocks)

### Sync Infrastructure & Libraries

- **[ElectricSQL](https://electric-sql.com/)** - An open-source Postgres sync engine that adds real-time and local-first capabilities to applications built on PostgreSQL by syncing data to client-side environments. [GitHub](https://github.com/electric-sql/electric)
- **[PowerSync](https://www.powersync.com/)** - A sync engine that connects backend databases like Postgres, MySQL, or MongoDB with an in-app SQLite database on the client, enabling offline-first applications. [GitHub](https://github.com/powersync-ja/powersync-js)
- **[Ditto](https://ditto.live/)** - A sync platform with a mobile database featuring peer-to-peer mesh networking, allowing data synchronization directly between devices without a central server.
- **[Replicache](https://replicache.dev/)** - An influential client-side sync framework for building real-time, collaborative web applications with an "optimistic UI" model. It is now open-source and in maintenance mode. [GitHub](https://github.com/rocicorp/replicache)
- **[Logux](https://logux.org/)** - A flexible JavaScript framework for building custom local-first sync engines by synchronizing a log of actions between the client and server. [GitHub](https://github.com/logux/logux)

### Local-First Databases

- **[pglite](https://pglite.dev/)** - An embeddable PostgreSQL database that runs entirely in the browser or other JavaScript environments via WebAssembly. [GitHub](https://github.com/electric-sql/pglite)
- **[Livestore](https://livestore.dev/)** - A next-generation state management framework that functions as a client-centric data layer, using a reactive embedded SQLite database and a Git-inspired sync engine. [GitHub](https://github.com/livestorejs/livestore)
- **[RxDB](https://rxdb.info/)** - A fast, local-first NoSQL database for JavaScript applications, built on the principles of reactive programming where "everything is a stream." [GitHub](https://github.com/pubkey/rxdb)
- **[PouchDB](https://pouchdb.com/)** - An established open-source JavaScript database for offline-first applications, designed to work with and synchronize to Apache CouchDB. [GitHub](https://github.com/pouchdb/pouchdb)
- **[SignalDB](https://signaldb.js.org/)** - A modern, reactive, local-first JavaScript database that uses the "Signals" pattern for state management and reactivity. [GitHub](https://github.com/maxnowack/signaldb)
- **[KuzuDB](https://kuzudb.com/)** - An embedded graph database built for query speed and scalability. Optimized for handling complex analytical workloads on property graphs with extremely fast query performance. [GitHub](https://github.com/kuzudb/kuzu)

### Core Data Structures & Algorithms

- **[Yjs](https://yjs.dev/)** - A high-performance CRDT implementation for building collaborative software. It provides shared data types that automatically distribute and merge changes without conflicts. It's network-agnostic and has a rich ecosystem of extensions. [GitHub](https://github.com/yjs/yjs)
- **[Automerge](https://automerge.org/)** - A library of JSON-like CRDT data structures for local-first collaborative applications. It uses an immutable state model, making it a good fit for functional programming paradigms. [GitHub](https://github.com/automerge/automerge)
- **[Loro](https://loro.dev/)** - A high-performance CRDT library with a rich set of data types, including advanced structures for rich text and hierarchical data. It maintains a full version history, similar to Git. [GitHub](https://github.com/loro-dev/loro)

### Technical Deep Dives: How Sync Engines Work

- **[How Figma's multiplayer technology works](https://www.figma.com/blog/how-figmas-multiplayer-technology-works/)** - An in-depth technical explanation of Figma's operational transform-based sync engine and real-time collaboration architecture.
- **[Scaling the Linear sync engine](https://linear.app/now/scaling-the-linear-sync-engine)** - A detailed breakdown of Linear's custom sync engine, covering state management, conflict resolution, and performance optimizations.
- **[The data model behind Notion's flexibility](https://www.notion.com/blog/data-model-behind-notion)** - Notion's engineering team explains their block-based data model and how it enables flexible, collaborative document editing.
- **[Extreme native perf on the web with Superhuman](https://syntax.fm/show/918/extreme-native-perf-on-the-web-with-superhuman)** - Technical insights into Superhuman's performance optimizations and architecture for achieving native-like performance in web applications.
- **[Building a real-time collaborative text editor for the web](https://medium.com/@david.roegiers/building-a-real-time-collaborative-text-editor-for-the-web-draftjs-sharedb-1dd8e8826295)** - A comprehensive guide to implementing collaborative text editing using DraftJS and ShareDB.
- **[Conflict-free replicated data types (CRDTs) explained](https://josephg.com/blog/crdts-are-the-future/)** - Joseph Gentle's influential blog post explaining CRDTs and their advantages over operational transforms.
- **[Creating a chat application with WebRTC](https://blog.logrocket.com/creating-chat-application-with-webrtc/)** - Technical guide to implementing real-time communication using WebRTC for peer-to-peer applications.

### Conceptual & Philosophical Resources

- **[Local-first software: You own your data, in spite of the cloud](https://www.inkandswitch.com/local-first/)** - The seminal 2019 essay from Ink & Switch that coined the term "local-first" and outlined its seven guiding ideals.
- **[The Computer as Malleable Material](https://www.inkandswitch.com/malleable-software/)** - A follow-up essay from Ink & Switch advocating for software that users can reshape and adapt to their own needs.
- **[How Linear's sync engine works](https://linear.app/blog/how-linear-s-sync-engine-works)** - A detailed, community-driven technical write-up of the high-performance sync engine behind the Linear application.
- **[CRDTs: The Hard Parts](https://www.youtube.com/watch?v=x7drE24geUw&pp=ygUVQ1JEVHM6IFRoZSBIYXJkIFBhcnRz)** - An expert-level talk by Dr. Martin Kleppmann exploring the challenging edge cases and nuances of Conflict-free Replicated Data Types.
