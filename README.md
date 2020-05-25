DirectoryLister - Version 1.11
==============================

PHP Directory Listing Script (Alternative for Apache AutoIndex).
https://github.com/mikeotizels/directorylister/

Easily display files and folders in a mobile friendly, clean and cool way. 

Originally developed by Hal Gatewood.
https://halgatewood.com/free/file-directory-list/

Modified and distributed by Michael Otieno as part of Mikeotizels Open Source Project.
http://mikeotizels.orgfree.com/projects/opensource/

-------------------------------------------------------------------------------------


Requirements
------------

1. Web Server  - A web server with PHP language and MySQL database like Apache
2. Web Browser - A web browser like Chrome, Firefox, Opera, Edge, e.t.c


Installation
------------

Installing DirectoryLister is an easy task. Just follow these simple steps:

 1. **Download** the latest version from the my GitHub repository: 
      https://github.com/mikeotizels/directorylister/ 
      You should have already completed this step, but be sure you have the very latest version.

 2. **Unzip** all the DirectoryLister files on your computer.

 3. **Drop** the `index.php` file in your folder and you are ready to go.  

To test your installation, just call the following link at your website using a web browser:

    http://your-site-address/directory-lister-folder-path/


## Options 

At the top of the `index.php` file you have a few settings you can change:

--
`$dir = "";`
The directory to be scanned for file listing. NEEDS FIXING.

--
`$title = "";`

The meta title of the document and also the title of the page.

--
`$theme = "light";`

Change this variable to `dark` when you are feeling down.

--
`$icon_url = "images/flat.png";` Images folder
`$icon_url = "https://www.dropbox.com/s/lzxi5abx2gaj84q/flat.png?dl=0";` Direct link
`$icon_url = "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAA+gAAAAyCAYAAADP7vEw....";` Data image

A data sprite of evenly spaced out icons (Choose ONLY one option).  

--
`$ignore_file_list = array('.htaccess', '.htpasswd', 'Thumbs.db', '.DS_Store', 'index.php');`

Create an array of files that you do not want to appear in the listing.

--
`$ignore_ext_list = array();`

You can create an array of extensions not to show, for example: 'ico', 'jpg', 'jpeg', 'png', 'gif', 'pdf'

--
`$sort_by = "name_asc";`

This will sort the files, the available options are: name_asc, name_desc, date_asc, date_desc

--
`$ignore_empty_folders = true;`

Ability to hide empty folders.
You can turn this off by changing the value to false.

--
`$toggle_sub_folders = true;`

If a folder is clicked on, it will slide down the sub folder. 
You can turn this off by changing the value to false.

NOTE: You need to include jQuery on the page to enable the toggle function:

--
`$force_download = false;`

You can set this to true to add the html download attribute which forces the download in some browsers.


## Upgrading

DirectoryLister cannot really be "upgraded" - simply delete the old files on your 
web server, and follow the installation instructions above.


Contributing
-------------

The work is not yet complete! You are invited to get involved in the DirectoryLister
project. There are several levels of contributing:

Development - Build plugins, extensions and more to be included in DirectoryLister.       
Traslation  - Change the DirectoryLister into other languages. 
Feedback    - Report bugs and other issues, provide helpful ideas. 
Donation    - Support the DirectoryLister project.


Licensing
---------

DirectoryLister is licensed under the terms of the The MIT License.
https://opensource.org/licenses/MIT


Contacts
--------

If you would like to work with me on a project, need some litle help
or just want to say hi, I would like to here from you! You can get in
touch with me through:

Email   : mikeotizels@gmail.com
Website : http://mikeotizels.orgfree.com/contact/


------------------------------------------------------------------------

Thanks for using DirectoryLister 1.11.

Enjoy!

-------------------------------------------------------------------------
*"Built by a Developer, for a Developer. Make it Bigger and Better!"*
