This repository provides documentation for the MongoDB technical posting https://programmar7.wordpress.com/2026/04/17/optimizing-slow-queries-with-mongodbs-tim-kelly-part-one/

It includes custom .pdf, .md, MongoDB tuning mindmap and handy performance tuning guide that makes targets 7 areas:


MongoDB query tuning guide covering the full diagnostic and optimization lifecycle organized into seven sections:

1. Diagnosing slow queries — profiler setup, explain() interpretation, Atlas tools
2. Indexing strategies — single-field, compound, covered queries, partial, text, and wildcard indexes, including the ESR rule
3. Query patterns to avoid — unanchored regex, negation operators, $where, large $in arrays
4. Aggregation pipeline optimization — stage ordering, early projection, $lookup tuning
5. Schema design — embedding vs. referencing, unbounded arrays, the bucket pattern
6. Connection and config tuning — pool sizing, read preferences, write concern tradeoffs
7. Monitoring and maintenance — index usage stats, rolling index builds, ongoing hygiene
