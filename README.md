# Digital-Locker
The project's major goal is to develop a low-cost multi user
authentication system that provides trustworthy security. It's simple to
create, cost-effective in application, the right size for installation, uses less
active power, and is both robust and accurate.
The authentication system will contain two keypads: one for entering
the password and one for the administrator to specify the desired
password. In the keypad, a user can select a user number (such as user1,
user2, etc.).
We utilized a 3-digit hexadecimal number as our password to make it
more difficult to choose a password at random, giving us a total of 4096
potential options without forcing the user to memorize long passwords.
Furthermore, any three consecutive incorrect tries will cause the
alarm system to start buzzing and stop when the system is reset via the
admin interface, making our password based lock system extremely
trustworthy.
We utilized a simple bit by bit comparator to compare the configured
password with the input password, which compares every bit of the output
from the keypad which uses a hexadecimal to binary converter.
If the user's input matches the pre-set input, the user is granted
access. Any incorrect password will trigger the counter, and if the number
of incorrect attempts reaches 3, an alert will be triggered. Our security
system will be more reliable and user-friendly as a result of its design.
