# awesome-sync-engines

Local-first databases, CRDTs, sync engines

### Sync Platforms & Backends-as-a-Service (BaaS)

- **[PartyKit](https://www.partykit.io/)** - Edge-deployed stateful servers with WebSocket connections for real-time multiplayer synchronization. Implements room-based state management with automatic persistence and scaling. [GitHub](https://github.com/partykit/partykit)
- **[Convex](https://www.convex.dev/)** - Reactive database with automatic subscription management and real-time query invalidation. Uses TypeScript for schema definition and implements optimistic updates with conflict resolution. [GitHub](https://github.com/get-convex/convex-backend)
- **[InstantDB](https://www.instantdb.com/)** - Client-side database with declarative queries and automatic optimistic updates. Implements offline-first architecture with conflict-free synchronization to backend. [GitHub](https://github.com/instantdb/instant)
- **[Liveblocks](https://liveblocks.io/)** - WebSocket-based collaboration infrastructure with presence awareness, cursor tracking, and document synchronization protocols. [GitHub](https://github.com/liveblocks/liveblocks)

### Sync Infrastructure & Libraries

- **[ElectricSQL](https://electric-sql.com/)** - PostgreSQL logical replication with client-side SQLite synchronization. Implements bidirectional sync using write-ahead logs and conflict resolution through last-write-wins semantics. [GitHub](https://github.com/electric-sql/electric)
- **[PowerSync](https://www.powersync.com/)** - Database synchronization layer that replicates server-side PostgreSQL/MySQL/MongoDB changes to client-side SQLite using incremental sync and conflict resolution. [GitHub](https://github.com/powersync-ja/powersync-js)
- **[Ditto](https://ditto.live/)** - Peer-to-peer mesh database with CRDT-based synchronization. Implements multi-hop data propagation and works without internet connectivity using Bluetooth, WiFi, and LoRaWAN.
- **[Replicache](https://replicache.dev/)** - Client-side sync framework implementing optimistic UI patterns with server reconciliation. Uses mutation functions and implements speculative execution with rollback capabilities. [GitHub](https://github.com/rocicorp/replicache)
- **[Logux](https://logux.org/)** - Action-based synchronization protocol that maintains a distributed log of operations. Implements automatic conflict resolution and supports both client-server and peer-to-peer architectures. [GitHub](https://github.com/logux/logux)

### Local-First Databases

- **[pglite](https://pglite.dev/)** - PostgreSQL compiled to WebAssembly for in-browser execution. Implements full PostgreSQL compatibility including extensions and provides filesystem persistence via OPFS. [GitHub](https://github.com/electric-sql/pglite)
- **[Livestore](https://livestore.dev/)** - Embedded SQLite database with reactive queries and Git-like versioning system. Implements automatic schema migrations and conflict-free synchronization using vector clocks. [GitHub](https://github.com/livestorejs/livestore)
- **[RxDB](https://rxdb.info/)** - NoSQL database implementing reactive programming patterns with observable queries. Uses adapters for IndexedDB, LevelDB, and in-memory storage with CouchDB-style replication. [GitHub](https://github.com/pubkey/rxdb)
- **[PouchDB](https://pouchdb.com/)** - JavaScript implementation of CouchDB's replication protocol. Stores documents locally using IndexedDB/WebSQL and synchronizes via HTTP-based replication with conflict resolution. [GitHub](https://github.com/pouchdb/pouchdb)
- **[SignalDB](https://signaldb.js.org/)** - In-memory database implementing reactive queries using the Signals pattern. Provides automatic dependency tracking and re-computation of derived state. [GitHub](https://github.com/maxnowack/signaldb)
- **[KuzuDB](https://kuzudb.com/)** - Embedded graph database implementing Cypher query language. Uses columnar storage for nodes and edges with vectorized query execution. [GitHub](https://github.com/kuzudb/kuzu)

### Core Data Structures & Algorithms

- **[Yjs](https://yjs.dev/)** - CRDT implementation using operation-based shared types (Y.Array, Y.Map, Y.Text). Implements delta compression and supports various network layers including WebSocket, WebRTC, and HTTP. [GitHub](https://github.com/yjs/yjs)
- **[Automerge](https://automerge.org/)** - JSON CRDT implementation using immutable data structures and vector clocks. Implements automatic merge resolution for concurrent edits with complete operation history tracking. [GitHub](https://github.com/automerge/automerge)
- **[Loro](https://loro.dev/)** - CRDT library implementing tree-based data structures for rich text and hierarchical content. Uses Rust-based core with WebAssembly bindings and maintains full version history with branch merging. [GitHub](https://github.com/loro-dev/loro)

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
- **[CRDTs: The Hard Parts](https://www.youtube.com/watch?v=x7drE24geUw&pp=ygUVQ1JEVHM6IFRoZSBIYXJkIFBhcnRz)** - An expert-level talk by Dr. Martin Kleppmann exploring the challenging edge cases and nuances of Conflict-free Replicated Data Types.
