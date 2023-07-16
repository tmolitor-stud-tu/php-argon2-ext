# php-argon2-ext
php argon2 extension as used by kwo

This is based upon commit 098883c33f1f0eaf01b27b8314d4ef198c23b744 of https://github.com/charlesportwoodii/php-argon2-ext/

Strangely, though, something must be different, because only this tar.gz allows the 'salt' option to be used to specify a custom salt in argon2_hash()

## Usage:
Just unpack php-argon2-ext.tar.gz, cd into it and run build.sh which will build and install the argon2 extension
