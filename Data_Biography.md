# Data Biography

### Declaration of Authorship

I, [Anbing Ma], confirm that the work presented in this assessment is my own. Where information has been derived from other sources, I confirm that this has been indicated in the work.

[Anbing Ma]

Date of signature: 
Assessment due date:26/11/2021 
Student Number: 20041465

_Please write your answer immediately below the level-3 headers and delete the guidance prior to submission._

---

### 1. Who collected the data?

    This Airbnb listing data is initally scrapped and provided by the online provider Inside Airbnb. The researchers who want to do some research on Airbnb or the sharing economy can download this data from that website.

---

### 2. Why did they collect it?

    Because they may want to do the research which is related to Airbnb by using this London Airbnb listing data. For instance, the Airbnb listing data could be used to evaluate the influence of Airbnb listings’ descriptions on demand. In this study, the authors used the LDA model to perform topic modelling on the listing descriptions[1].

---

### 3. How was it collected?

    The data was scraped from the Airbnb website on 24 August 2020. This means that all data is listing information as it displayed on the Airbnb platform at that moment in time. The web data scraping process is divided into five steps:

   1.Identify the target website.
    
   2.Collect URLs of the pages where you want to extract data from.
    
   3.Make a request to these URLs to get the HTML of the page.
    
   4.Use locators to find the data in the HTML.
    
   5.Save the data in a JSON or CSV file or some other structured format.


---

### 4. What useful information does it contain?

    What useful information this data contains depends on what kinds of analysis that researchers want to do. If someone wants to do the same research as what I mentioned in Q.2, they can analyze the description data contained in this Airbnb data to gain similar conclusions about London. In this case, the description is useful information. In addition, let’s take another article titled “An empirical analysis of Airbnb listings in forty American cities” as an example. In this article, the authors used the multilevel mixed-effect linear regression model to analyze the factors affecting the average price per night per person of the Airbnb listing[2], and the variables in the model include the locations of houses, the number of beds, the number of online pictures, the number of online reviews, star rating, etc., which are regarded as useful information and all contained in our Airbnb data.

---

### 5. To what extent is the data 'complete'?

    No data is 100% complete. The limitation is an inherent property of data because the storage space for data, like paper, disk, CD, even cloud space, is limited, but this world, which produces data constantly, is infinite. In other words, it is impossible to find a piece of data without any limitation. 
    
    For the data studied here, firstly, it has time limitations. This data was scraped from the Airbnb website on 24 August 2020, which means that all data is listing information as it displayed on the Airbnb platform at that moment in time. However, this data can only show one day’s information of Airbnb listings on the website. If someone decided to become a host to share his or her home with other people and posted his or her house’s information on the Airbnb website on 25 August 2020, then this data which was scrapped on 24 August 2020 would lose its accuracy. In other words, this data became incomplete. However, the analyses which are supported by this Airbnb listing data are not very sensitive to the daily changes in data, so in the short period centred on 24 August 2020, this data can be described as ‘complete data’, which can support the analyses about Airbnb.

    Secondly, it has spatial limitations. This data only contains London’s Airbnb listings, then it only supports the analyses on the scale of London and any results and conclusions from those analyses can only apply for London but other cities. In all, this data can be described as ‘complete data’ when the study area is London.
    
    Thirdly, in this Airbnb listing data, some values of listings' properties are blank and these listings may be excluded when this data is used to do some research which may make this data sample uncomplete. 


---

### 6. What kinds of analysis would this support?

