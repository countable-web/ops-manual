File Storage and Organization
=============================

.. toctree::
   :maxdepth: 2
   :caption: Contents:
   :hidden:

**Purpose**

To enable anyone to find any file or asset, without having to ask the person who created it where it is. 

**Scope**

This page makes it clear where all work is saved, and gives more granular instructions
regarding Google Drive file organization.


Why We Need Organized Storage
-----------------------------

-  devs need to find sliced versions of assets.
-  clients and other team members need to find mock-ups (such as XD links) and know which is the most recent version.
-  artists need to find raw project files in order to be able to take over each others' work.

Every file we create should have one obvious place that it is stored. If there seem to be 2 or more options as to where a file is stored, we should clarify our process.

List of Storage Locations
-------------------------

We should store things only in the places and ways described below.

+----------------------+----------------------+----------------------+
| System               | What Goes Here       | Who Has Access       |
+======================+======================+======================+
| GitHub - this repo   | Document how and why | Everyone in the      |
|                      | we do things         | world                |
+----------------------+----------------------+----------------------+
| GitHub               | Open source code     | Everyone in the      |
|                      |                      | world                |
+----------------------+----------------------+----------------------+
| Trello               | Work requests,       | The specific client  |
|                      | tasks. Never store   | and project staff    |
|                      | work deliverables    |                      |
|                      | here, only links to  |                      |
|                      | Google Drive         |                      |
+----------------------+----------------------+----------------------+
| Bitbucket            | Private source code  | The specific client  |
|                      |                      | and project staff    |
+----------------------+----------------------+----------------------+
| Google Drive         | Private client files | The specific client  |
| `                    | (such as artwork)    | and project staff    |
| `/clients/<client sl |                      |                      |
| ug>/<project slug>`` |                      |                      |
| folder               |                      |                      |
+----------------------+----------------------+----------------------+
| `Google Drive        | Private company data | Our staff            |
| ``/team/``           | (minimize this)      |                      |
| fold                 |                      |                      |
| er <https://drive.go |                      |                      |
| ogle.com/drive/folde |                      |                      |
| rs/12iWzlcOP_qdFlVcM |                      |                      |
| _U1yLVKB6IDq4Uvd>`__ |                      |                      |
+----------------------+----------------------+----------------------+
| `Google Drive        | Any public assets    | Everyone in the      |
| ``/public/``         | (maximize this)      | world                |
| fold                 |                      |                      |
| er <https://drive.go |                      |                      |
| ogle.com/drive/folde |                      |                      |
| rs/1Do2l9oaPHlyJ-J6w |                      |                      |
| -BoGAvUmJjK1mDk3>`__ |                      |                      |
+----------------------+----------------------+----------------------+
| Google Drive (your   | Never store anything | You                  |
| own folders)         | here                 |                      |
+----------------------+----------------------+----------------------+
| Your local computer  | No more than one     | You                  |
|                      | day's work           |                      |
+----------------------+----------------------+----------------------+

Never share work directly in Slack by uploading it. Only share links to
things stored in the correct place in Google Drive.

Folder Structure on Google Drive
--------------------------------

The intention of this standard is to have one obvious folder in Google Drive that any file belongs in. We want to minimize the cases where there is ambiguity on where to save or retrieve a file.

General Guidelines
~~~~~~~~~~~~~~~~~~

-  Our work should be organized based on how how it's used. For example, artwork will typically need an editable copy for developers.
-  The goal is to be able to find the things we need quickly. Things we use more often should take fewer clicks.
-  Make sure your work is stored in a way that is convenient for those who will be using it.
-  When a file is no longer needed, outdated, or otherwise more likely to confuse than help, move it to a folder named \_archive in the same directory.
-  If an additional folder is needed, create the additional folder and name it according to the naming structure.

Standard Folders
~~~~~~~~~~~~~~~~

-  When creating a new project in Google Drive, copy the template linked `HERE <https://drive.google.com/drive/u/0/folders/19uOpYepddtD_fsheccNiAdTOPYYaAymg?ddrp=1>`__

It is based on Felipe's folder design schema (attached) and
`this article <https://pixeldreams.com/blog/best-practices-folder-structure/>`__

|Countable Web Production, File Organization Tree|

+----------------------+----------------------+----------------------+
| Folder               | What Goes Here       | Description          |
+======================+======================+======================+
| ``/cli               | projects folders for | `official client     |
| ents/<client slug>`` | this client.         | slug <https:         |
|                      |                      | //docs.google.com/sp |
|                      |                      | readsheets/d/11IvCJC |
|                      |                      | tw0iD4vWEOY_tNMvpUnt |
|                      |                      | e2eb1Z3exMMtevIzk/ed |
|                      |                      | it#gid=279543225>`__ |
+----------------------+----------------------+----------------------+
| `                    | projects folders for | `official client     |
| `/clients/<client sl | this client.         | slug <https:         |
| ug>/<project slug>`` |                      | //docs.google.com/sp |
|                      |                      | readsheets/d/11IvCJC |
|                      |                      | tw0iD4vWEOY_tNMvpUnt |
|                      |                      | e2eb1Z3exMMtevIzk/ed |
|                      |                      | it#gid=279543225>`__ |
+----------------------+----------------------+----------------------+
| ``/clients/<client   | these are inputs to  |                      |
|  slug>/<project slug | the project that     |                      |
| >/01_preproduction`` | existed beforehand.  |                      |
+----------------------+----------------------+----------------------+
| ``/clients/          | raw project files    |                      |
| <client slug>/<proje | designers work on.   |                      |
| ct slug>/02_design`` |                      |                      |
+----------------------+----------------------+----------------------+
| ``/clients/<         | exported work to     | Recommended: Adobe   |
| client slug>/<projec | show the client.     | XD links, saved in a |
| t slug>/03_reviews`` |                      | Google Doc           |
+----------------------+----------------------+----------------------+
| ``/clients/          | Sliced outputs for   | PNG and SVG files,   |
| <client slug>/<proje | developers to take.  | separated so they    |
| ct slug>/04_assets`` |                      | can be positioned    |
|                      |                      | dynamimcally         |
+----------------------+----------------------+----------------------+
| ``/clients/<c        | New data and         | Usability tests      |
| lient slug>/<project | information gained   |                      |
|  slug>/05_feedback`` | as part of the       |                      |
|                      | project              |                      |
+----------------------+----------------------+----------------------+

