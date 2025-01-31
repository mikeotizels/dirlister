DirLister ChangeLog
===================

# 2.0.0 (2024-12-28)

- Fixed recursive directory scanning issue. Now you can list files from any 
  directory within your server document root. Initially, it only scanned the 
  files in the directory where the plugin's index.php file is placed.
  [Issue #1](https://github.com/mikeotizels/dirlister/issues/1)
- Cleaned the PHP code and modified the functions to support PHP 8.
- Modified the plugin configuration variables and added more options.
- Implemented the subfolder toggle feature in pure JavaScript and removed 
  dependency on jQuery library for the folder toggle function.
- Improved the CSS code for styling the directory listing page.

# 1.0.0 (2020-05-15)

- Initial release.