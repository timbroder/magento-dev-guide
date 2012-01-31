#WIP
##Index

* [Introduction](#introduction)

* ####[Coding Style](#codingstyle)
* [PHP File Formatting](#phpfileformating)
* [Naming Conventions](#namingconventions)


###<a name="phpfileformating">PHP File Formatting</a>
.php and .phtml files should not contain the closing tag:

```php
?>
```

__4 spaces__ should be used for indentation, no tabs

The target line length should be __80 charactes__. The maximum line length of any line should be 120 characters

###<a name="namingconventions">Naming Conventions</a>
Class names map to the directory location in which they are stored. 
For a local Product Model class located at app/code/local/Ai/Catalog/Model/Product.php the classname would be Ai_Catalog_Model_Product.
Numbers in class names are permited but are frowned upon, try to stick with only letters and underscores.

Abstract classes and Interfaces must and with their respective names: Ai_Catalog_Model_ProductAbstract or Ai_Catalog_Model_ProductInterface

When naming .php files; alphanumeric characters, underscores, and dashes are allowed. Spaces are prohibited.

Method names may only contain alphanumeric characters. Only use numbers when absolutely needed.  Try to be descriptive in method names. Ex:

```php
filterInput()
getElementById()
```