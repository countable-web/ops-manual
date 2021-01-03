File Storage and Organization
=============================

::: {.toctree maxdepth="2" caption="Contents:" hidden=""}
:::

**Purpose**

To enable anyone to find any file or asset, without having to ask the
person who created it where it is.

**Scope**

This page makes it clear where all work is saved, and gives more
granular instructions regarding Google Drive file organization.

Why We Need Organized Storage
-----------------------------

-   devs need to find sliced versions of assets.
-   clients and other team members need to find mock-ups (such as XD
    links) and know which is the most recent version.
-   artists need to find raw project files in order to be able to take
    over each others\' work.

Every file we create should have one obvious place that it is stored. If
there seem to be 2 or more options as to where a file is stored, we
should clarify our process.

List of Storage Locations
-------------------------

We should store things only in the places and ways described below.

  ------------------------------------------------------------------------------------
  System                                 What Goes Here         Who Has Access
  -------------------------------------- ---------------------- ----------------------
  GitHub - this repo                     Document how and why   Everyone in the world
                                         we do things           

  Miro                                   Mockups, visual        The specific client
                                         content                and project staff

  GitHub                                 Open source code       Everyone in the world

  Trello                                 Work requests, tasks.  The specific client
                                         Never store work       and project staff
                                         deliverables here,     
                                         only links to Google   
                                         Drive                  

  Bitbucket                              Private source code    The specific client
                                                                and project staff

  Google Drive [                         Private client files   The specific client
  ]{.title-ref}/clients/\<client sl      (such as artwork)      and project staff
  ug\>/\<project slug\>\`\` folder                              

  [Google Drive                          Private company data   Our staff
  ]{.title-ref}[/team/]{.title-ref}[     (minimize this)        
  fold er \<https://drive.go                                    
  ogle.com/drive/folde                                          
  rs/12iWzlcOP\_qdFlVcM                                         
  \_U1yLVKB6IDq4Uvd\>]{.title-ref}\_\_                          

  [Google Drive                          Any public assets      Everyone in the world
  ]{.title-ref}[/public/]{.title-ref}[   (maximize this)        
  fold er \<https://drive.go                                    
  ogle.com/drive/folde                                          
  rs/1Do2l9oaPHlyJ-J6w                                          
  -BoGAvUmJjK1mDk3\>]{.title-ref}\_\_                           

  Google Drive (your own folders)        Never store anything   You
                                         here                   

  Your local computer                    No more than one       You
                                         day\'s work            
  ------------------------------------------------------------------------------------

Never share work directly in Slack by uploading it. Only share links to
things stored in the correct place in Google Drive.

Folder Structure on Google Drive
--------------------------------

The intention of this standard is to have one obvious folder in Google
Drive that any file belongs in. We want to minimize the cases where
there is ambiguity on where to save or retrieve a file.

### General Guidelines

-   Our work should be organized based on how how it\'s used. For
    example, artwork will typically need an editable copy for
    developers.
-   The goal is to be able to find the things we need quickly. Things we
    use more often should take fewer clicks.
-   Make sure your work is stored in a way that is convenient for those
    who will be using it.
-   When a file is no longer needed, outdated, or otherwise more likely
    to confuse than help, move it to a folder named \_archive in the
    same directory.
-   If an additional folder is needed, create the additional folder and
    name it according to the naming structure.
-   As a rule of thumb, when looking at a folder\'s contents it should
    be clear what\'s there at a glance. Ideally, there should be about 5
    to 10 items in a folder. If it\'s much more, make logical
    subfolders. There are exceptions to this rule, but in general it
    will make our heirarchy more navigable.

Storing Non Code Assets
-----------------------

Official versions of Non-code assets are stored on Google Drive

Every client has a folder in our Company Google Drive named:

/clients/

### Standard Folders

-   When creating a new project in Google Drive, copy the template
    linked
    [HERE](https://drive.google.com/drive/u/0/folders/19uOpYepddtD_fsheccNiAdTOPYYaAymg?ddrp=1)

It is based on Felipe\'s folder design schema (attached) and [this
article](https://pixeldreams.com/blog/best-practices-folder-structure/)

![Countable Web Production, File Organization
Tree](https://github.com/fepirata/final-exam-special-topics/blob/master/public/cwp_file_organization_tree_v01.jpg?raw=true)

  --------------------------------------------------------------------------------------------------------------------------
  Folder                                                       What Goes Here         Description
  ------------------------------------------------------------ ---------------------- --------------------------------------
  `/cli ents/<client slug>`                                    projects folders for   [official client slug \<https:
                                                               this client.           //docs.google.com/sp
                                                                                      readsheets/d/11IvCJC
                                                                                      tw0iD4vWEOY\_tNMvpUnt
                                                                                      e2eb1Z3exMMtevIzk/ed
                                                                                      it\#gid=279543225\>]{.title-ref}\_\_

  [ ]{.title-ref}/clients/\<client sl ug\>/\<project           projects folders for   [official client slug \<https:
  slug\>\`\`                                                   this client.           //docs.google.com/sp
                                                                                      readsheets/d/11IvCJC
                                                                                      tw0iD4vWEOY\_tNMvpUnt
                                                                                      e2eb1Z3exMMtevIzk/ed
                                                                                      it\#gid=279543225\>]{.title-ref}\_\_

  `/clients/<client  slug>/<project slug >/01_preproduction`   these are inputs to    
                                                               the project that       
                                                               existed beforehand.    

  `/clients/ <client slug>/<proje ct slug>/02_design`          raw project files      
                                                               designers work on.     

  `/clients/< client slug>/<projec t slug>/03_reviews`         exported work to show  Recommended: Adobe XD links, saved in
                                                               the client.            a Google Doc

  `/clients/ <client slug>/<proje ct slug>/04_assets`          Sliced outputs for     PNG and SVG files, separated so they
                                                               developers to take.    can be positioned dynamimcally

  `/clients/<c lient slug>/<project  slug>/05_feedback`        New data and           Usability tests
                                                               information gained as  
                                                               part of the project    
  --------------------------------------------------------------------------------------------------------------------------

Naming Convention
-----------------

### Folders

The naming convention for folder have the following structure:

![Countable Web Production, Naming Structure guide for
folders](https://github.com/fepirata/final-exam-special-topics/blob/master/public/cwp_naming_guide_folder_v03.jpg?raw=true)

### Files

The files follow a similar structure, the main difference is that files
have versioning section in the end of the name:

![Countable Web Production, Naming Structure guide for
files](https://github.com/fepirata/final-exam-special-topics/blob/master/public/cwp_naming_guide_file_v01.jpg?raw=true)

### Guidelines for naming structure

-   Replace spaces and dashes by underlines. E.g.: cpw-donut icon =\>
    cwp\_donut\_icon
-   Always try to use short desccriptions unless is necessary to be more
    descriptive.
-   Be consistent with your own naming structure. E.g.: if you have a
    series of icons, don\'t name them: cwp\_icon\_pizza,
    cwp\_burger\_icon, cwp\_hotdog. Instead of that, keep one pattern:
    cwp\_pizza\_icon, cwp\_burger\_icon, cwp\_hotdog\_icon.

### Guidelines for folder structure

Sometimes it\'s necessary to create additional folders, so a simple
series of questions were made to help you to decided if you need an
additional folder or not:

-   Are there 10+ files and it makes sense to nest them into other
    folders? *Create a folder*
-   Do the files have really distinct content, i.e., doesn\'t make sense
    to keep two files together? *Create a folder*
-   Do you need to update a project with a complete new version? *Create
    a folder*
-   Is the project small and focused? (e.g. a single page project) *Do
    NOT create a folder*

### Nice-to-Have when you organize the folder structure

-   There\'s no rule for uppercase or lowercase words, but if you are in
    doubt, go for lowercase.
-   The versioning is not mandatory for all the files, like documents
    where most of the time there\'s just one version of each file.
    However, if a second version is created, it needs to be named with
    the versioning section in the end.
-   The five main folders follow a color structure, which visually helps
    us to guide through the folders. It\'s good to keep the color
    pattern whenever possible. ![Countable Web Production, folder color
    example](https://github.com/fepirata/final-exam-special-topics/blob/master/public/cwp_file_structure_folder_color_example.png)

### Example: Countable Marketing Folder

TODO: make this follow the convention fully.

[Example
folder](https://drive.google.com/drive/folders/1iPhpEg1RuEz_ki4yNgzSOg9Z257Mpa7x?usp=sharing)

All the old files are in there, but they\'ve been organized into the
following categories:

1.  cwp\_logo: in this folder exists our most up-to-date logo, its
    styleguide, and an \_archive folder which houses all previous
    versions.
2.  cwp\_marketingassets: this folder has a lot of content - any
    individual assets that have been created for marketing purposes
    (business cards, social media profile images and banners, brochures,
    signage, video, team bios, CV, proposals, etc) AND their working
    files.
3.  cwp\_marketing: this folder includes a folder for our blog and a
    folder for various tradeshows and other marketing events.
4.  cwp\_website: another big one! This folder includes all of
    countable.ca\'s web design files, content strategy, and assets,
    including sliced images and the logo files specifically used for the
    website.

### Sharing

For each client, this folder (and all its\' contents) is shared with the
following people and no others.

-   The client\'s designated staff who we are working with, and showing
    our work to.
-   Our staff who perform work for that client.

### Structure

-   /clients//Mockups should contain all drafts and revisions of mockups
    for clients to approve and developers to work from. Make it obvious
    which is the latest one, by deleting old ones when a new one comes
    available.
-   /clients//Assets should container all sliced imaages and other raw
    assets for developers to include in their code projects.

### Countable Marketing Folder

Here\'s the share link to our google drive cwp\_marketing
[folder](https://drive.google.com/drive/folders/1iPhpEg1RuEz_ki4yNgzSOg9Z257Mpa7x?usp=sharing)

All the old files are in there, but they\'ve been organized into the
following categories:

1.  cwp\_logo: in this folder exists our most up-to-date logo, its
    styleguide, and an \_archive folder which houses all previous
    versions.
2.  cwp\_marketingassets: this folder has a lot of content - any
    individual assets that have been created for marketing purposes
    (business cards, social media profile images and banners, brochures,
    signage, video, team bios, CV, proposals, etc) AND their working
    files.
3.  cwp\_marketing: this folder includes a folder for our blog and a
    folder for various tradeshows and other marketing events.
4.  cwp\_website: another big one! This folder includes all of
    countable.ca\'s web design files, content strategy, and assets,
    including sliced images and the logo files specifically used for the
    website.

It is based on Felipe\'s folder design schema (attached) and [this
article](https://pixeldreams.com/blog/best-practices-folder-structure/)

### Miro

Miro is a great tool but the art boards can get messy quickly. General
guidelines to keep us productive: - Store everything in project folders.
Every client should have exactly one folder, and you should invite the
relevant team members to that folder. Do NOT make different folders per
project, or save things in the root folder, if you want to share them
with the team. - Name your artboards clearly. You can put a lot in one
art board, and that\'s often better than having many small art boards.
As a rule fo thumb, create one art board per project epic (major
activity the group works together on, such as a substantial user
interface) - For mock-ups. Please put them in frames (such as the
browser frame). Label each page clearly in the frame title (ie, in CRUD
notation like \"Widget List\"). Use arrows to indicate navigation
between frames.
