# AI Study Material

Interactive study notes on AI retrieval architecture, published as a static site with GitHub Pages.

## Live site

- [AI Study Material](https://dharmsonariya.github.io/ai-study-material/) — landing page
- [Advanced RAG Strategies Taxonomy](https://dharmsonariya.github.io/ai-study-material/advanced-rag/) — 14 strategies across the RAG pipeline: prepare knowledge (chunking, enrichment, encoding), shape the query, retrieve and select, orchestrate and verify
- [Knowledge Bases Taxonomy](https://dharmsonariya.github.io/ai-study-material/knowledge-bases/) — Amazon Bedrock Knowledge Bases as a family of retrieval architectures: operating models, architecture shapes, sources, preparation, encoding, stores, retrieval, and fast paths by intent

## Preview locally

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Update the site

Edit the HTML files, then:

```
git add .
git commit -m "Describe the change"
git push
```

GitHub Pages redeploys automatically from the `main` branch.

## Add a topic

Create a new folder with an `index.html` (e.g. `graphrag/index.html`), add a card linking to it on the landing page, and link it in the Live site section above.
