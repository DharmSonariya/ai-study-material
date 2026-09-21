# AI Study Material

Interactive study notes on AI retrieval architecture, published as a static site with GitHub Pages.

## Pages

- **Advanced RAG Strategies Taxonomy** (`advanced-rag/`) — 14 strategies across the RAG pipeline: prepare knowledge (chunking, enrichment, encoding), shape the query, retrieve and select, orchestrate and verify.
- **Knowledge Bases Taxonomy** (`knowledge-bases/`) — Amazon Bedrock Knowledge Bases as a family of retrieval architectures: operating models, architecture shapes, sources, preparation, encoding, stores, retrieval, and fast paths by intent.

## Preview locally

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Publish with GitHub Pages

```
git init
 git add .
 git commit -m "Initial study material site"
 gh repo create ai-study-material --public --source=. --push
```

Then enable Pages: repo Settings → Pages → Deploy from branch → `main` / root.

## Add a topic

Create a new folder with an `index.html` (e.g. `graphrag/index.html`) and add a card linking to it on the landing page.
