# Project4

iota.gpu

|Vector<br>Length|Wall Clock<br>Time|User Time|System Time|
|:--:|--:|--:|--:|
|10| 0.30| 0.07| 0.23|
|100| 0.26| 0.06| 0.20|
|1000| 0.26| 0.06| 0.20|
|10000| 0.29| 0.07| 0.22|
|100000| 0.27| 0.06| 0.21|
|1000000| 0.29| 0.06| 0.23|
|5000000| 0.32| 0.07| 0.24|
|100000000| 0.90| 0.19| 0.70|
|500000000| 3.40| 0.73| 2.66|
|1000000000| 6.55| 1.47| 5.08|
|5000000000|40.21| 8.71|31.50|

iota.cpu

|Vector<br>Length|Wall Clock<br>Time|User Time|System Time|
|:--:|--:|--:|--:|
|10| 0.00| 0.00| 0.00|
|100| 0.00| 0.00| 0.00|
|1000| 0.00| 0.00| 0.00|
|10000| 0.00| 0.00| 0.00|
|100000| 0.00| 0.00| 0.00|
|1000000| 0.00| 0.00| 0.00|
|5000000| 0.02| 0.00| 0.02|
|100000000| 0.52| 0.07| 0.44|
|500000000| 2.63| 0.39| 2.24|
|1000000000| 5.34| 0.83| 4.51|
|5000000000|36.31| 6.32|29.98|

Question: It seems like the gpu takes longer, which was not what I was expecting. I'm honestly not sure why this is: Maybe the conversion from
float to integer is slowing things down? Maybe the gpu isn't as good at math as the cpu?

![Screenshot 2025-05-10 233516](https://github.com/user-attachments/assets/f623a00d-c535-4eb8-8879-2914cb78a71b)
