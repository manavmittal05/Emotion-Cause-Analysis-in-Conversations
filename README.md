# Emotion Recognition and Cause Detection in Conversations

This project aims to integrate emotional dynamics with advanced NLP techniques to build a model capable of identifying emotions and their triggers in conversations. Our model predicts not only the emotions of each speaker but also the causes behind those emotions, leveraging both modern machine learning techniques and psychological insights.

## Introduction

Incorporating human emotional dynamics alongside modern computational linguistics and natural language processing (NLP) methods is a promising frontier for improving machine understanding of human interactions. This project addresses the challenge of predicting the causes and triggers of emotions in conversation, whether they arise from specific statements or inherent personal feelings.

By integrating **Transformers**, **Attention Mechanisms**, and **Convolutional Neural Networks (CNNs)**, along with psychological insights like the **Myers-Briggs Type Indicator (MBTI)**, our model predicts emotions, emotional causes, and triggers in a conversation.

## Problem Statement

We tackle two key tasks in this project:

1. **Emotion Recognition**: Identify the emotion expressed in each utterance of a conversation.
2. **Cause Detection**: Identify the cause of the current emotion of the speaker by pinpointing which part of a prior utterance triggered the emotion. This is done for each utterance in the conversation, as multiple causes may exist.

### Input
- A conversation containing the speaker's name and the text of each utterance.

### Output
- Emotion-cause pairs: Each pair consists of an emotion, its corresponding utterance, and the exact text span of the utterance that caused the emotion.
  
**Example**:  
For a conversation:

```plaintext
U1: "You never listen to me."
U2: "I'm sorry, I just forget sometimes."
U3: "You made up!"
