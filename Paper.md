### Paper

![](image/poster.png)

You can refer to our [paper](https://arxiv.org/abs/1902.01718) for detail.

We proposed an end-to-end open-domain question answering system called BERTserini. 
The main idea is combing IR toolkit with machine reader. 
When user proposed an open-domain question, we use Anserini, an open-source information 
retrieval toolkit to extract the most related document from wikipedia. 
Then we apply BERT, the state of the art pre-trained language representation model, 
to identify the answer span in the document.  We finally rerank the candidates using 
weighted score from both system. 

