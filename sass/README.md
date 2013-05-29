SASS structure
==============


The aim, to provide a clear delineation of CSS separation as to make development and management of the code base as understandable and consistent as can be accomplished.


Modules
-------
This directory is for reusable objects that you've built for your project.

Partials
--------
This directory is built to house like sections of code. Examples could include: typography, grids, etc.

Vendor
------
The vendor directory is built to house CSS modules and partials or libraries that are not of your making. In this way you can section off pre-built styles as to make updating them easier to manage. 

Large projects
--------------
It may be prudent for large projects to build off this structure and adopt a structure as seen below:

SectionA
  - modules
  - partials
  - vendor

SectionB
  - modules
  - partials
  - vendor
