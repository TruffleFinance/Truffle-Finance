---
description: Calculating APY
---

# 💸 How the APY is Calculated

### Compound Interest Equation

$$
A = P(1 + r)^n
$$

Where:

* A = Total Accrued Amount (principal + interest)
* P = Principal Amount
* r = Rate of Interest for each epoch (3 seconds)
* n = # of epochs

We have:\
r = 0.000000858%\
3 second = 1 epoch\
1 year = 10512000 epochs

So:

$$
A = P(1 + 0.000000858)^{10512000}= P(1+8259.92)
$$

So it means,

$$
APY =(A/P -1)*100 = 825992.73 %
$$

Same goes to other time periods.

$$
A_{month}=P(1+0.000000858)^{20*60*24*30}=P(1+1.0986)
$$

$$
A_{week}=P(1+0.000000858)^{20*60*24*7}=P(1+0.1888)
$$

$$
A_{day}=P(1+0.000000858)^{20*60*24}=P(1+0.025)
$$

$$
A_{hour}=P(1+0.000000858)^{20*60}=P(1+0.001)
$$

$$
A_{minute}=P(1+0.000000858)^{20}=P(1+0.0000171)
$$

0.0000858% per block (3 seconds)\
0.00171% per minute \
0.1% per hour \
2.5% per day \
18.88% per week \
109.86% per month \
<mark style="color:green;">980,990,50%</mark> <mark style="color:green;">per year (APY)</mark>

### <mark style="color:green;">**Example:**</mark>

**P = **<mark style="color:green;">**$1,000**</mark>

**A = (After 1 year) = **<mark style="color:blue;">****</mark>** **<mark style="color:green;">**$9,809,905.00**</mark>
