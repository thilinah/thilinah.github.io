---
layout: post
title: IceHrm Setting up Leave module
description: How to setup IceHrm leave module properly
---

Since I've have noticed that its not a trivial task to setup the icehrm leave module initially when moving from another 
active leave management setup, I'm writing this to walk you through a short tutorial.

### Assumptions

Let's assume following:

1. You are moving the leave management system to icehrm, in the middle of the leave period for 2015
2. Some of your employees have leaves carried forwarded from 2014, which might not have been used
3. Your company have annual leave which can be carried forwarded to next year
4. Company supported casual leave which are accrued 1.5 per each month
5. Some employees have joined in 2015 and there leaves should be proportionate according to joined date

### Setting up leave periods

First task is setting up the leave periods. If you are starting from 2015 you only need to have the 2015 leave period.
But creating a leave period for 2016 also should not be an issue. Creating a leave period for 2014 will carry forward
what ever the remaining leaves from 2014 to 2015. In that case you have to enter all employee leave details for 2014 
manually into IceHrm. So the preferred way is to not create the previous leave period by adding all leave carried forwarded 
by employees using PTO (there will be another section for this).

Also note that leave period can have different lengths and can be started from any month in the year.


![Setting up leave periods](/assets/blog/leave-periods.png)

### Setting up leave types


1. Lets setup the leave type for annual leave which can be carried forwarded to the next year


![Setting up annual leave](/assets/blog/adding-annual-leave.png)

Here I've set leave carried forward to 'Yes' and carry forward percentage to 100% so all the remaining annual leave of
this year will be carried forward to the next.

2. Setting up casual leave with which are accrued 1.5 per each month and should not be carried forward to the next year


![Setting up casual leave](/assets/blog/casual-leave-setup.png)


Note that I have entered 18 for leave amount, this will accrue 1.5 (18/12) days per month since leave period length for 2015 is 12 months



** Not completed yet .. **