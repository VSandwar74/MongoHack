# MongoHack
Vishakh Sandwar, Archit Kulkarni, Kevin Chan

## Pipeline
- Built a scraping script to find urls on arxiv at random (will port to arxiv AWS API soon)
- Downloaded pdfs through Mixpeek API and dumped in MongoDB Atlas Vector Database
- Used Mixpeek Client's multimodal vector indexing and integrated Nomic-AI's embeddings into the extracted text
- From MongoDB Atlas Vector Database ported into Nomic Atlas visualization tool using PCA for dimensionality reduction, then t-SNE for further dimensionality reduction and visualization to compress R-d vector embeddings onto 2 high variances axes for visualization

## URL
(https://atlas.nomic.ai/data/vs2800/cynical-schmidhuber/settings)

Thank you to arXiv for use of its open access interoperability.

