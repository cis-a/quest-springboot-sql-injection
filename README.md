# BankZecure Web Application

All the instructions are in the quest!

# Optional Task solved
As long as the update procedure did not use prepared statements, I managed to:
1) using the HTML-Inspector in the browser, EDIT the hidden form field to change VALUE to ' or true -- ' : 
    <input name="identifier" type="hidden" value="' or true -- '">
2) then input password "abc" in the form, and klick "update profile"
=> Outcome: all user passwords in the "customer" table were updated to "abc" (same could be done for all email-addresses).


The fake customer accounts' credentials are listed [here](https://github.com/WildCodeSchool/quest-springboot-sql-injection/blob/master/FakeAccountsCredentials.md).
