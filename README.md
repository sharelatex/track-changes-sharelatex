track-changes-sharelatex
========================

An API for converting raw editor updates into a compressed and browseable history.

[![Build Status](https://travis-ci.org/sharelatex/track-changes-sharelatex.png?branch=master)](https://travis-ci.org/sharelatex/track-changes-sharelatex)

Acceptance tests can be run with the command
```
AWS_BUCKET=<bucket-name> AWS_ACCESS_KEY_ID=<aws-access-key> AWS_SECRET_ACCESS_KEY=<aws-secret-access-key> make test
```
where `bucket-name`, `aws-access-key` and `aws-secret-access-key` are the credentials for an AWS S3 bucket.




License
-------

The code in this repository is released under the GNU AFFERO GENERAL PUBLIC LICENSE, version 3. A copy can be found in the `LICENSE` file.

Copyright (c) ShareLaTeX, 2014.