Naming Convention
-----------------

Folders
~~~~~~~

The naming convention for folder have the following structure:

|Countable Web Production, Naming Structure guide for folders|

Files
~~~~~

The files follow a similar structure, the main difference is that files
have versioning section in the end of the name:

|Countable Web Production, Naming Structure guide for files|

Guidelines for naming structure
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

-  Replace spaces and dashes by underlines. E.g.: cpw-donut icon =>
   cwp_donut_icon
-  Always try to use short desccriptions unless is necessary to be more descriptive.
-  Be consistent with your own naming structure. E.g.: if you have a series of icons, don't name them: cwp_icon_pizza, cwp_burger_icon, cwp_hotdog. Instead of that, keep one pattern: cwp_pizza_icon, cwp_burger_icon, cwp_hotdog_icon.

Guidelines for folder structure
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Sometimes it's necessary to create additional folders, so a simple series of questions were made to help you to decided if you need an additional folder or not:

-  Are there 10+ files and it makes sense to nest them into other folders? *Create a folder*
-  Do the files have really distinct content, i.e., doesn't make sense to keep two files together? *Create a folder*
-  Do you need to update a project with a complete new version? *Create a folder*
-  Is the project small and focused? (e.g. a single page project) *Do NOT create a folder*

Nice-to-Have when you organize the folder structure
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

-  There's no rule for uppercase or lowercase words, but if you are in doubt, go for lowercase.
-  The versioning is not mandatory for all the files, like documents where most of the time there's just one version of each file. However, if a second version is created, it needs to be named with the versioning section in the end.
-  The five main folders follow a color structure, which visually helps us to guide through the folders. It's good to keep the color pattern whenever possible. |Countable Web Production, folder color example|

Example: Countable Marketing Folder
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

TODO: make this follow the convention fully.

`Example folder <https://drive.google.com/drive/folders/1iPhpEg1RuEz_ki4yNgzSOg9Z257Mpa7x?usp=sharing>`__

All the old files are in there, but they've been organized into the following categories:

1. cwp_logo: in this folder exists our most up-to-date logo, its styleguide, and an \_archive folder which houses all previous versions.
2. cwp_marketingassets: this folder has a lot of content - any individual assets that have been created for marketing purposes (business cards, social media profile images and banners, brochures, signage, video, team bios, CV, proposals, etc) AND their working files.
3. cwp_marketing: this folder includes a folder for our blog and a folder for various tradeshows and other marketing events.
4. cwp_website: another big one! This folder includes all of countable.ca's web design files, content strategy, and assets, including sliced images and the logo files specifically used for the website.

.. |Countable Web Production, File Organization Tree| image:: https://github.com/fepirata/final-exam-special-topics/blob/master/public/cwp_file_organization_tree_v01.jpg?raw=true
.. |Countable Web Production, Naming Structure guide for folders| image:: https://github.com/fepirata/final-exam-special-topics/blob/master/public/cwp_naming_guide_folder_v03.jpg?raw=true
.. |Countable Web Production, Naming Structure guide for files| image:: https://github.com/fepirata/final-exam-special-topics/blob/master/public/cwp_naming_guide_file_v01.jpg?raw=true
.. |Countable Web Production, folder color example| image:: https://github.com/fepirata/final-exam-special-topics/blob/master/public/cwp_file_structure_folder_color_example.png


Storing Non Code Assets
-----------------------

Official versions of Non-code assets are stored on Google Drive

Every client has a folder in our Company Google Drive named:

/clients//

Sharing
~~~~~~~

For each client, this folder (and all its' contents) is shared with the
following people and no others.

-  The client's designated staff who we are working with, and showing
   our work to.
-  Our staff who perform work for that client.

Structure
~~~~~~~~~

-  /clients//Mockups should contain all drafts and revisions of mockups
   for clients to approve and developers to work from. Make it obvious
   which is the latest one, by deleting old ones when a new one comes
   available.
-  /clients//Assets should container all sliced imaages and other raw
   assets for developers to include in their code projects.

Countable Marketing Folder
~~~~~~~~~~~~~~~~~~~~~~~~~~

Here's the share link to our google drive cwp_marketing
`folder <https://drive.google.com/drive/folders/1iPhpEg1RuEz_ki4yNgzSOg9Z257Mpa7x?usp=sharing>`__

All the old files are in there, but they've been organized into the
following categories:

1. cwp_logo: in this folder exists our most up-to-date logo, its
   styleguide, and an \_archive folder which houses all previous
   versions.
2. cwp_marketingassets: this folder has a lot of content - any
   individual assets that have been created for marketing purposes
   (business cards, social media profile images and banners, brochures,
   signage, video, team bios, CV, proposals, etc) AND their working
   files.
3. cwp_marketing: this folder includes a folder for our blog and a
   folder for various tradeshows and other marketing events.
4. cwp_website: another big one! This folder includes all of
   countable.ca's web design files, content strategy, and assets,
   including sliced images and the logo files specifically used for the
   website.

It is based on Felipe's folder design schema (attached) and
`this article <https://pixeldreams.com/blog/best-practices-folder-structure/>`__
