reCaptcha-PHP-5 (v1.0)
==========================

A properly coded PHP 5 reCaptcha class that will allow you to interact with Google's
reCaptcha API.

* 100% phpDocumentator 2 coverage
* 100% PSR-2 code standard coverage

Feel free to extend and modify it to fit your frameworks / applications needs.

Usage
-----

Please see Examples directory for a simple run down of functionality.

Notes
-----

- If you are using name space loader, you should remove 'require' lines within Captcha.php file. 
- The functionality is based on $_POST requests by default, you can modify it (fairly easy) to take
$_GET or whatever you want instead.
- It will always send remote address from $_SERVER['REMOTE_ADDR'] variable if you are behind Vagrant/etc, please update it
(or write a setter to set remote address on the fly :))