API
===

`PrivacyDocs <https://privacydocs.eu>`_ is designed as a standard single-page webapp, with the front-end accessible from the PrivacyDocs user interface <https://app.privacydocs.eu> and the back-end accissible through `https://app.privacydocs.eu/api`.

The back-end accepts REST GET and PUT requests with JSON payload to return JSON back.

It uses the `pdauthorization` HTTP header bearing `Bearer <KEY>` where the `<KEY>` is assigned during user authentication process. 
Demo users are using pre-defined language-specific keys `DEMO-en`, `DEMO-de`, etc.

