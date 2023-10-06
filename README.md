Bill Of Material Server
=======================

Current Scope and Functionality
-------------------------------

This project contains a light weight nginx webserver in a docker container which is simply making board of material html pages which are created out of KiCad with the [Interactive Bill of Material](https://github.com/openscopeproject/InteractiveHtmlBom/wiki) Pluign: available via the webserver.

At the moment the tool does not do much more than providing access to a folder which contains in its subfolders the bill of material webpages for different projects. Nginx is configured in a way that it loads the ibom files as index if it finds them in a subfolder. No more additional functionality is at the moment provided.


Future extensions:
------------------

- Provide a dedicated main page, containing the projects found in the subfolders
- Provide also pictures of schematic and Board layout
- Linking to Partsbox