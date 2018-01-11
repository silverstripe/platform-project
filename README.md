## Overview

Base project for SilverStripe Platform:

 * [`framework`](http://github.com/silverstripe/silverstripe-framework): Module including the base framework
 * [`cms`](http://github.com/silverstripe/silverstripe-cms): Module including a Content Management System
 * [`dynamodb`](https://github.com/silverstripe/silverstripe-dynamodb): DynamoDB session handling
 * `themes/simple` (optional)

## Installation ##

```bash
composer create-project silverstripe/platform-project /path/to/local/site
```

Once installed, copy `.env.example` to `.env` and update with your relevant values - this should _not_ be committed up, and as such is in the `.gitignore` file.

To use the SilverStripe 3 version of the project, use:

```bash
	composer create-project silverstripe/platform-project /path/to/local/site 3.0.1
```

## Bugtracker ##

Bugs are tracked on github.com ([framework issues](https://github.com/silverstripe/silverstripe-framework/issues),
[cms issues](https://github.com/silverstripe/silverstripe-cms/issues)).
Please read our [issue reporting guidelines](http://doc.silverstripe.org/framework/en/misc/contributing/issues).

## License ##

	Copyright (c) 2007-2013, SilverStripe Limited - www.silverstripe.com
	All rights reserved.

	Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

	    * Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
	    * Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the
	      documentation and/or other materials provided with the distribution.
	    * Neither the name of SilverStripe nor the names of its contributors may be used to endorse or promote products derived from this software
	      without specific prior written permission.

	THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
	IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE
	LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE
	GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT,
	STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY
	OF SUCH DAMAGE.
