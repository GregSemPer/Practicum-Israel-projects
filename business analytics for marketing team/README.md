# Goal

This project aimed to find out the most profitable sources for the ad campaings based on the logs from Yandex.Afisha service from June 2017 through May 2018, containing information on the visits, orders and marketing expenses fro the given period.

The main question is to help optimize marketing expenses: what sources/platforms can be recommended for futher investments? 

# Data description:

### The visits table (server logs with data on website visits):

`Uid` — user's unique identifier

`Device` — user's device

`Start Ts` — session start date and time

`End Ts` — session end date and time

`Source Id` — identifier of the ad source the user came from
 
*All dates in this table are in YYYY-MM-DD format*

### The orders table (data on orders):
`Uid` — unique identifier of the user making an order

`Buy` Ts — order date and time

`Revenue` — Yandex.Afisha's revenue from the order
 
###The costs table (data on marketing expenses):
`source_id` — ad source identifier

`dt` — date

`costs` — expenses on this ad source on this day
