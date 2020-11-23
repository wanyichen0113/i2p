# Data Biography

## Student Number: 20189247

---

### 1. Who collected the data?

_Airbnb collects data from users who have registered to rent houses in London on the platform. Data scientists of Inside Airbnb made the data set._

---

### 2. Why did they collect it?

Airbnb collects data to analyze their user needs, adapt to and expand user market, and increase company profits.

Inside Airbnb collects data to help people research Airbnb issues and their impact on cities in all aspects and provide data support for relevant map-making and visualization.

---

### 3. How was it collected?

_Airbnb collects data by processing forms that users fill out, held in Hadoop Distributed File System clusters as Hive-managed tables.

For Inside Airbnb, the website is served by an Amazon S3 "bucket". Data scientists use python to crawl for information from the relevant website. And they use the following Open Source technologies:- D3, Crossfilter, dc.js, Leaflet, Bootstrap, jQuery, Select2, Python, PostgreSQL, and Google Fonts[1] to improve or recollect the data through user feedback._

---

### 4. What useful information does it contain?


_It includes the following useful information, 'id', 'listing_url', 'scrape_id', 'last_scraped', 'name', 'description', 'neighborhood_overview', 'picture_url', 'host_id', 'host_url', 'host_name', 'host_since', 'host_location', 'host_about', 'host_response_time', 'host_response_rate', 'host_acceptance_rate', 'host_is_superhost', 'host_thumbnail_url', 'host_picture_url', 'host_neighbourhood', 'host_listings_count', 'host_total_listings_count', 'host_verifications', 'host_has_profile_pic', 'host_identity_verified', 'neighbourhood', 'neighbourhood_cleansed', , 'latitude', 'longitude', 'property_type', 'room_type', 'accommodates', , 'bathrooms_text', 'bedrooms', 'beds', 'amenities', 'price', 'minimum_nights', 'maximum_nights', 'minimum_minimum_nights', 'maximum_minimum_nights', 'minimum_maximum_nights', 'maximum_maximum_nights', 'minimum_nights_avg_ntm', 'maximum_nights_avg_ntm', , 'has_availability', 'availability_30', 'availability_60', 'availability_90', 'availability_365', 'calendar_last_scraped', 'number_of_reviews', 'number_of_reviews_ltm', 'number_of_reviews_l30d', 'first_review', 'last_review', 'review_scores_rating', 'review_scores_accuracy', 'review_scores_cleanliness', 'review_scores_checkin', 'review_scores_communication', 'review_scores_location', 'review_scores_value', , 'instant_bookable', 'calculated_host_listings_count', 'calculated_host_listings_count_entire_homes', 'calculated_host_listings_count_private_rooms', 'calculated_host_listings_count_shared_rooms', 'reviews_per_month'_

---

### 5. What useful information is it missing?

_It misses the following information, host gender, the host's age, host language, room size, room style, the house age, house rules, transit, access, and customer information. And some columns in the existing dataset are examined for missing most of the data. They are 'neighbourhood_group_cleansed', 'bathrooms', 'calendar_updated', and 'license'._

---

### 6. To what extent is the data 'complete'?

_The data is partly complete. According to the description object, the author classifies 74 columns in this data into five categories. Among them, there are 22 columns about the host, it's 29.73%, 13 cues about the housing conditions and surrounding environment, it's 17.57%, 27 columns about the housing rental situation, it's 36.49%, and 8 columns about the housing use evaluation, it's 10.81%, 4 columns for order fetching information, it's 5.41%.

The integrity lies in providing a relatively complete description of the necessary information, owner information, use evaluation, house and neighborhood information, and house rental status. 

The incompleteness is that, first of all, it targets a specific place at a particular time, Airbnb rental information in London on August 24th. Secondly, there is a fundamental lack of knowledge about renters. Third, there is also the phenomenon of crawling empty for existing information._

---

### 7. What kinds of analysis would this support?

_When it comes to the London area, we can analyze the host, the housing conditions and surrounding environment, housing rental situation, and the housing use evaluation. These four aspects are divided before and their mutual influence. 
 
