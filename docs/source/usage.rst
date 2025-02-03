Authentication
==============

To use the PrivacyDocs API you need to obtain the authentication key. 
When a user logs in using the `PrivacyDocs login screen <https://app.privacydocs.eu/?cmd=login>`_ then a link containing single-use short-lived token is emailed to the email address of the user registered with PrivacyDocs.
When the user click the link this single-use token is exchanged for the authorization key that has a much longer TTL. This key should be used in REST requests.


A few common `questions regarding signing in are answered on the PrivacyDocs help page <https://privacydocs.eu/en/docs.html#accordion_accounts>`_.
We recommend creating a special user with appropriate permissions as described in the PrivacyDocs `collaborate feature <https://privacydocs.eu/en/collaborate.html>`_ and use this user for automated REST requests.


Reading Data
============

Reading your data is a common use case of the REST API.

To fetch all data visiable to the user, make a GET request to `the PrivacyDocs VIEW endpoint <https://app.privacydocs.eu/api/view>`_ and parse the JSON output.


Fair Use
========

PrivacyDocs is provided as a services aimed on human users, and the use of automatic scripts that overload the services is prohibited (see the `PrivacyDocs Terms of Service <https://privacydocs.eu/en/ts.html>`_.
You are expected to make infrequent REST requests that are compatible with fair use of the system.
Such as making daily backups.

