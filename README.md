#Ace Code Editor Module for TinyMCE WYSIWYG in Drupal

This will turn the standard HTML code editor into an Ace HTML code editor.

This module uses [Ace (Ajax.org Cloud9 Editor) v1.2.0](http://ace.c9.io/).

###Prerequisites
1. [Drupal v7](https://www.drupal.org/)
2. [wysiwyg](https://www.drupal.org/project/wysiwyg)
3. [tinymce-ace](https://github.com/sharpdressedcodes/tinymce-ace)

###Installation
1. Put the contents of the 'src' directory inside the 'sites/all/modules' directory.
2. Enable Ace inside configuration > wysiwyg profiles > tinymce (edit) > buttons and plugins.
3. Enable the Ace module inside modules > User Interface.