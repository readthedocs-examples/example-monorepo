# Example of a monorepo setup on Read the Docs

This project demonstrates having multiple `.readthedocs.yaml` files in the same repository in order to host nested documentation subprojects on Read the Docs.

You can read about the feature here:

https://docs.readthedocs.io/en/stable/guides/setup/monorepo.html

The feature is new (read: experimental).

This is an example of a Monorepo with 3 projects.
Each project isn't highly developed nor pretty.

main
----

This is the "main" project that nests other subprojects.
It uses the latest version of Sphinx.

blog
----

Completely different type of project.
Builds with Sphinx 5.x.

docusaurus
----------

Configured to be added as a subproject with alias "docusaurus"
