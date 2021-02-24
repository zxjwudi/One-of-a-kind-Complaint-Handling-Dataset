# A-Dataset-of-Customer-Complaint-Handling-of-Restaurants


## Overview
This customer complaint dataset is collected from the high-class restaurant chains of two brands, which are named 'Shintori' and 'People' with four branch restaurants in Taipei City (two branches for each brand). 


### Highlights:
Catering service robot is widely applied to restaurants to replace the works of the restaurant staffs partially. Limited by the degree of intelligence, these robots in the market can only handle relatively simple services such as ordering dishes, obstacle avoidance and food delivery, etc. For some complex tasks, such as dealing with customer complaints, human services are still needed. In order to equip the catering service robot with the intelligence of customer complaint handling, in this paper, we conduct a dataset collection work from restaurant chains of two brands over four years. As a result, we collect a dataset containing thousands of complaint cases. These complaint cases involve the whole stages of dining service, specifically contain include complaint attributes, complaint description and complaint handling result, etc. This dataset bridges the lack of detailed industrial customer complaint handling data in the dining service of high-end restaurants, which is very valuable for the development of catering service robot. To our best knowledge, the rich dataset reported in this paper is the ﬁrst comprehensive study of customer complaint handling in an industrial service management context. In addition, this dataset may help lead to more realistic complaint handling theoretic and analytic studies and more effective knowledge approaches for complaint handling recommendation.

### Bibtex
If you find this dataset is helpful, please kindly consider citing the following papers:

```
@article{lee2015ontology,
  title={Ontology-based reasoning for the intelligent handling of customer complaints},
  author={Lee, Ching-Hung and Wang, Yu-Hui and Trappey, Amy JC},
  journal={Computers \& Industrial Engineering},
  volume={84},
  pages={144--155},
  year={2015},
  publisher={Elsevier}
}
```

## Columns of Customer Complaint Data


Column Name		Range	Description
R_Time		Time	Reporting time 
R_WKSTOR		{Banboo_1, Shadow_3, Waterfall_4, Spring_5}	Title and number of restaurants
Banboo_1 and Waterfall_4 are the branches of Shintori. 
Shadow_3 and Spring_5 are the branches of People. 
R_CusCDate		Date	Date of customer complaint 
R_CusCTime		Time	Time of customer compliant
R_CusCPlace		Open text 	Dining table or places of complaints delivered
R_CusCMemo		Open text	Content of customer complaint
R_CusCType		{1-food taste and food defection, 2-insufficient quantity, 3-abnormal object, 4-serving speed, 5-food corruption, 6-other food quality issue, 7-price exceed customers’ expectation, 8-personnel service, 9-environment sanitation, 10-facility, 11-customer emotional issue, 12-others.	Types of customer complaints selected when users key in complaints handling process on e-CCH. We merged the original 17 types in the system into 12 classification to avoid some categories with little data. 
Cus_type		{1-Spring; 2- Summer; 3- Autumn; 4- Winter}	Spring temperament - bloody factor; Summer temperament - bile factor; Autumn temperament - mucus factor; Winter temperament - depression factor. 
R_Handling		Open text	Content of customer complaint handling, mainly including nine attributes: 1-free food, 2-discount, 3- coupon, 4-replacement, 5-correction, 6-managerial apology, 7-staff apology, 8-listening and 9-others. (Lee et al., 2015) 
R_Result		{4-very unsatisfactory
3- possibly unsatisfactory
2-satisfactory
1- very satisfactory }	Results from customers’ attitude and feeling



### Acknowledgement
We thanks for the original data-sharing and support of Shintori restaurant. This research was partially supported by the Xi’an Jiaotong University [grant number 7121192301]. 


If you have any questions or concerns, please kindly email to [**Xuejiao Zhao**](xjzhao@ntu.edu.sg).
