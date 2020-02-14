# Comparing Baltimore and Fairfax Household Income and Graduation Rates
### The goal of this project was to use 'Opportunity Atlas' data in order to compare household income and graduation rates as aggregated by race in Fairfax and Baltimore areas. In doing so, the project found large income disparities for households of different racial groups in both areas, disparities which translated into lower graduation rates for poor families (which were usually from black or brown racial demographics.)
## *Fairfax County Data*
- 1) High school graduation rates in Fairfax are consistently quite high, with a low outlier being at 75.3% in Manassas Park City, VA, and a the highest in Fairfax at 92.74%
- 2) Although data by total household income had many hundreds of data points, data aggregated by race was only performed in 15 districts based on Opportunity Atlas. Using average income from total Fairfax household data, we can find the top 20th percentile of incomes (at $63,297.2) and bottom 20th percentile ($35,360.2)
- 3) From there, we see that black households rank consistently lower in incomes, followed by hispanic, asian and finally white households, who hold the highest incomes. The chart below shows us that black households make up the entirety of the bottom 20th percentile share of incomes, with 53.3% of black households falling into this percentile. On the other hand, white households make up 40% of the top 20th percentile, and the rest fall into middle class percentiles. All Hispanic households fall in the middle 60th percentile, as do most Asian families, with 20% falling into the top 20th percentile of Fairfax incomes. 

<img width="490" alt="Screen Shot 2020-02-14 at 11 03 17" src="https://user-images.githubusercontent.com/60707160/74547165-b0f75f80-4f19-11ea-9cb9-d751a3e57293.png">
 <img width="293" alt="Screen Shot 2020-02-14 at 11 03 33" src="https://user-images.githubusercontent.com/60707160/74547147-ac32ab80-4f19-11ea-9b65-0db90bd5bc41.png">
 <img width="387" alt="Screen Shot 2020-02-14 at 11 03 02" src="https://user-images.githubusercontent.com/60707160/74547174-b359b980-4f19-11ea-9a00-a6da066ac32c.png">
 
**What we can conclude: Even though high school graduation rates are high in Fairfax County, there is a major disparity in household incomes when we factor in for race. This can lead us to wonder if total graduation rates are skewed towards wealthier (and as shown by the data, whiter) families, and if post-graduation options are limited for poorer families. Moreover, it begs the question of development in the area, and if the gentrification that negatively affected black and brown families in DC, may have had a spill-over effect into surrounding counties such as Fairfax, causing further income inequality.**
 
## *Baltimore Data*
- 1) In Baltimore, some of the speculations made about Fairfax County disparities are even starker. The chart below shows that more than half of black Baltimorean families fall in the bottom 20th percentile of total average Baltimore income (they make under $22735.8). Almost all remaining black families fall into the middle 60th percentile. For white families however, over 45% fall in the top 20th percentile of Baltimore income ($47771.4), while 36% still fall in the bottom 20th percentile of incomes. (It is important to note that data was only widely available for white and black families.) 
- 2) We can compare this data with five counties in and around Baltimore on the “Graduation Rates Baltimore” sheet. In each county, we see high high school graduation rates, but we notice a slight disparity in terms of class. Bottom 20th income percentile rates are in the 70-80% graduation ranges for each region, but top 80th income percentile high school graduation rates are in the 90% range.
<img width="402" alt="Screen Shot 2020-02-14 at 11 02 47" src="https://user-images.githubusercontent.com/60707160/74547176-b5bc1380-4f19-11ea-881e-17ba82831ecb.png">
<img width="476" alt="Screen Shot 2020-02-14 at 11 02 31" src="https://user-images.githubusercontent.com/60707160/74547184-b81e6d80-4f19-11ea-8cd6-f784a755b774.png">

**What we can conclude: This data breakdown is important as it shows us that simply looking at graduation rates is not a full picture. When noticing the income disparity by race, and then seeing that lower income families also have lower high school graduation rates, we begin to see how black families in Baltimore are dually disenfranchised. Since they make up the largest portion of bottom 20th percentile incomes, and this is precisely the income bracket that has the lowest graduation rates in Baltimore, it is clear that black families are more exposed to the risks of not completing high school, and thus, a higher chance of perpetuating a cycle of poverty due to a reduced employability.** 

## Excel Data
[Baltimore and Fairfax-Mini Project #1 Malika Dia .xlsx](https://github.com/mdia4/comparing-baltimore-and-fairfax-household-income-and-graduation-rates/files/4205458/Baltimore.and.Fairfax-Mini.Project.1.Malika.Dia.xlsx)
### Methods Used
1) VLOOK-UP
- Used to match tract number with racially aggregated data on sheets “Baltimore Household Percentiles”
- Used to match graduation rates and cty county number in table on sheet “Fairfax Household Graduation)
2) Nested If Statement
- Used to rank “top” “middle” and “bottom” income ranges on all sheets
3) Pivot Table
- Used to organize data on sheet “Graduation Rates Baltimore” and form a pivot chart seperated by county, race and income
4) Total of 4 Charts, one of which has a secondary axis and is mixed format (line and bar)
- Used on “Household-Graduation” sheet to show income and graduation rates on the same graph, despite differing scales.
5) Following Calculation Statements (=average, =percentile.exc, =countifs (with an exclusion), arithmetic)

## Opportunity Atlas Data

[Balitmore Houshold Data All.xlsx](https://github.com/mdia4/comparing-baltimore-and-fairfax-household-income-and-graduation-rates/files/4205718/Balitmore.Houshold.Data.All.xlsx)
[Baltimore Graduation Rates.xlsx](https://github.com/mdia4/comparing-baltimore-and-fairfax-household-income-and-graduation-rates/files/4205719/Baltimore.Graduation.Rates.xlsx)
[Baltimore Housing Data Black.xlsx](https://github.com/mdia4/comparing-baltimore-and-fairfax-household-income-and-graduation-rates/files/4205720/Baltimore.Housing.Data.Black.xlsx)
[Baltimore Housing Data White.xlsx](https://github.com/mdia4/comparing-baltimore-and-fairfax-household-income-and-graduation-rates/files/4205721/Baltimore.Housing.Data.White.xlsx)
[Fairfax Graduation Rates.xlsx](https://github.com/mdia4/comparing-baltimore-and-fairfax-household-income-and-graduation-rates/files/4205722/Fairfax.Graduation.Rates.xlsx)
[Fairfax Household Data All.xlsx](https://github.com/mdia4/comparing-baltimore-and-fairfax-household-income-and-graduation-rates/files/4205724/Fairfax.Household.Data.All.xlsx)
[Fairfax Houshold Data Asian.xlsx](https://github.com/mdia4/comparing-baltimore-and-fairfax-household-income-and-graduation-rates/files/4205725/Fairfax.Houshold.Data.Asian.xlsx)
[Fairfax Housing Data Black.xlsx](https://github.com/mdia4/comparing-baltimore-and-fairfax-household-income-and-graduation-rates/files/4205726/Fairfax.Housing.Data.Black.xlsx)
[Fairfax Housing Data Hispanic.xlsx](https://github.com/mdia4/comparing-baltimore-and-fairfax-household-income-and-graduation-rates/files/4205727/Fairfax.Housing.Data.Hispanic.xlsx)

