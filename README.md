# Forbes_Data_Python
Forbes Richest Athletes List (1990-2020): Performed exploratory analysis on data using Numpy, Pandas, Matplotlib, and Plotly

SITUATION & TASK:
  - The X Company (not a real company) wanted to know if there were any correlations in the Forbes Richest Athletes list from 1990-2020. 
  - I was tasked with finding insights in the data and utilizing a Jupyter Notebook to consolidate code and visualizations.
  - The data wasn't completely clean, but this was strictly for me to explore and learn.

ACTION:
  1. I started by importing everything I knew I would either use, want to try, or want to learn. This included: Numpy, Pandas, Plotly, Matplotlib, and HTML.

<img width="700" alt="Forbes-1" src="https://user-images.githubusercontent.com/64383895/166611971-f961c884-08fd-46e9-910c-fdad36e1072d.png">

  2. Next, I wanted to figure out who the athletes were that had been on the list at least 10 times. To do this, I grouped the athletes by the number of times their names appeared on the list. I created a bar chart to show the number of athletes with counts greater than or equal to 10.

<img width="650" alt="Forbes-3" src="https://user-images.githubusercontent.com/64383895/166612308-763aa42b-0a20-4cad-a18f-1a14c4cb8fe7.png">

  3. To determine which countries produced the highest number of high-paid athletes, I created a function that counts the number of times each country appears on the list and delivers the top 10 results in descending order. I, then, wanted to practice making a pie chart. Utilizing the same function, I was also able to find the top 10 sports producing the highest numbers of high-paid athletes.

 <img width="650" alt="Forbes-4" src="https://user-images.githubusercontent.com/64383895/166612675-8802a4d3-3a38-44e1-9ee5-375008ce89e4.png">


  4. My next question was how much each athlete earned in total for each time they made the list. I grouped the athletes by name and took the sum of their reported earnings. I also made another bar chart.

<img width="650" alt="Forbes-5" src="https://user-images.githubusercontent.com/64383895/166613617-5277a306-3fba-443c-a16e-aafe911989f9.png">

  5. I decided to focus my attention on a specific athlete, so I chose Floyd Maywether. I wanted to know how his earnings evolved over time. Using the get_group function and his name as an argument, I was able to create a sub-table with just his information. I used this table to create a line graph to show the highs and lows of his earnings.

<img width="650" alt="Forbes-6" src="https://user-images.githubusercontent.com/64383895/166614081-43065c07-9416-498c-8d81-22d8bd58ab11.png">

  6. My final act was to create an animation which illustrates changes to the top 10 of the list over time. I created a video which can be viewed here:

https://user-images.githubusercontent.com/64383895/166614157-6c6e8349-6f39-411e-9c16-0b5b624605f3.mp4

RESULT:
  - I was able to pull 7 different insights from this list. I used this list to learn how to create different visualizations with Matplotlib, get more experience manipulating data using Pandas and Numpy, and create an animation using Plotly.