After reviewing the literature, I come up with 5 kinds of analysis that can be supported by this Airbnb data.
    
   1.Some research on Airbnb focused on the determinants of guests’ decision making and their impact on demand. For example, Janssens, Bogaert and Poel evaluated the influence of Airbnb listings’ descriptions on demand[1]. Pooja Sengupta et al. examined the predictors of successful Airbnb bookings with Hurdle models[3]. 
    
   2.Some research focused on the impact of sharing economy. For instance, Minhong Xu and Yilan Xu explored the impact of home-sharing (e.g. Airbnb) on neighbourhood investment[4].
    
   3.Some research focused on the hosts of Airbnb listings and want to explore whether the professional hosts who own better pricing strategies yield higher returns. Georges Casamatta et al. tested whether professional hosts indeed have a better perception of the degree of market power than non-professionals[5].
    
   4.Some research focused on the price of Airbnb listings. Augusto Volotes- Dorta and Agustín Sánchez-Medina presented a study about the drivers of Airbnb prices in Bristol using ordinary least squares (OLS) and geographically weighted regression (GWR) methods[6].
    
   5.Some research used GIS to map out the distribution of Airbnb listings and hotels. Gutierrez et al. concluded that not only Airbnb have different spatial patterns from traditional hotels, but the explanatory factors to the location of Airbnb listings were also different from those for traditional hotels[7].


---

### 7. Which of the uses presented in Q.6 are _ethical_?

    The biggest ethical crisis of this era of information is the issue of personal privacy.

    Firstly, there is the ethical issue of data collection. Whereas in the past, data collection was done manually, and the person being collected was usually informed, but today, data is collected automatically by intelligent devices, often without the knowledge of the person being collected. 

    Secondly, there is the issue of privacy in the use of data. Now the volume of data grows constantly and the ways in which data can be combined to reveal more data are constantly evolving too[8]. This combination of multiple data may reveal some private information without the person’s knowledge, which is described as the “aggregation effect”[9].

    Analyzing the studies listed in Q.6 from two perspectives of ethical issues mentioned above, I found that the data and analyses in these studies only involved just a little private information about the hosts, for example, the hosts’ first names, the hosts’ self-introductions and the hosts’ locations, and basically did not involve private information about the Airbnb users. Although some studies that explore the behavioural habits and preferences of Airbnb users may inadvertently involve some personal privacy, I think, from the perspective of personal privacy, the studies mentioned in Q.6 are all ethical.



## Bibliography

[1]	B. Janssens, M. Bogaert, and D. Van den Poel, ‘Evaluating the influence of Airbnb listings’ descriptions on demand’, Int. J. Hosp. Manag., vol. 99, p. 103071, Oct. 2021.

[2]	J. Jiao and S. Bai, ‘An empirical analysis of Airbnb listings in forty American cities’, Cities, vol. 99, p. 102618, Apr. 2020.

[3]	P. Sengupta, B. Biswas, A. Kumar, R. Shankar, and S. Gupta, ‘Examining the predictors of successful Airbnb bookings with Hurdle models: Evidence from Europe, Australia, USA and Asia-Pacific cities’, J. Bus. Res., vol. 137, pp. 538–554, Dec. 2021.

[4]	M. Xu and Y. Xu, ‘What happens when Airbnb comes to the neighborhood: The impact of home-sharing on neighborhood investment’, Reg. Sci. Urban Econ., vol. 88, p. 103670, May 2021.

[5]	G. Casamatta, S. Giannoni, D. Brunstein, and J. Jouve, ‘Host type and pricing on Airbnb: Seasonality and perceived market power’, Tour. Manag., vol. 88, p. 104433, Feb. 2022.

[6]	A. Voltes-Dorta and A. Sánchez-Medina, ‘Drivers of Airbnb prices according to property/room type, season and location: A regression approach’, J. Hosp. Tour. Manag., vol. 45, pp. 266–275, Dec. 2020.

[7]	J. Gutiérrez, J. C. García-Palomares, G. Romanillos, and M. H. Salas-Olmedo, ‘The eruption of Airbnb in tourist cities: Comparing spatial patterns of hotels and peer-to-peer accommodation in Barcelona’, Tour. Manag., vol. 62, pp. 278–291, Oct. 2017.

[8]	K. Crawford and M. Finn, ‘The limits of crisis data: analytical and ethical challenges of using social and mobile data to understand disasters’, GeoJournal, vol. 80, no. 4, pp. 491–502, Aug. 2015.

[9]	D. J. Solove, ‘Privacy Self-Management and the Consent Dilemma’, Social Science Research Network, Rochester, NY, SSRN Scholarly Paper ID 2171018, Nov. 2012. Accessed: Nov. 21, 2021. [Online]. Available: https://papers.ssrn.com/abstract=2171018


## Appendix 

