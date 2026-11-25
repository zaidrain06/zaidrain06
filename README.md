## Hi, I'm Ömer Said Yağmur, you can call me Said 👋

Software and database engineer based in Türkiye. I work mostly with **C#, Python, SQL, C++, Go and Oracle**, and I like digging into database engines, storage internals, and data infrastructure.

### Open source

**Merged & Credited**
- [open-telemetry/opentelemetry-collector-contrib#53463](https://github.com/open-telemetry/opentelemetry-collector-contrib/pull/53463): fix OTTL string-indexing parser ambiguity on map paths and string literals (`pkg/ottl`)
- [duckdb/duckdb#28563](https://github.com/duckdb/duckdb/pull/28563): fix for `contains(list_column, '')` returning true for lists that do not contain the value
- [repowise-dev/repowise#5995](https://github.com/repowise-dev/repowise/pull/5995): validate Git repository root before diffing in `repowise impacted-tests`
- [pydantic/pydantic-ai#13272](https://github.com/pydantic/pydantic-ai/pull/13272): credited for the store-side fix ([#12826](https://github.com/pydantic/pydantic-ai/pull/12826)) preventing `ConversationStore.save` from re-storing serialized output-tool history as a new branch every turn
- [SparcleHQ/bolt-apps#43](https://github.com/SparcleHQ/bolt-apps/pull/43): credited for identifying and resolving `icon_unknown` launcher schema mismatches across gallery Boltpacks
- [vmangos/core#3606](https://github.com/vmangos/core/pull/3606): fix C++ compilation with OpenSSL 4.0+ where `OPENSSL_atexit` was removed

**Open pull requests**
- [ConduitIO/conduit#3373](https://github.com/ConduitIO/conduit/pull/3373): restore in-memory `processor.Service` instance when `ProcessorOrchestrator.Delete` rolls back a failed DB transaction
- [authzed/spicedb#3529](https://github.com/authzed/spicedb/pull/3529): use slash-separated `fs.FS` paths for composable schema subdirectory imports on Windows
- [galaxy-io/filament#785](https://github.com/galaxy-io/filament/pull/785): Twilio SendGrid v3 source connector (marketing lists, contacts, Single Sends, templates, incremental Unix-second suppression streams, and daily delivery stats)
- [galaxy-io/filament#714](https://github.com/galaxy-io/filament/pull/714): native Go Apple App Store Connect source connector (`ES256` JWT auth, JSON:API pagination, in-memory gzipped TSV parser, restated event-date dedup & segment URL refresh for Analytics & Sales reports)
- [mautic/mautic#18296](https://github.com/mautic/mautic/pull/18296): preserve configured global `Reply-To` for ownerless contacts in queued batch emails and prevent batch merging with owned contacts sharing a fallback sender
- [duckdb/duckdb#28853](https://github.com/duckdb/duckdb/pull/28853): allow concurrent reads of active log files on Windows in `BufferedFileWriter`
- [duckdb/duckdb#28837](https://github.com/duckdb/duckdb/pull/28837): bound snapshots below WAL-skipping commits until checkpoint completes
- [duckdb/duckdb#28554](https://github.com/duckdb/duckdb/pull/28554): avoid copying `BoundSubqueryExpression` in collated `min`/`max` binding
- [ClickHouse/ClickHouse#129979](https://github.com/ClickHouse/ClickHouse/pull/129979): fix signed `Int64` overflow when computing fraction in `roundTimeConstant`
- [temporalio/api-go#326](https://github.com/temporalio/api-go/pull/326): skip visiting compute config payloads in `VisitPayloads`
- [onyx-dot-app/onyx#17040](https://github.com/onyx-dot-app/onyx/pull/17040): add Jira Service Management connector
- [serpapi/nokolexbor#53](https://github.com/serpapi/nokolexbor/pull/53): cache compiled CSS selector lists in a per-thread LRU cache
- [temporalio/sdk-go#2910](https://github.com/temporalio/sdk-go/pull/2910): include activity ID in local activity panic stack trace logging
- [basicmachines-co/basic-memory#2135](https://github.com/basicmachines-co/basic-memory/pull/2135): slice PostgreSQL full-text search chunk inserts into bounded JSONB batches

### Interests
Query engines, analytical databases, storage/WAL internals, and developer tooling.

### Contact
- **Email:** saidyagmur@gmx.com
- Available for **async B2B engineering contracts** and technical systems work. You can also open an issue or reach out through GitHub.
