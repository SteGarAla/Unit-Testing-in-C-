# Unit Testing in C#
CW 13: Unit Testing In C#

## Objective
Get use to writing unit tests in C#

Modify and fix unit test for Debit method

Create 3 unit test for the debit function that test the following:
1. If everything else checks out, the debit amount should be subtracted from the account balance
2. If the debit amount is negative, it should also throw an ArgumentOutOfRangeException
3. If everything else checks out, the debit amount should be subtracted from the account balance

Create 3 unit test for the credit function that test the following:
1. The account has been frozen and an exception is thrown.
2. The argument (debit amount) is negative, and an ArugmentOutOfRangeException is thrown.
3. Make sure that the account is updated by amount when everything hunky dory.
