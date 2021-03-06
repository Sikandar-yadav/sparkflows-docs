SAML OneLogin setup
==============

Below are steps to setup SAML 2.0 OneLogin

1. Create an account at one Login 
2. SignIn into oneLogin


.. figure:: ../../_assets/authentication/oneLoginSignIn.png
   :alt: sso
   :width: 60%
	   
3. Go to administrator >> Click on applications menu >> 

.. figure:: ../../_assets/authentication/applications_menu.png
   :alt: sso
   :width: 60%
	   
4. Add an app

.. figure:: ../../_assets/authentication/addAppButton.png
   :alt: sso
   :width: 60%
   
5. Select an application::

    Search application 'SAML Test Connector'
    Select the application SAML Test Connector (Advanced).
      
.. figure:: ../../_assets/authentication/searchApp.png
   :alt: sso
   :width: 60%
	    
6. Input an application name and save it.

.. figure:: ../../_assets/authentication/saveApp.png
   :alt: sso
   :width: 60%
   
7. Configure the newly created app and add below information::

    Audience (EntityID)
    Recipient
    ACS (Consumer) URL Validator*
    ACS (Consumer) URL*
    Single Logout URL
    Login URL
	   
.. figure:: ../../_assets/authentication/configuration.png
   :alt: sso
   :width: 60%
