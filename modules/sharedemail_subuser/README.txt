Sharedemail Subuser
-------------------

This modules integrates the Shared Email and Subuser modules. It provides the
following functionality.

1. Subusers use the same email address as their parent account.
2. Only Subuser accounts may use an email address otherwise in use.
3. Subusers may not change their email address.

Corner Cases
------------

If you change an email account via a method that does not go through standard
hook_user() update methods, email accounts might fall out of proper sync.
