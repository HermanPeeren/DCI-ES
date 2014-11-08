DCI-ES
======
Explore the combination of Contextual Encapsulation (inspired by DCI) with Event Sourcing (ES) using PHP.

Disclaimer: although I called this repo DCI-ES and I'm certainly inspired by DCI, I have no claims at all that my investigations
are "proper DCI" as intended by the core DCI-developers. I call this part **Contextual Encapsulation**.

See https://groups.google.com/forum/#!topic/object-composition/DcD8QH2linA

Money Transfer example
----
* data is represented by a stream of events
* behaviour is functional

Roles are static classes: containing (static) functions. Roles have no state: http://verraes.net/2014/06/when-to-use-static-methods-in-php/

Infrastructure used for ES:
* Broadway: https://github.com/qandidate-labs/broadway 