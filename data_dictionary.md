# Feature Explaation :

* The dataset consists of 10 numerical and 8 categorical attributes. 
* The **'Revenue'** attribute can be used as the class label,i.e. revenue will be generated or not 
* These features represent the number of different types of pages visited by the visitor in that session and total time spent in each of these page categories.
    * **Administrative** - Administrative Value
    * **Administrative_Duration** - Duration in Administrative Page
    * **Informational** - Informational Value
    * **Informational_Duration** - Duration in Informational Page
    * **ProductRelated** - Product Related Value
    * **ProductRelated_Duration** - Duration in Product Related Page        
The values of these features are derived from the URL information of the pages visited by the user and updated in real time when a user takes an action, e.g. moving from one page to another. 
* These features represent the metrics measured by "Google Analytics" for each page in the e-commerce site. 
    * **BounceRates** - The value of this feature for a web page refers to the percentage of visitors who enter the site from that page and then leave ("bounce") without triggering any other requests to the analytics server during that session. 
    * **EXitRates** - The value of this feature for a specific web page is calculated as for all pageviews to the page, the percentage that were the last in the session. 
    * **Page Value** - This feature represents the average value for a web page that a user visited before completing an e-commerce transaction.
* **"Special Day"** - This feature indicates the closeness of the site visiting time to a specific special day (e.g. Mother’s Day, Valentine's Day) in which the sessions are more likely to be finalized with transaction. The value of this attribute is determined by considering the dynamics of e-commerce such as the duration between the order date and delivery date. For example, for Valentina’s day, this value takes a nonzero value between February 2 and February 12, zero before and after this date unless it is close to another special day, and its maximum value of 1 on February 8. 
* The dataset also includes :
    * **OperatingSystems** - Operating system used
    * **Browser** - browser used
    * **Region** - region of the user
    * **TrafficType** - type of traffic
    * **VisitorType** - types of visitor
        * Returning_Visitor
        * New_Visitor
    * **Weekend** - a Boolean value indicating whether the date of the visit is weekend or not
    * **Month** - month of the year.