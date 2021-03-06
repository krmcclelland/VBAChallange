# VBA Challange
   
## Overview:
The client is interested in investing in green stocks and has been monitoring the stock market for a stock called DQ but needs to analyze other green stocks for the past two years to ensure it is the best stock for their investment dollars.  The client provided a list of twelve (12) stocks to review captured on a spreadsheet.  To continue our evaluation, we also need to refactor or index the code to speed up the code's run time.

## Analysis Results: 
There was a significant contrast between 2017 over 2018.  By far, 2017 was a better year for these green stocks.  DQ showed positive returns of 199.4% in 2017, wherein 2018 had negative returns of (62.6%), and with a swing of (262%) it would not be the best investment for a conservative investor.  Their performance in 2017 are as follows:

![2017_All_Stocks_Spreadsheet](https://user-images.githubusercontent.com/17502725/140571181-86fb928b-ebe6-48f1-ae84-1e3ab6978dab.PNG) ![2018_All_Stock_Spreadsheet](https://user-images.githubusercontent.com/17502725/140571220-174df1b8-d7b3-47a6-abad-707955ac7592.PNG)










### Pros & Cons on When to Use Refactoring 
Refactoring Code should not be used all the time.  Refactoring should not be used if you are up against a deadline.  Refactoring is good to use when restructuring internal code without altering the external behavior.^[1]   

Pros | Cons 
|:--------------:|:-----------------:|
Product enhancements adding new features and functions.  | Tight schedules, delivery deadlines are to close, or product enhancements are being planned.| 
Finding bad or sluggish functionality, eliminate duplicate code, reducing run time, or reorganizing code. | Expensive and risky.  Cost of code rewrite from the foundation.|
Bug fixing -Root cause of bugs; smell test. | Short on the amount of time testing will be done causing a bad ender user experience.|
Peer review – Identify areas of coding improvement. | Waiting to long to recode can cause a bigger mess. |
Stable code should not be refactored | Potential of adding bugs to the code. |
Refactoring improves design, improves code and maintainability. | Lack of management support. |

Refactoring the code, has decreased the time it takes to run the code.  To use the VBA code to analyze future investments, we have refactored or indexed the code to reduce the time it takes to analyze investment to react faster to investment opportunities. In addition, we inserted code to monitor the time it takes to run the code below shows the before and after the code is indexed.  The run time figures below on the left are before the indexing, and the right is after the indexing. 


### Indexing Code Before & After Improves Run Time
                Before Indexing                         After Indexing

![2017_Code_Run_Time](https://user-images.githubusercontent.com/17502725/140571307-9c59189e-5884-47f2-95be-8296a652a609.PNG) ![B_2017_Code_Run_Time](https://user-images.githubusercontent.com/17502725/140571325-6e29340f-9778-49ce-a0b3-0d9331f8b801.PNG)


![A_2018_Code_Run_Time](https://user-images.githubusercontent.com/17502725/140571354-579090e0-d612-4184-a000-84e2ab7f4747.PNG) ![B_2018_Code_Run_Time](https://user-images.githubusercontent.com/17502725/140571383-208554d3-f10b-4563-8965-2c22634cf5f4.PNG)

## Conclusion:
Refactoring has streamlined the code with and the run time without effecting the external functionality making it easier to evaluate the potential green investments.  In preforming the analysis, it is concluded ENPH and RUN produced better returns than DQ for a conservative investor and should be considered as future investment opportunities. The code can be used to run analysis in the future and on additional stock.   

### Footer
^[1] https://www.c-sharpcorner.com/article/pros-and-cons-of-code-refactoring/#:~:text=Code%20Refactoring%20is%20an%20important%20exercise%20to%20remove,the%20development%20and%20is%20prone%20to%20more%20defects.
