# deprecated-zend-loader-class

## About

Beta versions of the upcoming Zend Framework 2 up to Beta 4 inclusive (it was removed for Beta 5) contained a class called ``\Zend\Loader``, which was a remnant from ZF1.  However, a number of other components, in current beta versions of Zend Framework 2, referenced this file/class.  The Zend Framework team made their own Composer repository available as of the Beta 4 release, but no package (this includes zend-loader) included ``\Zend\Loader``.  This package provides this file, with a Composer definition that will make sure the class is accessible using the generated autoload script in your project.
