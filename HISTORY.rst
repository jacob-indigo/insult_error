Insult Error Change Log
=======================

v0.2.1
------

-  Added insults from XKCD "code quality" series, with attribution
-  Some of these new insults are commented out until a future date when
   we have more non-XKCD insult to balance them out.

v0.2.0
------

-  Overhauled implementation to make everything much simpler
-  Fixed "bug" that prevented showing different error classes when user
   called raise with Insult error class, not instance
-  Fixed crummy workaround where users had to use a special list in
   try-except clauses
-  Changed to a 1-10 rating system, which made it easier to assign
   ratings and easier to use them

v0.1.1
------

-  New insults contributed by Nick Weir
-  Added InsultErrors tuple to support try-except clauses for all
   InsultError classes

v0.1.0
------

First release
