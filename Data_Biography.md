# Data Biography

### Declaration of Authorship

I, [Anbing Ma], confirm that the work presented in this assessment is my own. Where information has been derived from other sources, I confirm that this has been indicated in the work.

[Anbing Ma]

Date of signature: 25/11/2021

Assessment due date:26/11/2021

Student Number: 20041465

_Please write your answer immediately below the level-3 headers and delete the guidance prior to submission._

---

### 1. Who collected the data?

This Airbnb listing data is initially collected and organized by the online provider Inside Airbnb and the researchers who are interested in Airbnb could download this data from that website. 

---

### 2. Why did they collect it?

Because they may want to study some fundamental questions about Airbnb in any neighbourhood, or across the city as a whole. For example, Janssens, Bogaert and Poel used the LDA model to perform topic modelling on the listing descriptions[1].

---

### 3. How was it collected?

The data was scraped from the Airbnb website on 24 August 2020. The web data scraping process is divided into five steps:

**1.** Identify the target website.

**2.** Collect URLs of the pages where you want to extract data from.

**3.** Make a request to these URLs to get the HTML of the page.

**4.** Use locators to find the data in the HTML.

**5.** Save the data in a JSON or CSV file or some other structured format.

---

### 4. What useful information does it contain?

What useful information this data contains depends on what kinds of analysis that researchers want to do. If someone wants to analyze the description data contained in this Airbnb data to gain similar conclusions about London, in this case, the descriptions of listings are useful information. In addition, let’s take another article titled “An empirical analysis of Airbnb listings in forty American cities” as an example. In this article, the authors used the linear regression model to analyze the factors affecting the average price of the Airbnb listing[2], and the variables in the model include the locations of houses, the number of beds, online pictures, online reviews, star rating, etc. These variables (useful information) are all contained in this data.

---

### 5. To what extent is the data 'complete'?

There are over 50 fields in this data that almost contain every aspect of information of Airbnb listings. However, this data is not as complete as it looks like, because different kinds of discrimination have always existed in Airbnb data and are often ignored by people.

Firstly, the age discrimination. Not everyone is good at using smart devices and not everyone uses Airbnb. Nowadays, almost all young people own at least one smart device and there is no doubt that young people are the main consumers of Airbnb, so a huge amount of Airbnb resources are going to them. For example, the hosts prefer to decorate their apartments with fashion styles or dress up themselves more youthfully to attract young consumers, and the hosts may also pay more attention to reviews from young consumers. In all, this kind of discrimination makes the Airbnb data more relevant to young people and makes this data incomplete. 

Secondly, racial discrimination. The Airbnb users believe that they have the right to choose "who comes into their home" and "whose home they enter". Although Airbnb launched an anti-discrimination directive to users, it is impossible to intervene in every user’s choice. As such discrimination is inevitable, the data will naturally be affected. As a result, this data will be more relevant to users who don’t suffer from racial discrimination and tend to ignore discriminated users. In other words, this data is incomplete.

---

### 6. What kinds of analysis would this support?

After reviewing the literature, I come up with 5 kinds of analysis that can be supported by this Airbnb data.

**1.** Some research on Airbnb focused on the determinants of guests’ decision making and their impact on demand. For example, Janssens, Bogaert and Poel evaluated the influence of Airbnb listings’ descriptions on demand[1]. Pooja Sengupta et al. examined the predictors of successful Airbnb bookings with Hurdle models[3]. 

**2.** Some research focused on the impact of sharing economy. For instance, Minhong Xu and Yilan Xu explored the impact of home-sharing (e.g. Airbnb) on neighbourhood investment[4].

**3.** Some research focused on the hosts of Airbnb listings and want to explore whether the professional hosts who own better pricing strategies yield higher returns. Georges Casamatta et al. tested whether professional hosts indeed have a better perception of the degree of market power than non-professionals[5].

**4.** Some research focused on the price of Airbnb listings. Augusto Volotes- Dorta and Agustín Sánchez-Medina presented a study about the drivers of Airbnb prices in Bristol using ordinary least squares (OLS) and geographically weighted regression (GWR) methods[6].

**5.** Some research used GIS to map out the distribution of Airbnb listings and hotels. Gutierrez et al. concluded that not only Airbnb have different spatial patterns from traditional hotels, but the explanatory factors to the location of Airbnb listings were also different from those for traditional hotels[7].

---

### 7. Which of the uses presented in Q.6 are _ethical_?

