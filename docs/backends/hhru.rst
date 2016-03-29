Hhru
====

Hhru OAuth v2 for Authentication.

- Register a new application at the `Hhru API`_, and

- Add instagram backend to ``AUTHENTICATION_SETTINGS``::

      AUTHENTICATION_SETTINGS = (
        ...
        'social.backends.instagram.InstagramOAuth2',
        ...
      )


- Fill ``Client Id`` and ``Client Secret`` values in the settings::

      SOCIAL_AUTH_HHRU_OAUTH2_KEY = ''
      SOCIAL_AUTH_HHRU_OAUTH2_SECRET = ''


.. _Hhru API: https://dev.hh.ru/
