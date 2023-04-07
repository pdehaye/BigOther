EU and Swiss data protection laws allow individuals to access their personal data. 

This is the result of doing such a request for data with the company Uber. Note that I have only used Uber for a handful of rides (all in the U.S.)

Credit
======

Please credit Paul-Olivier Dehaye, co-founder of [PersonalData.IO](http://www.PersonalData.IO) if you use this data for research, art, education, journalism or business purposes.

Data file
=========

The data is contained in one file called `uber_second_response.xlsx`, a workbook spanning several sheets. Apologies for using this  format, but this is what I was given by Uber, with all the weird formatting. All the other files are from a previous successful request, and contain less data and different exports for it.  

It contains, among other things, information about:
 - my timestamped latitude, longitude, orientation and altitude prior to getting a ride, as well as uncertainty on some of those measurements;
 - my battery level when setting up the ride;
 - my timestamped latitude and longitude during a ride, as measured through the drivers' device;
 - my star rating, per ride.

Data removed
============

For privacy reasons, Uber removed some of the data prior to sending over the rest. This includes, for instance, the name of my drivers. I myself edited some of the data so I could share it more widely. This includes, for instance, information related to my credit card. 

 * AAA: email
 * BBB: phone
 * CCC: ?????
 * DDD: last 4 digit credit card, bank, expiration date
 * EEEEEEEE-EEEE-EEEE-EEEE-EEEEEEEEEEEE: (Apple) Advertiser ID
 * FFFFFFFF-FFFF-FFFF-FFFF-FFFFFFFFFFFF: Uber ID
 * GGGGGGGGGG: push notification token

History of the requests
=======================

This is the result of several requests. The first was in July 2015. It was addressed to the Uber headquarters in the US, who punted to their European HQ in the Netherlands, but I never heard back from them. I tried to get the [Dutch data protection authority to investigate on the topic](https://www.reddit.com/r/thenetherlands/comments/3rxs9a/help_with_submitting_a_verzoekschrift_bij_de/), but they declined and told me I would have to sue. The Belgian DPA refused to get involved, despite my nationality, as I had not used Uber there. 

On April 25th 2016, I filed again, this time by certified mail directly addressed in the Netherlands, which finally prompted a first successful response from Uber NL (see `uber_first_response.xlsx`). You can see the course of the exchange in the `letters/` folder. Further insistance from me led to more detailed response from Uber (`uber_second_response.xlsx`), including much more data.

Battery level
=============
The data recovered includes battery levels. This is discussed in the following paper:
"Battery Status Not Included: Assessing Privacy in Web Standards" Lukasz Olejnik, Steven Englehardt, Arvind Narayanan
https://lukaszolejnik.com/AssessingPrivacyWebStandardsIWPE17.pdf
