![Brirish-Airways-Logo](https://raw.githubusercontent.com/swalehmwadime/British-Airways-Ds/9235eaeb620f1987f3def874d539a62297da9f30/british-airways%20logo.png)
# British Airways Data Science Project

We shall be analyzing customer reviews of British Airways (BA) to gain insights into customer sentiment, preferences, and areas for improvement. The goal is to leverage data science techniques to extract valuable insights from customer feedback data.

## Overview

British Airways (BA) is the flag carrier airline of the United Kingdom (UK). With thousands of flights departing and arriving daily, BA serves a diverse range of customers. Understanding customer feedback is crucial for improving service quality, enhancing customer satisfaction, and making informed business decisions.

## Data Collection

The data for this project was collected from the [Airline Quality website](https://www.airlinequality.com/airline-reviews/british-airways). The website contains customer reviews specifically about British Airways. Reviews were scraped using Python and BeautifulSoup, collecting both review text and recommendations.

## Data Analysis

### Sentiment Analysis
- Sentiment analysis was performed on the review text to determine the overall sentiment (positive, negative, neutral) of customer feedback.
- ![customer-Feedback](https://github.com/swalehmwadime/British-Airways-Ds/blob/main/Images/customer%20feedback.png)
- The TextBlob library was used to calculate sentiment polarity.

### Recommendation Analysis
- The recommendations provided by customers (whether they recommend BA or not) were analyzed to understand customer satisfaction levels.
- Positive and negative recommendation percentages were calculated.

### Word Frequency Analysis
![Word-Frequency](https://github.com/swalehmwadime/British-Airways-Ds/blob/main/Images/word%20frequency.png)
- Word frequency analysis was conducted to identify common topics or concerns raised by customers.
- Word clouds were generated to visualize the most frequent words in positive and negative reviews.
- ![Word-cloud](https://github.com/swalehmwadime/British-Airways-Ds/blob/main/Images/word%20cloud%20reviews.png)

## Results

- Overall sentiment towards British Airways was predominantly positive, with a sentiment polarity score of X.
- X% of customers recommended BA, indicating high levels of satisfaction.
- Common topics mentioned in positive reviews include excellent service, comfortable flights, and friendly staff.
- Negative reviews often mentioned issues related to flight delays, customer service responsiveness, and baggage handling.

## Conclusion

The analysis of customer reviews provides valuable insights into customer sentiment and preferences. By addressing areas of improvement highlighted in negative reviews, British Airways can enhance customer satisfaction and loyalty. Additionally, positive feedback can be leveraged to reinforce and promote BA's strengths.

## Notebooks
- Run notebooks on Google colab <br>
[BA1 notebook](https://colab.research.google.com/drive/1sXcZZpE_d9isISxd0fZqI2mOwszFp9XJ#scrollTo=pGO0VAg-i7pl)    <br>
[BA2 notebook](https://colab.research.google.com/drive/1n0BTvnOdbDGRp48cn7sXHjVgjefZcxcE#scrollTo=K4b8mGISLlSB)

## Future Work

- Explore advanced sentiment analysis techniques, such as aspect-based sentiment analysis, to gain deeper insights into specific aspects of customer experience.
- Incorporate machine learning models to predict customer sentiment and identify potential issues in real-time.
- Expand data collection to include additional sources, such as social media platforms, to capture a broader range of customer feedback.

---

