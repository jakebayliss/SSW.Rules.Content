---
type: rule
title: Explaining PBI's
uri: explaining-pbis
authors:
  - title: Jake Bayliss
    url: https://www.ssw.com.au/people/jake-bayliss
created: 2022-10-12T03:57:00.991Z
guid: 42132d16-69d8-4900-bce0-83f0209b6ab0
---
Explaining PBI's to our Product Owner is an important part of the process of getting PBI's over the line. We as developers love diving into the details about what we have been working on and all the complex things we have had to do and it can be a hard task to skip over all that. However, we need to remember that the technical details are not the most important things to our Product Owner but rather it is the business value that they will be gaining.

<!--endintro-->

It is like taking your car to the mechanic and them telling you all of the things they had to do to fix your car. But you don't really need to know and just want to drive off in a working car.

### Follow the Zoom-in and out rule

We have a rule on how to structure your explanations - https://www.ssw.com.au/rules/zooming-in-and-out

### Cater your explanation to your audience

And a rule on catering to your audience - https://www.ssw.com.au/rules/catering-to-audience

We are trying to put these two together when explaining our PBI's to our Product Owner.

## The demonstration steps

Generally, you want to follow these 4 steps when demonstrating your PBI's to your Product Owner:
* Give context on the problem and PBI itself. The product owner most likely knows this already but this will give them a second to refresh their memory on why this exists. Remember to focus on the business value here and not to include any unnecessary technical details.
* (If applicable) Show the old feature to reinforce the problem we are having. This will really highlight the business value that we were missing out on. Remember to include any important details.
* Show the new feature to reinforce the value that we are gaining.
* Ask for any feedback on the current feature


::: greybox
Example PBI:
Policy Form - Show the Policy Owner
:::

::: greybox
For this I had to do an extra join to the Member table from the ClientLink table where the link reason was PO which means Policy Owner, and then from there I could join the Client table to that ClientLink record to get the Policy Owner name.
Here is what that looks like.
:::
::: bad 
Figure: Bad example - we are mentioning all these tables that are not necessary to talk about
:::

::: greybox
In some cases the Policy Owner could be a Super Fund so our users needed to know if the policy owner was the Life Insured individual or whether it is a Super Fund.
This was the policy screen before and we can't see who the Policy Owner is.
Now here is the new form where we are showing the Policy Owner and the users can even click through to the Owner if they need any other details.
Do you have any feedback?
:::
::: good
Figure: Good example - We give context, show the old version, then the new version and ask for feedback
:::
