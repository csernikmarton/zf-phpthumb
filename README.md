# PHPThumb support for Zend Framework (1.X) #

This code is based on PHPThumb, located at: 
http://phpthumb.gxdlabs.com/
https://github.com/masterexploder/PHPThumb

## How to use ##

1. Copy files to your library directory

2. Initiate the code, example:

    ```php
    $image = PhpThumb_Factory::create('/path/to/the/image.jpg', array('jpegQuality' => 90));
    $image->resize(360);
    $image->save('/path/to/the/new/image.jpg');
    ```

3. Modify the parameters to fit your needs. (Original documentation: https://github.com/masterexploder/PHPThumb/wiki)

## Changelog ##

### 0.1 (March 17th 2013) ###

* Initial release