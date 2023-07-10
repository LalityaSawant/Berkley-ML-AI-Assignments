# Repository: Berkley-ML-AI

## This Repository Contains the Data Analysis for "Will a customer accept the coupon?" problem provided in Assignment 5:1

### **Data:**
The dataset provided was from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, passenger, etc., and then asks people whether they will accept the coupon if they are the driver. Answers given that the users will drive there “right away” or “later before the coupon expires” are labeled as “Y = 1”, and answers “no, I do not want the coupon” are labeled as “Y = 0”. There are five different types of coupons—less expensive restaurants (under $20), coffee houses, carry out and take away, bars, and more expensive restaurants ($20–$50).


## **Analysis Report:**                         
#####                                                  Author - Lalitya Sawant
## Investigating Coupon Acceptance and analyzing Bar and Coffee House Coupons
#### Python Notebook: https://github.com/LalityaSawant/Berkley-ML-AI-Assignments/blob/master/assignment_5_1_starter/prompt_Lalitya_Sawant.ipynb
#### Charts folder: https://github.com/LalityaSawant/Berkley-ML-AI-Assignments/tree/master/assignment_5_1_starter/images

### **Introduction:**
  This analysis report aims to examine the acceptance rate of coupons among drivers and investigate the behavior of drivers who accepted bar and coffee house coupons. Additionally, we will provide recommendations for further analysis and strategies based on the findings.

### *The proportion of total observations accepting the coupon:*
  The acceptance rate for coupons among drivers is 43%. This indicates that a significant portion of drivers is willing to take advantage of the offered discounts.

### *Visualization of coupon preferences:*
  Based on the bar plot visualization of the coupon column, it is evident that coffee house coupons have the highest preference among drivers. Cheap restaurant coupons ("Restaurant(<20)") are the second most accepted category of coupons by drivers. This suggests that drivers prioritize coffee house coupons over other categories of coupons offered.

### *Visualization of temperature distribution:*
  The histogram visualization of the temperature column shows that the majority of the data is skewed toward a temperature of 80°F. This indicates that the data collection has primarily occurred during sunny weather conditions. To better predict driver's behavior for different types of coupon acceptance, it is recommended to collect more data for various weather conditions, ensuring a more comprehensive representation.

**Hypotheses regarding drivers accepting bar coupons:**

  * **Acceptance rate:** Out of the observed data, 41% of the bar coupons were accepted by drivers. This suggests a moderate interest in bar-related promotions.
  * **Frequency of bar visits:** Drivers who visit bars 1 to 3 times a month accepted the highest number of bar coupons. This finding highlights the importance of targeting drivers with a moderate level of engagement with the bar scene.
  * **Age group:** Drivers in the age group around 26 years were the most likely to accept bar coupons. Understanding the motivations and preferences of this demographic can aid in tailoring marketing efforts.
  * **Influence of companions:** Drivers accompanied by friends were more likely to accept bar coupons. Leveraging social dynamics and encouraging group experiences may increase the acceptance rate of bar coupons.

  **Next Steps and Recommendations:**

  * **Weather data collection:** Expand data collection efforts to include a wider range of weather conditions to provide a more comprehensive understanding of driver behavior for different types of coupon acceptance. This will enable better predictions and targeted marketing strategies.

  * **Demographic analysis:** Further investigate the age group around 26 years to gain deeper insights into their motivations and preferences. Conduct surveys or focus groups to gather qualitative data and refine marketing strategies to effectively target this demographic.

  * **Promote group experiences:** Develop marketing campaigns that emphasize the social aspect of visiting bars, targeting drivers who are more likely to accept bar coupons when accompanied by friends. Encourage group discounts or incentives to further incentivize group outings.


**Hypotheses regarding drivers accepting Coffee House coupons:**

 **- Gender-based analysis:**

  * Single male drivers exhibit a higher tendency to accept coffee coupons compared to females.
  * Married female drivers tend to accept more coffee coupons, indicating a potential preference for coffee-related offers.

  **- General analysis on drivers who accept coffee house coupons:**

  * Drivers heading to non-urgent places, followed by those going to the office, show a higher likelihood of accepting coffee coupons. This suggests that drivers who have more flexibility in their schedules or who are not in a rush are more receptive to coffee offers.
  * Solo drivers are more likely to accept coffee coupons, followed by drivers traveling with friends. This finding suggests that individuals who are alone or with friends may have different motivations or preferences when it comes to accepting coffee coupons.
  * The most popular time slots for accepting coffee coupons are around 10 am and 6 pm. This aligns with typical coffee consumption patterns during morning and evening hours.
  * Coupons with a one-day expiration period are more accepted than short-lived coupons. Drivers may prefer offers with longer validity to ensure they have enough time to redeem the coupons.
  * Female drivers exhibit a higher likelihood of accepting coffee coupons, indicating a potential gender preference for coffee-related promotions.
  * Among different age groups, drivers in the age group of 21 show a higher tendency towards accepting coffee coupons, followed by the age group of 26. Understanding the preferences and motivations of these age groups can help tailor marketing efforts accordingly.
  * Single drivers and drivers with no kids also show interest in accepting coffee house coupons. These demographics may have more flexibility in their schedules or be more open to trying new experiences.

  **Next Steps and Recommendations:**

  * **Targeted marketing campaigns:** Utilize the insights gained from the analysis to develop targeted marketing campaigns. Tailor the messaging and channels to effectively reach single male drivers, married female drivers, and female drivers in general, highlighting the benefits of coffee-related offers.

  * **Personalized offers:** Consider offering personalized coupons to drivers based on their preferred time slots, such as morning or evening hours. This can enhance the relevance and appeal of the offers.

  * **Collaborations and partnerships:** Explore partnerships with non-urgent places or offices to offer joint promotions. This can attract drivers who frequently visit these locations and increase the acceptance rate of coffee coupons.

  * **Customer feedback:** Engage with customers to gather feedback on coffee house coupons. Understand the reasons behind the preference for accepting longer expiration period coupons and leverage this insight to refine coupon designs and offerings.


## **Conclusion:**
  Based on the analysis of bar and coffee house coupons, several hypotheses have been identified regarding the characteristics and preferences of drivers who accept these coupons. Targeted marketing campaigns, personalized offers, collaborations, and gathering customer feedback can further optimize the acceptance rate and engagement of drivers for any category of coupons. By implementing these recommendations, businesses can effectively reach and cater to the preferences of their target audience, ultimately driving increased coupon acceptance and customer satisfaction.
