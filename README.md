# Automated Web Scraping
Use the 'rvest' package in Rstudio to automatically web scrape donations to 'teamtrees.org' testing the goal-gradient hypothesis at a collective level.
The running_script md is used to extract total donations and save the output to a .csv file.
The 'taskscheduleR' package is used to automate when the running_script is executed (e.g., what time each day).
Trees_GoalGradient md takes the data from the .csv file and models the change in donations.
