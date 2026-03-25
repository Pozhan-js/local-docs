# local-docs

Private knowledge base repository for project summaries, troubleshooting notes, and conversation-derived knowledge artifacts.

## Structure
- `knowledge/conversations/`: Structured knowledge generated from chat conversations.
- `index/documents.json`: Document metadata index for retrieval pipelines.
- `index/tags.json`: Tag-to-document mapping.
- `index/relations.json`: Lightweight cross-document relationship data.

## Retrieval
The repository stores Markdown documents with stable frontmatter and section structure so they can be consumed by pageIndex-style pipelines or custom indexing scripts.

## Sync
Changes are committed and then pushed to the remote GitHub repository through GitHub MCP by default.