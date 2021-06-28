# Module-2-Challenge
## Overveiew of Project
The purpose of this project was to implement the VBA skills we learned to refactor code to find total volumes and returns in 2017 and 2018 for a numnber of different stocks from a long list of values

## Results
Our analysis showed how our stocks differed in 2017 and 2018. Returns for all but one stock were positive. In 2018 however, our same stocks performed much worse. Where every stock except for two had negative returns.

The execution times were also significantly reduced after refactoring the code. The attached images show the updated times it took to pull the results for each year.

[2017]("C:\Users\jvanv\OneDrive\Desktop\Classwork Folder\Green Stock Data\Resources\VBA_Challenge_2017.png")

[2018]("C:\Users\jvanv\OneDrive\Desktop\Classwork Folder\Green Stock Data\Resources\VBA_Challenge_2018.png")

I would like to point out two key For loops in the refactored code that allowed for our results to efficiently run. The attached screenshot below shows this code.

- The first For loop (with variable "j") runs through each line in the data for a given ticker and pulls the starting and ending prices based on if the tickers above and below don't match the current ticker.
- The second For loop (with variable "i") is where we designate where our ouputs for each ticker, volume and percent return will be shown (in this case, in our "All Stocks Analysis" sheet)

[For Loops code]("C:\Users\jvanv\OneDrive\Desktop\Classwork Folder\Green Stock Data\Resources\For Loops Code.png")

## Summary
1. There are advantages and disadvanteges of refactoring code. The two main advantages are that it allows your system to run much quicker and it makes the report dynamic. A disadvantage to refactoring code is that it requires more time a level of understanding to build and troubleshoot that most individuals don't understand.
2. The pros and cons listed above apply to this report. The code allows for this research to be dynamic in the sense we can pull this same data in future years if our data is stored like it was for 2017 and 2018. However, if our client experiences an error in the future, they likely will not be able to make a quick change.
