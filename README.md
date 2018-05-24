Nagios check for local SSL certificate file
===============================================

## Preface

This [Nagios](https://www.nagios.org/) check checks several aspects of the public key of a local SSL certificate file.

---

## Requirements

Required packages:

  * Python 2.6 or newer
  * [pyOpenSSL](https://github.com/pyca/pyopenssl)

---

## Command line parameters

Supported command line parameters are:

  * `-h` or `--help` - shows a brief help
  * `-e <wdays>,<cdays>` or --expires=<wdays>,<cdays> - check if the certificate expires in <wdays>/<cdays> or less
  * `-s <algo>` or `--signature-agorithm=<algo>` - check signature algorithm of public key file.
  * `-v` or `--valid` - check if certificate is valid (this is the default check if no other check is requested)

---

## License
This program is licenses under [GLPv3](http://www.gnu.org/copyleft/gpl.html).

