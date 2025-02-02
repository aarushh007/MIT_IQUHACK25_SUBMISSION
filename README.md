
# TEAM AQUI 
Aarush Hadimani: aarushh007@gmail.com

Hari Palaniyappan: hpalaniyappan@gmail.com

Venkat Pasupuletti: saharshvenkatp@gmail.com

Adhitya Vasudevan: adhiv2007@gmail.com

Niranjan Nair: niranjan.nair.email@gmail.com

## Description

RSA is a really popular encryption method which is used for many applications. It encrypts everything from direct messaging to bank transactions. It involves a public encryption key and a private decryption key. Given the public encryption key, classical algorithms have tried countless times to find the decryption key. The most they could do was __ number, which took 2000 years of processing time. Professor Shor proposed a solution to this problem in the form of Shor's aglorithm, which uses principles of number theory to effectively to factorize large integers. 

To factorize the following semiprime numbers, we used Shor's algorithm optimized using qubits from Quantum Rings. See the python notebook for more details.



| **Bits** | **Number** | **Factors** | **Qubits Used** | **Execution Time** |
|----------|------------|-------------|-----------------|--------------------|
| 8        | 143        | 13 , 11     | 19              | 1s                 |
| 10       | 899        | 29 , 31     | 23              | 3s                 |
| 12       | 3127       | 53 , 59     | 27              | 8s                 |
| 14       | 11009      | 101 , 109   | 31              | 38s                |
| 16       | 47053      | 211 , 23    | 35              | 440s               |
| 18       | 167659     | 389 , 431   | 39              | 3720s              |
| 20       | 744647     | 821 , 907   | 43              | 24786s             |  |



## Bits vs Time Relationship 

The time t (seconds) it takes to factorize an x-bit number can be represented by

t = 5.01569*10^{-20} * x ^ 18.22 + 0.15 

![Graph](https://i.postimg.cc/d0qqSqXK/Screenshot-2025-02-02-074044.png)

Using our method and according to this relationship we found, it would take 120131319599983696 years to factorize the 256 bit semiprime 104343749483876530238735961449384774965065842501756473864398652143393515842787
## Gate Counts

| **Bits** | **Number** | **Barrier** | **cu1** | **cx** | **h** | **x** |
|----------|------------|-------------|---------|--------|-------|-------|
| 8        | 143        | 51          | 28      | 8      | 16    | 1     |
| 10       | 899        | 63          | 45      | 10     | 20    | 1     |
| 12       | 3127       | 75          | 66      | 12     | 24    | 1     |
| 14       | 11009      | 87          | 91      | 14     | 28    | 1     |
| 16       | 47053      | 99          | 120     | 16     | 32    | 1     |
| 18       | 167659     | 111         | 153     | 18     | 36    | 1     |
| 20       | 744647     | 123         | 190     | 20     | 40    | 1     |




