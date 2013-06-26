Readme
------
This module allow users to assign the lifetime in days their account.

Developer: Danilevsky Kirill k.danilevsky@gmail.com

It's small, but in many respects useful module allows you to assign the lifetime of a user's account.
This is necessary if you want to create for someone temporary guest access. Then you need to create a new account
and noted in the field Lifetime time of working account in days.

After the expiry of specified period, the account will automatically
blocked and the user will not be able to get to the site under your login and password.

You can also assign a lifetime account for an existing user. But be aware that the module
start counting from the beginning of the creation of this account, and not from the time when you have assigned the lifetime of the account.

To verify compliance with the relevance of your account occurs at cron.

The installation process:

1. Installs the module.
2. Change the value of a field Lifetime, when adding or editing a user.
3. Lifetime value of the field should be in days. If you want to remove all the time limits, set value = 0
4. Default = 0