Sentry Lark 
=========================================

Plugin for Sentry which allows sending notification via `Lark <https://feishu.cn/>`_ messenger.

Presented plugin tested with Sentry from 8.9 to 9.1.2.

    **DISCLAIMER**: Sentry API is under development and `is not frozen <https://docs.sentry.io/server/plugins/>`_.

Installation
------------

1. Install this package

.. code-block:: bash

    pip install sentry-lark

2. Restart your Sentry instance.
3. Go to your Sentry web interface. Open ``Settings`` page of one of your projects.
4. On ``Integrations`` (or ``Legacy Integrations``) page, find ``Lark Notifications`` plugin and enable it.
5. Configure plugin on ``Configure plugin`` page.

   See `Documentation <https://getfeishu.cn/hc/en-us/articles/360024984973-Use-Bots-in-group-chat>`_ to know how to create ``Bot Webhook``.

6. Done!
