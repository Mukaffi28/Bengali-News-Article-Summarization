# Bengali News Article Summarization
## Overview
This repository contains the implementation of a Bengali News Article Summarization model, utilizing two powerful variants:

<ol>
    <li><strong>banglaT5:</strong> A dedicated Bengali transformer model designed for natural language processing tasks, including summarization.</li>
    <li><strong>mT5 (Multilingual Text-to-Text Transfer Transformer 5):</strong> A versatile multilingual transformer model capable of handling various NLP tasks, including summarization, across multiple languages.</li>
  </ol>

  <h2>Evaluation Metrics</h2>

  <p>The performance of both summarization models is assessed using the following evaluation metrics:</p>

  <ul>
    <li><strong>CER (Character Error Rate):</strong> Measures the percentage of characters that are incorrectly predicted in the generated summary compared to the reference summary.</li>
    <li><strong>WER (Word Error Rate):</strong> Similar to CER but operates at the word level, measuring the percentage of words that differ between the generated and reference summaries.</li>
    <li><strong>BLEU (Bilingual Evaluation Understudy):</strong> Evaluates the quality of the generated summary by comparing it to reference summaries based on precision and recall of n-grams.</li>
    <li><strong>Exact Match:</strong> Calculates the percentage of generated summaries that match the reference summaries exactly, without any differences.</li>
    <li><strong>ROUGE (Recall-Oriented Understudy for Gisting Evaluation):</strong> Measures the overlap of n-grams (unigrams, bigrams, etc.) between the generated and reference summaries.</li>
  </ul>


