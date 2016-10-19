sa-tarsnap
==========

[![Build Status](https://travis-ci.org/softasap/sa-tarsnap.svg?branch=master)](https://travis-ci.org/softasap/sa-tarsnap)


Tarsnap is a secure online backup service for UNIX-like operating systems, including BSD, Linux and OS X. Created in 2008 by Colin Percival, Tarsnap encrypts and stores data in Amazon S3. The service is designed for efficiency, only uploading and storing data that has directly changed since the last backup.[2] Its security keys are known only to the user.
It was developed and debugged, with input solicited from bug-bounty hunters, to try to find vulnerabilities. An inadvertent yet serious nonce-reuse vulnerability was found by this process and fixed in 2011.


Example of usage (all parameters are optional)

Simple

```
  roles:
    - {
        role: "sa-tarsnap"
      }
```

Advanced:

```
  roles:
    - {
        role: "sa-tarsnap",
        tarsnap_version: "1.0.37"
      }
```




Copyright and license
---------------------

Copyright 2016 - Vyacheslav Voronenko

Code licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) or the [MIT License] (http://opensource.org/licenses/MIT).

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)