Personal privacy is always the biggest ethical issue in any field. Whereas in the past, data collection was done manually, and the person being collected was usually informed, but today, data is collected automatically by intelligent devices, often without the knowledge of the person being collected. What’s more, the volume of data grows constantly and the ways in which data can be combined to reveal more data are constantly evolving too[8]. This combination of multiple data may reveal some private information without the person’s knowledge, which is described as the “aggregation effect”[9]. Regarding the studies mentioned in Q.6, I found that the data and analyses in these studies only involved just a little private information about Airbnb listings’ hosts, for example, the hosts’ first names, the hosts’ self-introductions and the hosts’ locations, and basically did not involve private information about the Airbnb users. Although some studies that explore the behavioural habits and preferences of Airbnb users may inadvertently involve some personal privacy, I think, from the perspective of personal privacy, the studies mentioned in Q.6 are basically ethical.

However, what can’t be ignored is that there is digital discrimination in Airbnb data. The term digital discrimination is used to define a range of circumstances in which a person or group is treated less favourably than another person or group based on their background and/or certain personal characteristics with regards to the Internet[10]. Today, young people are obviously better at using smart devices, so Airbnb users’ groups mainly include teenagers and middle-aged people, barely including elderly people. Then, inevitably, all Airbnb data and the analyses supported by it would have the problem of digital discrimination because only the data from Airbnb users can be collected and those who never use Airbnb would be ignored by the studies and research. From this perspective, although Airbnb’s digital discrimination is inevitable, technically, all studies supported by Airbnb data are not ethical.

---

## Bibliography

[1]	B. Janssens, M. Bogaert, and D. Van den Poel, ‘Evaluating the influence of Airbnb listings’ descriptions on demand’, Int. J. Hosp. Manag., vol. 99, p. 103071, Oct. 2021.https://doi.org/10.1016/j.ijhm.2021.103071.

[2]	J. Jiao and S. Bai, ‘An empirical analysis of Airbnb listings in forty American cities’, Cities, vol. 99, p. 102618, Apr. 2020.https://doi.org/10.1016/j.cities.2020.102618.

[3]	P. Sengupta, B. Biswas, A. Kumar, R. Shankar, and S. Gupta, ‘Examining the predictors of successful Airbnb bookings with Hurdle models: Evidence from Europe, Australia, USA and Asia-Pacific cities’, J. Bus. Res., vol. 137, pp. 538–554, Dec. 2021.https://doi.org/10.1016/j.jbusres.2021.08.035.

[4]	M. Xu and Y. Xu, ‘What happens when Airbnb comes to the neighborhood: The impact of home-sharing on neighborhood investment’, Reg. Sci. Urban Econ., vol. 88, p. 103670, May 2021.https://doi.org/10.1016/j.regsciurbeco.2021.103670.

[5]	G. Casamatta, S. Giannoni, D. Brunstein, and J. Jouve, ‘Host type and pricing on Airbnb: Seasonality and perceived market power’, Tour. Manag., vol. 88, p. 104433, Feb. 2022. https://doi.org/10.1016/j.tourman.2021.104433.

[6]	A. Voltes-Dorta and A. Sánchez-Medina, ‘Drivers of Airbnb prices according to property/room type, season and location: A regression approach’, J. Hosp. Tour. Manag., vol. 45, pp. 266–275, Dec. 2020. https://doi.org/10.1016/j.jhtm.2020.08.015.

[7]	J. Gutiérrez, J. C. García-Palomares, G. Romanillos, and M. H. Salas-Olmedo, ‘The eruption of Airbnb in tourist cities: Comparing spatial patterns of hotels and peer-to-peer accommodation in Barcelona’, Tour. Manag., vol. 62, pp. 278–291, Oct. 2017. https://doi.org/10.1016/j.tourman.2017.05.003.

[8]	K. Crawford and M. Finn, ‘The limits of crisis data: analytical and ethical challenges of using social and mobile data to understand disasters’, GeoJournal, vol. 80, no. 4, pp. 491–502, Aug. 2015. https://doi.org/10.1007/s10708-014-9597-z.

[9]	D. J. Solove, ‘Privacy Self-Management and the Consent Dilemma’, Social Science Research Network, Rochester, NY, SSRN Scholarly Paper ID 2171018, Nov. 2012. Accessed: Nov. 21, 2021. [Online]. Available: https://papers.ssrn.com/abstract=2171018.

[10] M. Cheng and C. Foley, ‘The sharing economy and digital discrimination: The case of Airbnb’, Int. J. Hosp. Manag., vol. 70, pp. 95–98, Mar. 2018. https://doi.org/10.1016/j.ijhm.2017.11.002.

---

## Appendix

None