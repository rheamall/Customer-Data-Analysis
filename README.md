# Customer Data Analysis

Scraped and analysed customer review data using a large language model (LLM) to uncover findings for British Airways. Developed predictive machine learning models, achieving a prediction accuracy of 85.1%, to discover factors that influence buying behaviour.

### Objectives

The aim of this project was to analyze customer review data and predict factors influencing flight bookings using machine learning techniques. Specifically, I sought to do 2 things:
- Uncover key themes in customer feedback using topic modelling and NLP techniques.
- Develop predictive models to determine factors influencing customer booking behavior.

### Tools & Technologies Used

- Python 
- Libraries: Pandas, NumPy, Scikit-learn, NLTK, Transformers (Hugging Face), Matplotlib, Seaborn
- Machine Learning Models: Random Forest, Logistic Regression, Gradient Boosting, XGBoost, RoBERTa (for NLP-based sentiment analysis)

### Challenges Faced

- Data Preprocessing: Cleaning and structuring unstructured customer review data for analysis.
- Model Performance: Experimenting with multiple classification models to optimize accuracy and interpretability.

### Key Actionable Insights

#### Customer Reviews 
- 43.4% of the customer reviews were of a negative sentiment, and 30.4% were positive.
- Using Latent Dirichlet allocation, I segregated the reviews into 5 broad topics:
  1. Check-in, boarding and luggage
  2. Customer service and booking
  3. Customer service, seat and class experience
  4. In-flight experience
  5. Flight timings and delays

I identified common pain points in reviews, such as flight delays and customer service, which negatively impacted customer sentiment. A majority of the reviews centred around in-flight experience were **positive**, and a vast majority of reviews centred around customer service were **negative**. Addressing these areas could significantly enhance customer satisfaction and brand loyalty.

#### Flights Booking Behaviour Analysis
- Irrespective of the duration of the flight, 60% or more customers wanted extra baggage allowance in their booking. 
- Less than 35% of customers wanted a preferred choice of seat when booking a flight. However, more passengers wanted a preferred seat when the flight duration was longer. More passengers also wanted an in-flight meal when the flight duration is longer.
- The random forest classifier had an accuracy of **85.1%** when predicting whether or not a particular customer would complete their booking. The three most influential factors in this prediction were:
  1. purchase_lead = number of days between travel date and booking date
  2. flight_hour = hour of flight departure
  3. length_of_stay = number of days spent at destination
Understanding these factors would allow for better customer segmentation and tailored marketing strategies. For instance, customers booking closer to the travel date might be more responsive to last-minute deals, whereas those booking far in advance could benefit from early-bird discounts.

### Conclusion

I made use of NLP to extract valuable insights from customer reviews, and by leveraging a combination of machine learning models, I uncovered factors influencing customer booking behavior with 85.1% accuracy. These insights can help British Airways refine marketing strategies, enhance customer service and optimize pricing models. Continuous iteration and experimentation with advanced techniques could further refine these predictions and drive better business outcomes.

### Feedback is welcome. Connect with me:

- Linkedin: https://www.linkedin.com/in/rheamall
- Email: rheadeepamall@gmail.com
