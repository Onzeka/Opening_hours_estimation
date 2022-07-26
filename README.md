# Opening_hours_estimation
Original method for estimating business opening hours

The notebook is to big to be rendered properly here is the link for the html view :

https://htmlpreview.github.io/?https://github.com/Onzeka/Opening_hours_estimation/blob/main/mytraffic.html


The goal here is to estimate the opening hours of some stores from phone pings near the store recieved by an antena.I decided to modelize the phones pings
as a poisson's law and tried to find the timestamp where the parameter lambda of this law was discontinuously changing.In order to do so the main challenge 
was to detect "jumps" on the ping distribution.All the charts are interactive for better visibility.
