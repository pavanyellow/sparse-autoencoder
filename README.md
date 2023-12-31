# Sparse Autoencoder Features

Interpreting the ultra-low density cluster in sparse autoencoders from [Anthropic](https://transformer-circuits.pub/2023/monosemantic-features/index.html#appendix-feature-density).

Interesting findings:
- Features in ultra low cluster have very high loss  
- Average loss vs frequency shows phase transition
- Low loss features more likely to be interpretable
<img width="629" alt="Screenshot 2023-12-05 at 10 37 37 PM" src="https://github.com/pavanyellow/sparse-autoencoder/assets/17449478/8a119de6-b283-4dbb-bfdf-f59c2b84dd1f">

Successfully interpreted several low frequency features. Built upon opensourced work from [Neel Nanda](https://www.alignmentforum.org/posts/fKuugaxt2XLTkASkk/open-source-replication-and-commentary-on-anthropic-s).

[Notebook](https://colab.research.google.com/drive/19WG5bpa0vatr71cFf6qFSJcOZT8f34xi) | [Report](https://docs.google.com/document/d/1WIT25qFlbU3MgrvTbl-Q3PhccBpNvRpZhuNlfSNhOq8/edit)
