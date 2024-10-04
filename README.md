# Data_Vault_2.0_Modeling_Project
This is a Sample Data Modeling Design and deployment project (Near Real Time vault) using Data Vault 2.0 methodology. 

Snowflake Quick Starts Link : https://quickstarts.snowflake.com/guide/vhol_data_vault/index.html?index=..%2F..index#0


Hands-on code repo: https://github.com/dheeraj2112/Data_Vault_2.0_Modeling_Project/blob/ae6fc13b2b03dd86e7279d708481cc3b34279f5a/Data%20Vault%202.0%20on%20Snowflake%20tutorial%20code%20repo.sql


Data Vault Modeling Guide:  https://github.com/dheeraj2112/Data_Vault_2.0_Modeling_Project/blob/014a714a2c817bfbe3b13cde85c5e9f6d4f4e690/data-vault-modeling-guide.pdf

**Course Overview and Contents**

**1. Overview**

In this day and age, with the ever-increasing availability and volume of data from many types of sources such as IoT, mobile devices, and weblogs, there is a growing need, and yes, demand, to go from batch load processes to streaming or "real-time" (RT) loading of data. Businesses are changing at an alarming rate and are becoming more competitive all the time. Those that can harness the value of their data faster to drive better business outcomes will be the ones to prevail.

One of the benefits of using the Data Vault 2.0 architecture is that it was designed from inception not only to accept data loaded using traditional batch mode (which was the prevailing mode in the early 2000s when Dan Linstedt introduced Data Vault) but also to easily accept data loading in real or near-realtime (NRT). In the early 2000s, that was a nice-to-have aspect of the approach and meant the methodology was effectively future-proofed from that perspective. Still, few database systems had the capacity to support that kind of requirement. Today, RT or at least NRT loading is almost becoming a mandatory requirement for modern data platforms. Granted, not all loads or use cases need to be NRT, but most forward-thinking organizations need to onboard data for analytics in an NRT manner.

Those who have been using the Data Vault approach don't need to change much other than figure out how to engineer their data pipeline to serve up data to the Data Vault in NRT. The data models don't need to change; the reporting views don't need to change; even the loading patterns don't need to change. (NB: For those that aren't using Data Vault already, if they have real-time loading requirements, this architecture and method might be worth considering.)

**Data Vault on Snowflake**

There have been numerous blog posts, user groups, and webinars over the last few years, discussing the best practices and customer success stories around implementing Data Vaults on Snowflake. So the question now is how do you build a Data Vault on Snowflake that has real-time or near real-time data streaming into it.

Luckily, streaming data is one of the use-cases that Snowflake was built to support, so we have many features to help us achieve this goal. This is an extended version of the article posted on Data Vault Alliance website, now including practical steps to build an example of real-time Data Vault feed on Snowflake. see the simple-to-follow steps to see it in action.

**Prerequisites**
A Snowflake account. Existing or if you are not(yet) a Snowflake user, you can always get a trial account
Familiarity with Snowflake and Snowflake objects
Understanding of Data Vault concepts and modelling techniques


**Learning Outcomes**

how to use Data Vault on Snowflake
how to build basic objects and write ELT code for it
how to leverage Snowpipe and Continous Data Pipelines to automate data processing
how to apply data virtualization to accellerate data access


**What You'll Build**
A Data Vault environment on Snowflake, based on sample dataset
Data pipelines, leveraging streams, tasks and Snowpipe

<EOD>

