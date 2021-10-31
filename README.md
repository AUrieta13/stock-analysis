# stock-analysis
# Written Analysis:Deliverable 2

For your written analysis, be sure to use complete and coherent sentences. Your written analysis should contain three sections, which cover the following:

## Overview of Project: Explain the purpose of this analysis.
 > The purpose of this analysis was to help Steve expand and display the dataset to include the entire stock market over the years 2017 and 2018. Our mission was to refactor our previous code that only had the ablitiy to run through one year at a time to now have the capablitity of pulling data for more than one year on the stock of interest! 

## Results: Using images and examples of your code, compare the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script.

### Use images and example of code:

> Creating the tickerIndex variable and three output arrays. 

   ![tickerIndex_and_arrays](https://user-images.githubusercontent.com/90146132/139595757-a20b2202-3d60-4c32-88c4-7c1a630c629c.PNG)

> Initializing tickervolumes to began at the vaule zero and creating a loop that will loop over all the row in the selected year value spreadsheet

   ![totalvolume_zero](https://user-images.githubusercontent.com/90146132/139595669-b81c9b30-7d0e-44e4-805e-804a6f09a1c5.PNG)
   ![loop_to_all_rows_spreadsheet](https://user-images.githubusercontent.com/90146132/139595682-863a4c54-369b-43f0-a332-70ca92ea3904.PNG)


> Aftering setting totalVolume to zero and creating loop through all rows, we assemble the first loop and create a script to obtain the current ticker's ticker volume and increase tickerIndex if the new row's ticker does not match the previous row's ticker.

   ![increasae_tickervolume_currentticker](https://user-images.githubusercontent.com/90146132/139595724-f80315c2-308a-4112-bc04-7fffd9c1496b.PNG)

> A nested loop was created to loop through the rows to assign the tickerStartingPrices and tickerEndingPrices for each ticker with if-then statments.

   ![nested_loop_startandend_prices](https://user-images.githubusercontent.com/90146132/139595731-48050767-e956-4300-8b4f-70982267f915.PNG)

> A for loop was used to obtain values for arrays to out the Ticker, Total Daily Volume, and Return created and formatted into the All Stock Analysis.

   ![ticker_totaldailyvolume_return](https://user-images.githubusercontent.com/90146132/139595736-0947d9da-68b7-4b5e-83c8-e9b9ead773e7.PNG)

### Comparing Stock Peformance:

> In the original code, 2018 and 2017 run time was longer. 

![old_code_2018](https://user-images.githubusercontent.com/90146132/139595798-aa45241b-e88f-467d-a107-c557806223dd.PNG)
![old_code_2017](https://user-images.githubusercontent.com/90146132/139595803-23a607b9-a834-4f34-8c3b-b994c3bdb288.PNG)

> After altering some of the code in the refactored vba challenge, the time was able to decrease by miliseconds with having the capacity to run through both year 2018 and 2017 simulataneously.

![VBA_Challenge_2018](https://user-images.githubusercontent.com/90146132/139595811-a9e000a7-4de3-4d9c-9352-685083e8f947.PNG)
![VBA_Challenge_2017](https://user-images.githubusercontent.com/90146132/139595822-dd17ee50-8833-4e30-996a-2b90fcd78ef5.PNG)

## Summary: In a summary statement, address the following questions.

### What are the advantages or disadvantages of refactoring code?
> Some of the advantages of refactoring code include fast execution times and scripts are easier to keep up with and read if there ever needs a change to be made. Since the refactored code is also well structured, the user is able to alter or fix mistakse in the code easier and faster.
> Some of the disadvantages of refactoring code include having to split up the code into several sections to figure out with line of code needs to be altered for efficiency. Although refactoring code is faster, it is possible that the refactored code could affect the testing outcomes of the data be analyzed, so it is important to keep up with what changes are being made to the code and how it affects the final product. 

### How do these pros and cons apply to refactoring the original VBA script?
> Since the goal was to refactor the code for Steve so that he was able to see ticker data for more than one year for the ticker of interest, refactoring the original VBA script was necessary to achieve what Steve wanted. Refactoring the code also made the execution time faster, so when there are more tickers that want to be analyzed, the code is more efficient in doing so rather than the original code. 
