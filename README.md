# Text-Summarization

This project is an in-depth exploration of Natural Language Processing (NLP) techniques, focusing on text summarization and evaluation using state-of-the-art tools like BERT (Bidirectional Encoder Representations from Transformers) and ROUGE (Recall-Oriented Understudy for Gisting Evaluation) metrics. The main objective is to assess the effectiveness of machine-generated summaries against human-written references.

Utilizing the HuggingFace `transformers` library, I leveraged the `sshleifer/distilbart-cnn-12-6` model to generate concise summaries of lengthy articles, in this case, the Daily Mail reviews. The aim was to condense the content while retaining key information and context.

ROUGE-2, which emphasizes the overlap of bigrams between the generated summary and the reference text, was calculated for each summary to determine its closeness to the actual article content. Additionally, BERT, a more recent and contextually-aware evaluation method, was employed to compute the F1 scores for these summaries. This helped in understanding the semantic coherence and relevance of the generated summaries.

The results of both ROUGE-2 and BERT scores were meticulously compiled and analyzed. The average scores provided insights into the effectiveness of the summarization model and highlighted areas for improvement. This project not only served as a practical application of advanced NLP techniques but also contributed valuable insights into the effectiveness of automatic text summarization in comparison to human benchmarks.
