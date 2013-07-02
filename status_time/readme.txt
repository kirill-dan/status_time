Readme
------
This module allow users to assign the lifetime in days their account.

Developer: Danilevsky Kirill k.danilevsky@gmail.com

It's small, but in many respects useful module allows you to assign the lifetime of a user's account.
This is necessary if you want to create for someone temporary guest access. Then you need to create a new account
and noted in the field "Date account blocking" date when will be blocked account.

After the expiry of specified period, the account will automatically
blocked and the user will not be able to get to the site under your login and password.

You can also assign a lifetime account for an existing user.

To verify compliance with the relevance of your account occurs at cron.

The installation process:

1. Installs the module.
2. Change the value of a field "Date account blocking", when adding or editing a user.
3. If you want to remove all the time limits, set empty value
4. Default value - empty field

History:

03.07.2013
Version 1.1

- Rewrote the logic module. Now the field is created through the Field API
- Now you do not need to specify in the days when the account is blocked
- To block the account should just specify the date when his block
- The following are required module Date
- Click on the field calendar appears, but you can enter the date and manually