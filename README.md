# deprecated-zend-loader-class

## About

Beta versions of the upcoming Zend Framework 2 contain a class called ``\Zend\Loader``, which is a remnant from ZF1, is deprecated and will be removed before the final release.  However, a number of other components, in current beta versions of Zend Framework 2, reference this file/class.  The Zend Framework team has made their own Composer repository available as of the Beta 4 release, but no package (this includes zend-loader) includes ``\Zend\Loader``.  This package provides this file, with a Composer definition that will make sure the class is accessible using the generated autoload script in your project.
