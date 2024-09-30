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
## Citation

If you use this work, please cite it as:

```bibtex
@inproceedings{berezin-etal-2023-offence,
    title = "No offence, Bert - {I} insult only humans! Multilingual sentence-level attack on toxicity detection networks",
    author = "Berezin, Sergey  and
      Farahbakhsh, Reza  and
      Crespi, Noel",
    editor = "Bouamor, Houda  and
      Pino, Juan  and
      Bali, Kalika",
    booktitle = "Findings of the Association for Computational Linguistics: EMNLP 2023",
    month = dec,
    year = "2023",
    address = "Singapore",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.findings-emnlp.155",
    doi = "10.18653/v1/2023.findings-emnlp.155",
    pages = "2362--2369",
    abstract = "We introduce a simple yet efficient sentence-level attack on black-box toxicity detector models. By adding several positive words or sentences to the end of a hateful message, we are able to change the prediction of a neural network and pass the toxicity detection system check. This approach is shown to be working on seven languages from three different language families. We also describe the defence mechanism against the aforementioned attack and discuss its limitations.",
}
```

