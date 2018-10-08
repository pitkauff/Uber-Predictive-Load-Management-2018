# Uber - Predictive Load Management

### Problem Statement: ride-sharing companies such as Uber and Lyft have historically had issues with large-scale events (inlduing concerts and sports events) to the extent that customers are forced to either accept high wait times or exorbitant surge priing. The below analysis attempts to suggest a solution to that problem, by predicting requests ahead of time, which would allow a company to pre-emptively relocate vehicles in anticipation of demand spikes.

**Data Sources**

- Uber trip data - https://github.com/fivethirtyeight/uber-tlc-foil-response
- Yellow taxi trip data - http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml

x<sub>ij</sub>

|   |     1    |    2     |     3    |
| - | -------- | -------- | -------- |
| 1 | 0.992608 | 0.686474 | 0.172143 |
| 2 | 0.686474 | 0.992608 | 0.541465 |
| 3 | 0.172143 | 0.541465 | 0.992608 |

c<sub>ij</sub>

|   |    1    |    2    |    3    |
| - | ------- | ------- | ------- |
| 1 | 0       | 4.14604 | 8.19311 |
| 2 | 4.14604 | 0       | 5.24474 |
| 3 | 8.19311 | 5.24474 | 0       |

N<sub>0j</sub>

|   |   N_0j   | 
| - | -------- |
| 1 | 5.3333   | 
| 2 | 43.6667  |  
| 3 | 704.6667 | 

r = 13.54
