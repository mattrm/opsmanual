Email alias management
======================

Introduction
------------

This document contains a description of how to manage our large set of email
domains and aliases. **Members of the coordination team** (management + unit
heads), as well as the sysadmin team, can edit aliases through the interface at
FastMail, our front-line email provider.

How to add an email alias
-------------------------

#. Visit the `FastMail Virtual Domains configuration page <fm-config_>`_ (log in
   from LastPass)

   .. _fm-config: https://www.fastmail.fm/html/?MSS=!SE-*&MSignal=VD-*&u=a864411d

#. Fill out the form as shown below. For this example, we are adding an alias so
   that joe.bloggs@gmail.com receives mail sent to joe.bloggs@okfn.org. Please
   ensure that the penultimate checkbox (“SRS”) is checked as shown below.

   .. image:: add-alias.png

#. When you’re done click the “Add” button. You should see a confirmation like
   the following at the top of the page:

   .. image:: notification.png

#. If the domain you wish to receive email at is not in the dropdown list,
   please submit your request to sysadmin@okfn.org.

How to remove an email alias
----------------------------

#. Visit the `FastMail Virtual Domains configuration page <fm-config_>`_ (log in
   from LastPass)

#. Use the search box to find the alias. NB: enter only the username part of the
   email address. That is, if you wish to delete info@okfn.org, just
   search for "info".

#. Click the "Del" button on the right hand side of the row containing the alias
   you wish to delete. You will see a confirmation similar to that shown above
   for alias creation.

How to search for an email address across all aliases
-----------------------------------------------------

#. The Fastmail web interface search, does not let you search for email addresses that may be part of an alias, 

#. An optional method to look for email addresses across all aliases is,
   to set the 'Aliases to display' to its maximum value.

   .. image:: aliases-display.png 

#. The 'Aliases to display' option is located at the bottom of the 'Virtual Aliases' list.

#. Once all the Aliases are displayed use CTRL+F, the browser search to find an email address or alias.


How to remove or add a user to an email alias
---------------------------------------------

#. Visit the `FastMail Virtual Domains configuration page <fm-config_>`_ (log in
   from LastPass)

#. Use the search box to find the alias. NB: enter only the username part of the
   email address. That is, if you wish to modify info@okfn.org, just
   search for "info".

#. Add a user's email or remove a user's email on on the second column, and
   click the "Save Changes" button at the bottom of the table. You will see
   a confirmation similar to that shown above for alias creation.
