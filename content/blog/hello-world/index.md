---
title: "Things developers can do to improve the UX"
date: "2019-04-14"
description: "spoiler alert"
---

There are small things that developers can do that can improve the overall user experience and development time which do not require high expertise levels on user experience, these small things that when passed unnoticed can damage application's overall experience, on the other hand, if you spend some time to look for these small things and correct them, it might improve your app's user experience by a significant factor.

Let the user do something in your app without requiring him to log in
"If you ask me for my data before offering any value, that means you're more concerned with my data than with solving my problem". Rushing User
But, if you can, just add a simple "Browse without account" button on your app. You will see that once experienced, once they completely understand why and how your service will ease their life, the users will definitely want to be a part of it and create an account. And the people who will signup here will be the one true users because they did sign up completely intentionally.


I think the statement above sums it up, you shouldn't ask for a user to log in or give in his data before even showing him why your app deserves his attention or data. I know some apps need to know about the user prior to him using it but I think you can always figure a way to give value before you ask for it.

Don't ask them to invite their friends nor rate you
Seriously I don't think users invite other people to use an app no one does that, it's odd and weird, if I want my friend to use this X app I simply tell him to download and explain the benefits and tell him how cool I I'm because I'm using it or how it has changed, improved or helped me doing X thing. Word of mouth is the kind of invite or recommendation that people want, not receiving a message or an email saying user X invited you to use this app, how is the app supposed to solve my problem if it's already creating a new one by spamming me?


Prefer Google sign in over traditional email-password
When you use Google Sign in with play services or firebase authentication, it creates an intent that shows a dialog for the user, where he can select the email to use in his app, unlike Facebook, Twitter or Linkedin (that usually requires opening another app or a browser) it does not require opening browser or another app to log in.
Opening the browser or external apps uses RAM and processing power, which is not what you want your app to do, because most devices have low RAM, processing power and scarce, even if they have good processing power it's highly likely that they opened dozen other apps besides yours.

One of the advantages of using Google OAuth is that the user doesn't need to memorize a password or a username, which also implies that you don't have to implement the logic for "forgetting" password/reset password that the user is likely to forget over and over again, until he/she stops using your service.
Maybe you're concerned that the user does not have a Google account, but if you distribute your app through Google Play, then the user will only be able to download it if he is signed up.
So that means If you use OAuth not only you have the convenience of logging the user in without requiring a password you also have access to the data that the user has already filled in his Google account


Having to memorize things is a pain/hard and time consuming, usually users have a lot of things to keep track of (tasks, family names, phone numbers, daily tasks) so it's very unlikely that they'll memorize your apps' password, they have zillions of apps, you want to make your app easy to use without the hassle of memorizing passwords and emails.


Use appropriate language (clean concise user language)
Unlike others extremely formal fields like architecture and advocacy, in software, no one will come and suspend your app because the language is not grammatically correct or it used words that do not exist in the dictionary.
When building your app prefer a language that is easy to grasp and is in the context it doesn't have to be grammatically correct, thou this is not an appeal to ignore the grammar completely but there are small things you can do or change in your language to make it easier to understand to your specific users.