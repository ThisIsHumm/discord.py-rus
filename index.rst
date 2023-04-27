.. discord.py documentation master file, created by
   sphinx-quickstart on Fri Aug 21 05:43:30 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Добро пожаловать в discord.py
===========================

.. image:: /images/snake.svg
.. image:: /images/snake_dark.svg

discord.py современная, легкая к использованию, многофункцианальная и асинхронная готовая оболочка API
для дискорда.

**Функции:**

- современный питонический API с использованием ``async``\/``await`` синтаксиса
- разумная обработка ограничения скорости, которая предотвращает 429s
- расширение команды для помощи в создании бота
- легко использовать с объектно-ориентированным дизайном
- оптимизирована как по скорости, так и по памяти

Начало
-----------------

Это твой первый раз использования библиотеки? Это место, чтобы начать!

- **Первые шаги:** :doc:`intro` | :doc:`быстрый старт` | :doc:`logging`
- **Работа с Discord:** :doc:`discord` | :doc:`intents`
- **Примеры:** множество примеров доступны в :resource:`repository <examples>`.

Помощь
--------------

Если у тебя с чем-то проблемы, эти ресурсы могут помочь.

- Try the :doc:`faq` first, it's got answers to all common questions.
- Ask us and hang out with us in our :resource:`Discord <discord>` server.
- If you're looking for something specific, try the :ref:`index <genindex>` or :ref:`searching <search>`.
- Report bugs in the :resource:`issue tracker <issues>`.
- Ask in our :resource:`GitHub discussions page <discussions>`.

Extensions
------------

These extensions help you during development when it comes to common tasks.

.. toctree::
  :maxdepth: 1

  ext/commands/index.rst
  ext/tasks/index.rst

Manuals
---------

These pages go into great detail about everything the API can do.

.. toctree::
  :maxdepth: 1

  api
  interactions/api
  discord.ext.commands API Reference <ext/commands/api.rst>
  discord.ext.tasks API Reference <ext/tasks/index.rst>

Meta
------

If you're looking for something related to the project itself, it's here.

.. toctree::
  :maxdepth: 1

  whats_new
  version_guarantees
  migrating