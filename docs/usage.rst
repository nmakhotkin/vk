
Usage
=====

API class
---------

You need instance of API class.

.. autoclass:: vk.API

Make requests
-------------

 .. code:: python

    >>> import vk
    >>> vkapi = vk.API()
    >>> vkapi.getServerTime()

 .. code:: python

    >>> import vk
    >>> vkapi = vk.OAuthAPI(user_login='andrew@gmail.com', user_password='***', app_id='appid')
    >>> vkapi.wall.get(count=1)

All API methods that can be called from server should be supported.
See https://vk.com/dev/methods for detailed API help.
