---
layout: answered-question
author: Serge
title: Unattended vs Attended UiPath Robots Question Answered
blurb: Learn when to use attended vs unattended robots. Your RPA architecture depends on this knowledge.
heading: UiPath PDF Activity and Invoices
difficulty: 6
objective: 1.1 Identify and describe the different types of robots, i.e., attended versus unattended robots
canonical: https://www.rpacertified.com//2020/11/11/unattended-robots-when-to-use.html
---


Question: A expense report submission process, in which the first step requires the user to log into the reporting system, must attach scanned image receipts and PDF files as part of the expense. This activity lends itself best to which of the following implementations:

- [ ] &nbsp;  A process that uses a single unattended robot
- [x] &nbsp;  A process that uses a single attended robot
- [ ] &nbsp;  A process that uses both a single attended robot and a single unattended robot
- [ ] &nbsp;  This process doesn not lend itself to automation

## Answer

Options b is correct.

Since the user must log into the reporting system, an unattended robot cannot be used.

<img src="https://files.readme.io/4b716bb-att.png" class="img-fluid" alt="Attended vs Unattened robots in UiPath">

