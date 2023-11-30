# **CS 410:** *Natural Language Processing (NLP)* **Group #3 Project**, Fall 2023
## *Portland State University* ([pdx.edu](https://pdx.edu)), *Maseeh College of Engineering & Computer Science* ([MCECS](https://pdx.edu/engineering/))

## by Dan Jang, Kobe Norcross, & Ahmad Alyajouri

### **Content Warning**:
*Alike many "natural language processing" oriented or sources for text & data, the text & data used in this project may have been collected from public websites or sources, and may be unfiltered. Thus, some text & data may be disturbing, disagreeable, or otherwise objectionable.*

## Description of our *Natural Language Processing* Project

This project seeks to look at the improvements of a specific *Natural Language Processing* related task, through the history of various [*OpenAI*](https://openai.com/)'s [*GPT*](https://platform.openai.com/docs/models/) (*Generative Pretrained Transformer*) models, and the historical effects (& performance) on proceeding models as released by [*OpenAI*](https://openai.com/blog/).

We will observe the historical effect on the efficacy & performance of a few, recent [*GPT*](https://platform.openai.com/docs/models/) (*Generative Pretrained Transformer*) models as released by [*OpenAI*](https://openai.com/blogs), over time, on *text summarization*.

Specifically, we will be observing the performance of *OpenAI* models [***```GPT-2```***](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf), [***```GPT-3```***](https://arxiv.org/abs/2005.14165)/[***```ChatGPT```***](https://openai.com/blog/chatgpt) ([***```gpt-3.5-turbo-1106```***](https://openai.com/blog/new-models-and-developer-products-announced-at-devday)), & [***```GPT-4```***](https://cdn.openai.com/papers/GPTV_System_Card.pdf) ([***```gpt-4-1106-preview```***](https://openai.com/blog/new-models-and-developer-products-announced-at-devday)) on the task of *text summarization* based on a set of text-prompt data - additionally, using the technique of [*prompt engineering*](https://arxiv.org/abs/2310.04438) with these models.

## Overview of the *Natural Language Processing* Project Codebase & Implementation

The implementation was done with a high-level implementation in-mind, with more emphasis made for the post-summarization analysis of performance & metrics.

## *Natural Language Processing* Project Performance & Metrics

We will be using three main metrics to analyze our results & gauge each model's *text summarization* task performance:

#1.) [**```ROUGE```**](https://aclanthology.org/W04-1013.pdf) (Recall-Oriented Understudy for Gisting Evaluation): Measures overlap between model-generated summaries and reference summaries.

#2.) [**```BLEU```**](https://doi.org/10.3115%2F1073083.1073135) (Bilingual Evaluation Understudy): Measures n-gram precision.

#3.) [**```METEOR```**](https://aclanthology.org/W05-0909.pdf) (Metric for Evaluation of Translation with Explicit ORdering): Evaluates the quality of the summaries by considering unigram matching, stemming, synonymy, and more.
