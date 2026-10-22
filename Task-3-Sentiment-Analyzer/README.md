# Task 3: Semantic Sentiment & Urgency Analyzer

## Internship

Growfinix AI Internship

## Objective

The objective of this project is to analyze customer feedback or support messages using sentiment analysis and urgency classification.

## Technology Stack

* Python
* Hugging Face Inference API
* Natural Language Processing (NLP)

## Project Description

This project analyzes customer feedback and support tickets to identify the sentiment expressed in a message and determine how urgently it needs attention.

Instead of only classifying a message as positive or negative, the analyzer also identifies the main complaint or praise and assigns an urgency level.

## Key Features

* Analyzes customer feedback and support messages.
* Classifies sentiment as Positive, Negative, or Neutral.
* Identifies urgency as High, Medium, or Low.
* Extracts the main complaint or praise from the message.
* Helps prioritize customer support responses.

## Project Structure

* `main.py` – Main Python program for sentiment and urgency analysis.
* `tests/` – Test cases for checking the analyzer's functionality.
* `README.md` – Project documentation.

## How to Run

Run the Python program using:

```bash
python main.py
```

If the project requires additional Python packages, install them according to the project's dependency instructions.

## Example

**Input:**

```text
I am very disappointed. My payment was deducted, but my order has not been delivered. Please resolve this issue immediately.
```

**Illustrative Expected Output:**

```json
{
  "sentiment": "Negative",
  "urgency": "High",
  "main_issue": "Payment deducted but order not delivered"
}
```

*Note: This is an illustrative example. The actual output depends on the implementation and AI model.*

## Learning Outcomes

* Understood sentiment analysis using NLP.
* Learned to classify customer messages by urgency.
* Practiced extracting meaningful information from unstructured text.
* Explored how AI can help prioritize customer support tickets.

## Conclusion

This project demonstrates how sentiment analysis and urgency classification can help support teams understand customer concerns and prioritize responses effectively.
