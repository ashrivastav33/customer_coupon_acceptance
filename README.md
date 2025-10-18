# customer_coupon_acceptance
This project is to demonstrate will customer accept coupon using pandas, visualization libraries, statistical functions

## How to get started
In order to get this project running please download the code using the git clone command

  - 'git clone https://github.com/ashrivastav33/customer_coupon_acceptance.git'

## Note
- We are making an assumption you already are familiar with using Jupyter Notebook using tools like Google Colab or Jupyter etc.
- You will need an internet connection to download/read the dataset or csv file

## Project Structure

### - /data/coupons.csv    ---> Stores the dataset used for this project
### - /code/coupon_acceptance_rate_ashri33.ipynb            ---> Stores the code/jupyter notebook used for this project

## Results

### Conclusion Bar coupon

 - Bar coupon acceptance rate is ~41% across ~2,017 entries.
 - Acceptance is consistent across demographics (age, income, marital status, education)
 - Frequent bar visitors (>3 times) show much higher acceptance (~76%).
 - Drivers over 25 who visit bars monthly have a ~69% acceptance rate.
 - Those who visit bars monthly, have no kid passengers, and are not in farming-related jobs have a ~62% rate.
 - Younger drivers (<30) who visit bars monthly show the highest acceptance (~72%).
 - Single/unmarried individuals accept more coupons; widowed drivers accept the least (0%).
 - Female drivers around 6 PM are more likely to accept.
 - High school students are most receptive, followed by those with graduate and bachelor’s degrees.

### Conclusion for Coffee House coupon 

 - Highest acceptance times are around 2 PM ~66%, followed by 10 AM ~62% and 6 PM ~55% — these times people are either going to office or coming from office
 - Overall coffee coupon acceptance rate is approximately 50%.
 - Customers with no urgent destination have the highest acceptance rate (55%), followed by those heading to work (44%), and home (~38%).
 - Widowed individuals show a higher acceptance rate for coffee coupons.
 - People with degrees tend to accept coupons less often.
 - Divorced individuals are less likely to accept coffee coupons.


## Conclusion

### Learning

- It was fun to work on this assignment, I did learn so many ways to explore data initially I was trying to create conditions and then conmbining conditions with this assignment I was able to start using .query() method which was much efficient
- We can state that coupon acceptance does depend on lots of factors e.g time of the day, customer visiting that place often or not, having kids as passenger, I have just scratched the surface the possibitlities with these sample data are so many.

## Next Steps and Recommendations

 - We can explore more scenarios to learn meaningful insights from the data
 - The recommendation is that customer who visit bar more often have higher acceptance rate
 - We need to target some very specific demographic questions to get meaningful insights
