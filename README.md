# No Offence, Bert - I Insult Only Humans!

This repository contains the code for the paper ["No offence, Bert - I insult only humans! Multiple addressees sentence-level attack on toxicity detection neural networks"](https://aclanthology.org/2023.findings-emnlp.155/), presented at the EMNLP 2023 conference. This paper introduces a novel, highly effective attack on state-of-the-art toxicity detection models, including **Google Perspective API and OpenAI Moderation API**.



## Introduction

Toxicity detection systems are widely used in social media platforms to moderate harmful content. However, these systems can be vulnerable to adversarial attacks. This repository provides the implementation of a sentence-level attack on black-box toxicity detection models by adding positive words or sentences to toxic messages to bypass the detection.

## Features
- **Unmatched Effectiveness:** Demonstrated success against leading toxicity detection models.
- **Multi-Language Support:** Effective in English, Russian, German, French, Portuguese, Spanish, Turkish, and Vietnamese.
- **Comprehensive Attack Methods:** Includes both word-based and sentence-based attack strategies.
- **Defense Mechanism:** Provides an adversarial training defense to improve model resilience.

### Word-Based Attack in English on Perspective API and OpenAI Moderation API

| n words | OpenAI S | OpenAI L | Per. API |
|---------|----------|----------|----------|
| 1       | 0.643    | 0.946    | 0.899    |
| ...     | ...      | ...      | ...      |
| 10      | 0.421    | 0.847    | 0.846    |
| 11      | 0.381    | 0.705    | 0.852    |
| 12      | 0.427    | 0.74     | 0.852    |
| 13      | 0.453    | 0.761    | 0.852    |
| 14      | 0.426    | 0.665    | 0.853    |
| 15      | 0.362    | 0.681    | 0.853    |
| 16      | 0.265    | 0.716    | 0.853    |

*Table 2: Word-based attack in English on Perspective API and OpenAI Moderation API. Per. - perspective, S - stable, L - latest.*


