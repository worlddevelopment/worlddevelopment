Development standards
===

Why standards
---
A multifaceted development of such large scale and so many different technologies, software and hardware modules all interacting and depending on each other requires solutions to tough problems like verdicts against single source principle and thus information redundancy that is easy to diverge easily which leads to conflicts as to know which is the most recent version.

When imagining this happening thousands of times, the tremendous scale of the problem becomes apparent.

Therefore to allow effective, consistent and steady world development fixing such issues required thinking power of several years.



The standards
---

Adhering to the following standards partly or entirely fixes most development issues, therefore ensures automatic, consistent, consequent development without data entropy getting out of control:


###Global

* [Every part its own `<part>`.blend grouped as "Group" => Fulfill single source principle, Automate dependency, URI reference handling](https://github.com/faerietree/multimachine_lightspeed_precise/issues/1)

* [Only stable parameters like e.g. dimensions, IDs in URI / file names. Prevent price, URL, ...](https://github.com/faerietree/gears_maedler/issues/1)

* [Give values in SI units and omit the unit](https://github.com/faerietree/universal_prototyping_kit/issues/4)

* [Reference at least one real world part in the URI / file name. Keep it at the end directly before the ending.](https://github.com/faerietree/universal_prototyping_kit/issues/5)

* [Use basic KB template for `<part>`.blend](https://github.com/faerietree/universal_prototyping_kit/issues/6)

* [Reasons for why to depend on an existing part instead of generating it for every project.](https://github.com/worlddevelopment/worlddevelopment/issues/3)


###Project internal
1. Group group instances that are linked.
**=>** Allows exchanging a part by another internal, linked part by redefining which objects are in the group.

1. Prefix 'Assembly' to groups that use parts (as group instances of the group that contains the instance of the linked group).
**=>** This way checking in which assemblies a part is used in the outliner is just a matter of searching within all prefixed groups for the group name of the part.
**Tip:** Search for the group name. Then scan the 'Assembly'-prefixed matches manually.

1. Keep linked boolean data blocks that are added at times when linking, instancing a group.
**=>** Allows to easily adapt the hole pattern by making these duplicates real, single user and repositioning, et alia. Including these satellite objects in the group (see 1.) may not be wise.



