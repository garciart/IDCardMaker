# ID Card Maker

![Demo ID Card](demo_card.png "We're on our way, Rampart!")

>*The Real ID Card Maker allows you to create identification cards compliant with the REAL ID Act of 2005.*

## Introduction:

One day back in 2013, in the radio room of Station 16, one of my fellow firefighters was discussing how he got discounts at Walt Disney World because he was a firefighter. He said that he used letters and pay stubs to prove he was with the Salisbury Fire Department, which brought up a conversation about why we did not have identification cards. At the same time, since we were gaining a few more people, the department was going to purchase more key fobs, which we used for building access. I did some research and found that by creating ID cards on proximity cards, we could kill two birds with one stone.

I wrote up a proposal to purchase a HID Prox card printer and presented it at the next volunteer corporation meeting (I was a volunteer at the time). The idea was approved unanimously, and I started looking into ID card creating software. One company got back to me, stating that the software would cost $3000, plus a licensing fee per computer using the program. Even though the corporation had allocated enough funds to cover both the printer and the software, I thought to myself, "I can probably write the application myself." Four months later, I launched the web application (this way it could be used on the ambulance tablets, which allowed people to take their head shot and sign the card digitally) and within a month, everyone had an ID card/proximity card. We did have some growing pains, but the application has run error-free since then!

Here's the code, and if you need REAL ID compliant cards for your company, you can customize the application, load it up to your web server, and start printing out cards!

## Solution Stack

.NET Core 3.1, SQLite, C#

## References:

Wikipedia. (2005, May 9). Real ID Act. Retrieved July 21, 2018, from [https://en.wikipedia.org/wiki/Real_ID_Act](https://en.wikipedia.org/wiki/Real_ID_Act "Real ID Act")