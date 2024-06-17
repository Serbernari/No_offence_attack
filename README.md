# Toxicity_attack
aper https://aclanthology.org/2023.findings-emnlp.155/

# No Offence, Bert - I Insult Only Humans!

This repository contains the code for the paper ["No offence, Bert - I insult only humans! Multiple addressees sentence-level attack on toxicity detection neural networks"](https://aclanthology.org/2023.findings-emnlp.155/), presented at the EMNLP 2023 conference. This paper introduces a novel, highly effective attack on state-of-the-art toxicity detection models, including **Google Perspective API and OpenAI Moderation API**.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Experiments](#experiments)
- [Results](#results)
- [Contributors](#contributors)
- [License](#license)

## Introduction

Toxicity detection systems are widely used in social media platforms to moderate harmful content. However, these systems can be vulnerable to adversarial attacks. This repository provides the implementation of a sentence-level attack on black-box toxicity detection models by adding positive words or sentences to toxic messages to bypass the detection.

## Features
- **Unmatched Effectiveness:** Demonstrated success against leading toxicity detection models.
- **Multi-Language Support:** Effective in English, Russian, German, French, Portuguese, Spanish, Turkish, and Vietnamese.
- **Comprehensive Attack Methods:** Includes both word-based and sentence-based attack strategies.
- **Defense Mechanism:** Provides an adversarial training defense to improve model resilience.

## Installation

Clone the repository and install the required dependencies:
```bash
git clone https://github.com/yourusername/toxicity-detection-attack.git
cd toxicity-detection-attack
pip install -r requirements.txt

