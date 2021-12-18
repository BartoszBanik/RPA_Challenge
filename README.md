# RPA_Challenge
Project is a solution to RPA Challenge from https://www.rpachallenge.com/ web site.
Solution is divide to 2 parts:
  1. User is selecting folder where excel file from abovementioned site is downloaded and will be used in futher actions
  2. Robot is checking if folder was selected. If no it stops, if yes:
    a) enters https://www.rpachallenge.com/
    b) clicks download button and saves file in selected folder
    c) reads data from folder
    d) clicks start button and enters excel data to web form
    e) after all data are entered robot takes screenshot with final time and it is saved to folder that was selected in first step
