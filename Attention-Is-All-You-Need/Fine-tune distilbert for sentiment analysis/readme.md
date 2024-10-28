# Fine-Tune a Transformer for Sentiment Analysis

I chose DistilBert and the IMDB movie reviews dataset. I used the Trainer API from the Transformers library to facilitate the fine-tuning process.

---



# Why DistilBERT?

DistilBERT is a lightweight version of BERT (Bidirectional Encoder Representations from Transformers). It retains 97% of BERT’s performance but is 60% smaller and 60% faster.

Faster training and inference: Because it’s smaller, DistilBERT is quicker to fine-tune and requires less computational power. This is ideal for smaller datasets or limited resources.

Good baseline performance: Despite being distilled (a process that compresses the model), it still performs well on a wide range of NLP tasks.


# Why the Trainer API?



Reduces Boilerplate Code: Instead of manually coding training loops, data loaders, and logging, you get these features built-in, reducing the setup time and lines of code.

Flexibility: It allows customizing the training parameters, evaluation metrics, logging frequency, and checkpointing—making it suitable for many kinds of tasks.

Optimized for Transformers: Specifically designed to work efficiently with Transformers, Trainer handles tasks like gradient clipping and distributed training which are often required for larger models.

---

TODO:
- [ ] display accuracy and other metrics
