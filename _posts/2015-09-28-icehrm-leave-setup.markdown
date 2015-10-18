---
layout: post
title: IceHrm Setting up Leave module
description: How to setup IceHrm leave module properly
---

Since I've have noticed that its not a trivial task to setup the icehrm leave module initially when moving from another 
active leave management setup, I'm writing this to walk you through a short tutorial.

### Assumptions

Let's assume following:

1. You are moving the leave management system to icehrm, in the middle of a leave period for 2015
2. Some of your employees have leaves carried forwarded from 2014, which might not have been used
3. Your company have annual leaves which can be carried forwarded to next year
4. Company supported casual leaves which are accrued 1.5 per each month
5. Some employees have joined in 2015 and there leaves should be proportionate according to joined date

### Setting up leave types

First task is setting up the leave types

1. Lets setup the leave type for annual leaves which can be carried forwarded to the next year

![Setting up annual leave](/assets/blog/adding-annual-leave.png)

Here I've set leave carried forward to 'Yes' and carry forward percentage to 100% so all the remaining leaves of
this year will be carried forward to the next.



** Not completed yet .. **