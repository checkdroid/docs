Test Execution and Reporting
====================================================

With CheckDroid, you can easily manage your test execution with multiple device cloud providers. Test 

Google Cloud Test Lab
---------------------

For running tests on CTL under your account, you can create a service account
on the developer console and upload the configuration to "Integrations" under
the CheckDroid dashboard.

Detailed Steps:

* Visit the Google Cloud Developer Console and navigate to Permissions > Service Account. `Direct Link <https://console.cloud.google.com/permissions/serviceaccounts/>`_
* Create a new Service Account. Make sure you select "Furnish a new private key" option. Save the key in JSON format.
* Login to the `CheckDroid App <https://app.checkdroid.com/>`_ and select "Integrations" on the sidebar.
* You can select the default configuration that is used to run the tests.


Amazon Device Farm
------------------

* Create a new IAM account and give it access to Device Farm
* Upload the account ACCESS_ID_KEY and SECRET_KEY under Integrations


Integrations coming soon:
-------------------------

* TestDroid Cloud
* TestObject
* Sauce Labs