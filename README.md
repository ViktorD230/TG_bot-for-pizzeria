# TG_bot-for-pizzeria

Bot for pizzeria implemented in telegram

The bot is implemented through aiogram library 

To work with the bot you need to insert your bot key instead of TOKEN or create .env and create a variable there.

The bot is configured to moderate a group of piceries where it will monitor the order, and has the ability to register admins. Which are the admins of the group or founders through the command /admin.

Bot is built on FSM machines simplifies the organization of complex dialogs and sequences of actions in the bot.
It also provides structured and easily maintainable code.

The bot implements management of 2 bases SQLite and PostgreSQL. The basic version for working with SQLite is saved, for working with PostgreSQL the code is commented, you can choose which one you like more.

The bot implements transfer of orm sqlalchemy sessions through middleware layer to the bot's aiogram handler. Also multilevel bot system.
