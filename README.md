# PHP QRCode Library test

To install this library please follow the next steps:

## Install the library using `composer`:

Add the required module to your `composer.json` file:

    {
        "require": {
            ...
            "chailong/phpqrcode": "dev-master"
            ...
        }
    }

Then run the command `composer update`.


## Usage

Sample code:

    \PHPQRCode\QRcode::png("Test", "/tmp/qrcode.png", 'L', 4, 2);
    \PHPQRCode\QRcode::jpg("Test", "/tmp/qrcode.png", 'L', 4, 2);
    \PHPQRCode\QRcode::jpeg("Test", "/tmp/qrcode.png", 'L', 4, 2);
