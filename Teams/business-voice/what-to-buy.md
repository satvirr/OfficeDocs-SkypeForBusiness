---
title: What do I need to purchase to use Microsoft 365 Business Voice?
author: dstrome 
ms.author: dstrome
manager: serdars
ms.topic: article
ms.service: msteams
audience: admin
localization_priority: Priority
MS.collection: 
- Teams_ITAdmin_Help
- M365-collaboration
- Teams_Business_Voice
search.appverid: MET150
description: 
appliesto: 
- Microsoft Teams
---

# What do I need to purchase to use Microsoft 365 Business Voice?

## Microsoft 365 Business Voice license

If someone in your organization wants to make or receive phone calls to or from an external phone number, they need a Microsoft 365 Business Voice license. A Microsoft 365 Business Voice license gives them all the features they need to make or receive phone calls, host audio conferences, and more. Users who don't need to make or receive phone calls to or from external phone numbers just need Teams; they don't need a Microsoft 365 Business Voice license. For example, you might have 10 factory employees and 5 office employees. The factory employees only need to call other employees within your company. The office employees need to call other employees, and they also need to make and receive phone calls to and from suppliers, partners, and customers. In this case, only the 5 office workers would need a Microsoft 365 Business Voice license.

Included with Business Voice is a Domestic Calling Plan, which gives you a certain amount of minutes per month to make calls within your country or region. You can also add an International Calling Plan for an additional cost if you plan on making calls other countries or regions. You can pay for an International Calling Plan, extra minutes per month for the Domestic Calling Plan, and for toll-free numbers, using Communications Credits. You can learn more about Calling Plans and Communications Credits later in this article.

If you want to know which features are included with Microsoft 365 Business Voice, take a look at [Microsoft 365 Business Voice Service Description](https://docs.microsoft.com/office365/servicedescriptions/microsoft-365-business-voice-service-description).

To buy Microsoft 365 Business Voice licenses, sign into the [admin center](https://admin.microsoft.com/Adminportal/Home#/homepage), click on **Billing**, and then **Purchase services**.

## Calling Plans

Calling Plans let users call phone numbers outside of your organization. They come with a monthly pool of minutes based on the number of users assigned Business Voice licenses in a given country or region. When a user makes a phone call, the number of minutes their call takes is deducted from the total minutes remaining in the Calling Plan pool. At the beginning of each month, the remaining balance of minutes in the Calling Plan pool is reset.

Calling Plan pools are specific to the country or region in which users are located. Users in a country or region can only use minutes from the Calling Plan pool in their country or region. Minutes in a Calling Plan pool in one country or region can't be transferred to a Calling Plan pool in another country or region.

If all the minutes in a Calling Plan pool are used up, what happens depends on whether you have any Communications Credits available (we'll talk about Communications Credits later in this article). If you have Communications Credits, users will start using them. If you don't have Communications Credits, users won't be able to make phone calls until the Calling Plan pool is reset at the beginning of the next month.

> [!IMPORTANT]
> The number of minutes in a pool depends on the number of Business Voice licenses assigned to users, not the number of Business Voice licenses purchased. For example, if you've purchased 10 Business Voice licenses in Canada but are only using three licenses, you'll have a total of 9,000 minutes in your pool (3 licenses multiplied by 3,000 minutes per user).

There are two types of Calling Plans:

### Domestic Calling Plan

The Domestic Calling Plan lets users call phone numbers in their country or region. Business Voice includes a Domestic Calling Plan for each user that's assigned a Business Voice license. The number of minutes given to each user each month depends on which country or region the user is located in. Here's a table that shows the number of minutes for each country or region where Business Voice is supported:

|Where the user is located          |Monthly allotment for domestic calls |
|-----------------------------------|-------------------------------------|
|Canada                             | 3000                                |
|United Kingdom                     | 1200                                |

Calls between the United States and Canada are domestic calls. You don't need to add the International Calling Plan to place calls between these two countries.

### International Calling Plan

The International Calling Plan lets users call phone numbers outside their country or region. Business Voice doesn't include the International Calling Plan for every user but it can be purchased as an add on.

When you think about whether to buy a user an International Calling Plan, check to see how often they make international calls and how much time they spend on them. This is important because, when you purchase an International Calling Plan, you're paying for a certain number of minutes up front. If a user doesn't use up all of the minutes in a month, the remaining minutes are discarded at the beginning of the next month. If it's likely that a user won't use up all the minutes provided by an International Calling Plan, don't buy one and instead use Communications Credits (coming up in the next section).

## Communications credits

Communications credits are like a digital wallet that's used to pay for calls made to phone numbers outside your phone system. Communications Credits are used in a few situations:

- **A user has run out of minutes in their Domestic or International Calling Plan** When the minutes in a Calling Plan are used up, Business Voice automatically starts using the balance available in your Communications Credits.
- **A user doesn't have an International Calling Plan** If a user doesn't have an International Calling Plan, they'll immediately start using the balance available in your Communications Credits.
- **You have one or more toll-free numbers** When someone calls a toll-free number, the cost of the call is deducted from your Communications Credit balance.

If you still have Communication Credits left over at the end of the month, they're carried over to the next month.

### Buy Communication Credits

We strongly recommend that you always keep a minimum Communication Credits balance so that your users can always make phone calls. The easiest way to make sure you always have a Communications Credits balance is to set up automatic recharging. With automatic recharging, if your Communication Credits balance goes below a minimum limit, Microsoft 365 will automatically refill your balance. You can choose the minimum limit and the amount to buy each time. If you'd rather refill your Communication Credits balance manually, you can do that too.

> [!IMPORTANT]
> Remember that you need Communications Credits if you run out of minutes in your Calling Plans or if you receive toll-free calls. If your Communications Credits balance is empty, you won't be able to receive phone calls on toll-free phone numbers and users won't be able to make calls if their Calling Plan balances are empty.

To learn more about Communication Credits, take a look at [What are Communications Credits](../what-are-communications-credits.md)?

To see rates for toll-free and international calling, scroll down to **Add time with Communication Credits** in [Cloud Based Phone System](https://products.office.com/microsoft-teams/voice-calling#ow-download-rates).

## Maximum number of supported users

The Business Voice add-on that's available with small and medium-sized Microsoft 365 subscriptions supports up to a maximum of 300 licensed users. If you want to license more than 300 users for Business Voice, you need to purchase a Office 365 365 E3 or E5 subscription.

