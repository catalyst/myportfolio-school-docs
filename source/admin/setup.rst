Setting up your school on MyPortfolio
-----------------------------------------------------

Congratulations on wanting to use MyPortfolio. Here you can find more information on setting up your school once you have access to MyPortfolio. We'll provide information on setting up accounts to deciding on settings for your school.

Register your school
~~~~~~~~~~~~~~~~~~~~~~~~~

If your school is not yet registered on MyPortfolio, you can register it within a couple of minutes. Just fill in the `registration form <http://myportfolio.school.nz/registration.php>`_ and send it off. A site administrator will review your request and set up your school if it does not already exist on MyPortfolio. You will receive the following from the support team:

#. Email confirming the registration of your school.
#. Your account details so that you can start working with MyPortfolio.

  .. note::
    The person who registers a school becomes the administrator for that school automatically. They can appoint other or additional administrators later on.

#. Invitations to two groups that may be of interest:

  * **"MyPortfolio Discussions" group**: The main group on MyPortfolio for support. You can connect with other educators, ask questions (both pedagogical and technical).
  * **"MyPortfolio Administrators" group**: Group for school administrators for specific questions. Often, "MyPortfolio Discussions" is used these days for that.

Currently, MyPortfolio is provided for free by the Ministry of Education to New Zealand schools. If you are unsure if you qualify, please send us an `email <support@myportfolio.school.nz>`_ and we will discuss your request further.

Once your school is set up on MyPortfolio, you can start using it straight away. However, we recommnd that you look into account creation more closely as well as reviewing the settings for your school.

Decide on account creation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You have several options for creating accounts for your students and teachers. The following are the main options available to schools:

#. **Manual account creation**: Set up accounts one at a time. This is good if you only set up one account every few days. Otherwise, use the bulk account creation. Check the Mahara user manual for `more information on how to create accounts manually <http://manual.mahara.org/en/1.10/administration/users.html#add-user>`_.
#. **Bulk account creation**: If you need to set up several accounts at once and don't use an external authentication method, create accounts via a CSV file. Check the Mahara user manual for `more information on how to create accounts in bulk <http://manual.mahara.org/en/1.10/administration/users.html#add-and-update-users-by-csv>`_.
#. **Single sign-on** (via SAML): If you use SSO at your school (see the `Identity and Access Management website <https://sites.google.com/site/schoolsiamsso/>`_), you can allow your students and teachers to use their regular logins also for MyPortfolio. Check the Mahara user manual for the `details that the site administrator would need from you in order to set up SSO <http://manual.mahara.org/en/1.10/administration/institutions.html#saml-authentication>`_.

  .. note::
    SSO is often used in conjunction with automatic account creation via Moodle. If you do not use Moodle, you should create accounts in bulk with the SSO information so that your users don't need to register individually.

#. **Moodle**: If you use Moodle, you can `set up MNet <http://manual.mahara.org/en/1.10/administration/institutions.html#xml-rpc-mnet-authentication>`_ in order to log in to MyPortfolio. This allows you to:

  * Log in to MyPortfolio via Moodle.
  * Transfer content from Moodle to MyPortfolio.
  * Use the `Mahara assignment submission plugin <https://moodle.org/plugins/view/assignsubmission_mahara>`_ (if installed on Moodle) for portfolio assessment.

#. **LDAP / Active Directory**: If you have your users in LDAP / Active Directory, this can be hooked up to MyPortfolio and you can even do user and group sync. Check the Mahara user manual for the `details that the site administrator would need from you in order to set up LDAP / AD <http://manual.mahara.org/en/1.10/administration/institutions.html#ldap-authentication>`_.

.. seealso::
  You could also use `Persona <http://manual.mahara.org/en/1.10/administration/institutions.html#persona-authentication>`_ authentication, but students may be too young for that or you may not wish to set it up because the school cannot do user account creation in bulk.
