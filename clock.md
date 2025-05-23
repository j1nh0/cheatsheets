<table align="center">
<tr><td>

|#####|
|:---:|
|UNITS|
|  CPU|
|  RAM|
|  HDD|
| SWAP|

</td><td>

|######|####|####|
|:----:|:--:|:--:|
|      | VM |    |
|2x1(U)|   2| 28U|
| 8192M|  8G| 24U|
|  16GB|16GB| 24U|
|    !=|  !=|  !=|

</td><td>

|######|####|####|
|:----:|:--:|:--:|
|      | CT |    |
|1x1(U)|   1| 56U|
| 4096M|  4G| 48U|
|   8GB| 8GB| 48U|
|    !=|  !=|  !=|

</td></tr></table>

<table align="center">
<tr><td>

|#####|###############|
|:---:|:-------------:|
|     |       SCHEDULE|
|200AM|   PWR ON PBSGW|
|215AM|        BCKP CT|
|230AM|        BCKP VM|
|245AM|    BCKP VERIFY|
|300AM|      REBOOT HV|
|315AM|      REBASE FW|
|330AM|STANDARD REBASE|
|345AM|               |
|400AM|               |
|415AM|               |
|430AM|               |
|445AM|               |
|500AM|     PWR ON CMS|
|515AM|               |
|530AM|               |
|545AM|               |

</td></tr></table>
