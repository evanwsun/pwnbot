# Pwnbot
Hi Troy,

A friend and I decided to focus on trying to reach more people who may not know they've been pwned. We've created a simple Slack bot called Pwnbot. While there is already a Slackbot that incorporates the API, we incorporated a number of features focusing on ensuring that users are able to check their emails for breaches as well as alert others in their organizations to breaches:

1. Check all emails in a slack organization, return a list of those pwned and not pwned, and privately DM each individual with details.

2. DM each new user upon sign-up to the Slack whether their associated email has been pwned. Returns the list of breaches in a text file.

3. Check the email associated with your slack account as well as any email you pass as a parameter. Returns if you have been pwned along with details of the breaches. 

It also redirects users to haveibeenpwned for more information. We think that with Slack's growing popularity, this is an easy way to reach hundreds of individuals without requiring them to visit another site or install anything. 

You can check out the code at https://github.com/evanwsun/pwnbot

The current bot is hosted at  https://glitch.com/edit/#!/pwnbot

Screenshots of it working are available at https://imgur.com/a/yPWoF


Let us know if you have any questions!

Evan and Ben