To be more concise, it can support single field analysis, such as the distribution of Airbnb rentals in London and the characteristics of hosts of Airbnb in London. It can also support correlation analysis between different categories. For example, we can analyze the relationship between usage evaluation and host information, " what characteristics the owner's house usage evaluation rate is high". And we can also research usage evaluation and house and neighborhood information, such as what sort of neighborhood environment gain compliments. It also contributes to dig out the use evaluation and pre-rental housing situation, such as whether a better-rated house is likely to be booked._

---

### 8. What kinds of analysis would it _not_ support?

_Firstly, because the data set sample is limited to London, we cannot analyze areas outside London.

Secondly, due to the lack of information related to the rental guests, it is impossible to carry out a relevant analysis. It can also not investigate host gender, the host's age, host language, room size, room style, the house age, house rules, the transit around the house, and the access to the house. 

Third, due to missing information in some parts of the existing data set, some of the analysis supported initially in the data set is also invalid._

---

### 9. Which of the uses presented in Q.7 and Q.8 are _ethical_?

_Discussing ethical issues in data processing from four aspects, which were assessing voices, consent, privacy, and anonymity[2], the author concludes that the analyses on the relationship between the housing use evaluation and the host information or the housing conditions and surrounding environment are ethical. 
	
First, accessing voices means collecting votes from each party, especially those quickly glossed over. We will develop the analyses above based on the opinion and view covering host and customers. The host provides the host information as well as the house conditions and surrounding information. And the housing use evaluation is a collection of customers' voices. Hence, it is a fruitful approach to avoiding drowning out the customer's voice during the transaction.

Second, in terms of consent, one crucial cornerstone of ethical principles in social research is to ensure that any participants in the study have given their fully informed consent[3] [4] [5][6]. Each of the individuals providing the analysis voluntarily filled out the web form and was informed that the information would be made public[7], thus complying with this ethical principle.

Third, for privacy and anonymity. Individuals have rights to choose which of their activities and facts are shared with others[8]. During Airbnb's public rental process, hosts and customers have signed privacy protection statements, and other data will not be made available or anonymous except voluntarily [7]. Moreover, when data collected in the data set, it is tough for analysts to match the data information for specific people, so data providers' privacy is better protected.

However, these ethical considerations are not merely related to data collection but are located throughout the research writing and publication process[2]. Therefore, whether the above analysis conforms to moral principles needs to be further discussed after completing the full examination to assess their ethical issues concerning interpretation, ownership, and authorship._

---

### Appendix
### References

_[1]	I. Airbnb, “Behind Inside Airbnb,” 2020. http://insideairbnb.com/behind.html.
[2]	J. Sixsmith and C. D. Murray, “Ethical Issues in the Documentary Data Analysis of Internet Posts and Archives,” Qual. Health Res., vol. 11, no. 3, pp. 423–432, 2001.
[3]	A. P. Association, “Ethical principles of psychologists and code of conduct.,” 2017. http://www.apa.org/ethics/code.html.
[4]	B. P. Society, “Ethical principles,” Psychologist, pp. 6,33-35, 1993.
[5]	B. S. Association, “BSA statement of ethical practice,” 1993. http://www.britsoc.org.uk/ethgu2.htm.
[6]	O. H. Association, “Oral history evaluation guidelines,” 1996. http://http//:www.baylor.edu/~OHA/EvaluationGuidelines.html%23OralHistoryEvaluationGuidelines.
[7]	Airbnb, “Privacy Policy,” 2020. https://www.airbnb.co.uk/help/article/2855/privacy-policy?_set_bev_on_new_domain=1606105007_ZjU4ZWI3MDk3ZWNi.
[8]	J. S. Saltz and N. Dewar, “Data science ethical considerations: a systematic literature review and proposed project framework,” Ethics Inf. Technol., vol. 21, no. 3, pp. 197–208, 2019, doi: 10.1007/s10676-019-09502-5._

 
