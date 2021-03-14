
Bëåñß Reminders
====
Bëåñß Reminders is a Django app to conduct web-based reminders. Visitors can input their contact details,
their reminder, and the date + time of reminder.

Quick start
-----------

1. Add "mysite" and "reminders" to your library

2. Include the reminders URLconf in your project urls.py like this::

    path('reminders/', include('reminders.urls')),

3. Run ``python manage.py migrate`` to create the reminders models.

4. Start the server by running ``python manage.py runserver``

5. Visit http://127.0.0.1:8000/reminders/ to enter a reminder.

