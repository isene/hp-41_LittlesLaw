# hp-41_LittlesLaw
Using [Little's Law](https://corporatefinanceinstitute.com/resources/data-science/littles-law/) to calculate resolution (throughput) time in a queue - e.g. resolution time for IT Service Desk tickets.

Use this convenient program to quickly get your average resolution times.

Upon `XEQ "LL"` you will first be prompted with `H D W M <=P?` Which means you will decide which time span (period) you are calculating the average for. Press `A` for Hours, `B` for Days, `C`for Weeks or `D` for Months. So - if you want to find out how many days it takes on average to solve a ticket in your Service Desk, then press `B`for Days. You can recalculate this to Hours, Weeks of Months later.

After pressing your desired period, you will be prompted with `QUEUE SIZE?`. Here you will enter how big the queue currently is - e.g. how many open tickets does your Service Desk have now. Then press `R/S`.

Then you will be prompted with `QUEUE INPUT?`. Now enter the number of items (tickets) that came in during the past period. You will get a more accurate result if you take the average incoming items/tickets over the past few periods - e.g. the number of tickets received in the past week divided by 7 which is the average per day.

When this is entered and you press `R/S` you will get the calculated average resolution time (e.g. `2.14 D` if you chose Days as the Period).

Now you can recalculate this number to Hours, Days, Weeks or Months by pressing `A`, `B`, `C` or `D` respectively.

## License
This software is released into the Public Domain.

