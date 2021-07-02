.. SPDX-License-Identifier: CC-BY-SA-4.0

============
Instructions
============

Repository Structure
====================
The root folder contains a list packages.  Under each package, there is a list
of ``tsv`` files exported from App Manager and a readme file which describes
each ``tsv`` files. For example, if ``disable_ads.tsv`` is a file, the readme
includes a list entry like below::

  - **disable_ads.tsv:** Disables all ad components from the package.

How to Contribute
=================
1. **Export blocking rules:**

   - In the app info tab of an app, clicking on the three-dots menu and then
     **Export blocking rules** (Recommended)
   - Using batch operations in the main page
   - From **Settings** > **Rules** > **Import/export blocking rules** >
     **Export**.

2. **Edit blocking rules:** Open the exported ``tsv`` file and keep only the
   rules that you want to add in this repository.

3. **Create a pull request or an issue.** Create an issue with the contents of
   the tsv along with the purpose of the rules, or clone the repository, put
   the rules file under the desired folder (based on package name), add/modify
   the readme file in the formate given above (the list should be sorted in
   ascending order) and create a merge request.


How to Use the Repository
=========================
You can download your desired files from the repository using GitHub without
cloning it. To do that,
1. Click on **Go to file** button on the right side near the **Code** button
2. Input your package name, a list of files will be displayed
3. Navigate to the file you want (or the corresponding readme file)
4. Download the desired file.

License
=======

Unless specified, everything in the repository are licensed under `Creative
Commons 4.0 ShareAlike license <https://creativecommons.org/licenses/by-sa/4.0/>`_.
