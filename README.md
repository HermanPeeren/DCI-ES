DCI-ES
======
Explore the combination of DCI with Event Sourcing (using PHP)

Money Transfer example
----
explore without using external libraries (Broadway, Doctrine, Nooku).
* data is represented by a stream of events
* behaviour is functional

Roles are static classes: containing (static) functions. Roles have no state, so allright if the classes are static: http://verraes.net/2014/06/when-to-use-static-methods-in-php/