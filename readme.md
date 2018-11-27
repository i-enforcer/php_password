# PHP Password interface

> Easy interface for generating a hash for a plain text password. Type a plain text password and get his password_hash() hash.

**For the maximum security, use the Argon2 hashing algorithm and for this reason, requires a least PHP 7.2**

Notes:

1. The function used is `password_hash()` which is native in PHP, therefore there are no dependencies with an external library.
2. The password in plain text is sent to the server since the hash is done by PHP. Nothing is stored of course on the server but make sure you're using a SSL connection i.e. the https protocol so everything is encrypted before being sent by your browser.

## Table of Contents

- [Install](#install)
- [Usage](#usage)
- [License](#license)

## Install

Clone this repository or just get a copy of the <a href="https://raw.githubusercontent.com/cavo789/php_password/master/index.php" target="_blank noreferrer noopener">index.php</a> and store the file, f.i., on your localhost.

You can also use the [interface online](https://www.avonture.be/php_password) without installing anything.

## Usage

Just type a password in the text box and click on the `Hash` button.

You'll then obtain the generated hash and, also, a PHP sample code for showing you how to use the hash.

![Interface](images/interface.png)

## License

[MIT](LICENSE)
