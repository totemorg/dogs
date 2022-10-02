# [DOGS](https://github.com/totemstan/dogs)

**DOGS** converts [TOTEM markdown](/api.view) to html.

## Installation

Clone **DOGS** from one of its repos:

	git clone REPO/totemstan/dogs

To start and manage **DOGS**:

	npm run start [ ? | $ | ...]	# Unit test
	npm run verminor				# Roll minor version
	npm run vermajor				# Roll major version
	npm run redoc					# Regen documentation

## Usage

Require, optionally configure and start **DOGS**:
	
	const DOGS = require("dogs").config({
		key: value, 						// set key
		"key.key": value, 					// indexed set
		"key.key.": value					// indexed append
	});

where configuration keys follow [ENUMS deep copy conventions](https://github.com/totem-man/enums)

## Program Reference
<details>
<summary>
<i>Open/Close</i>
</summary>
<a name="module_WATCHDOGS"></a>

## WATCHDOGS
Define DEBE watchdogs:

	sql => {  // watchdog
		const { ... } = site;  	// pull required site info
		// do your thing
	}

This module 
documented in accordance with [jsdoc](https://jsdoc.app/).

**Requires**: <code>module:[enums](https://github.com/totemstan/enums)</code>  
</details>

## Contacting, Contributing, Following

Feel free to 
* submit and status [TOTEM issues](http://totem.hopto.org/issues.view) 
* contribute to [TOTEM notebooks](http://totem.hopto.org/shares/notebooks/) 
* revise [TOTEM requirements](http://totem.hopto.org/reqts.view) 
* browse [TOTEM holdings](http://totem.hopto.org/) 
* or follow [TOTEM milestones](http://totem.hopto.org/milestones.view) 

## License

[MIT](LICENSE)

* * *

&copy; 2012 ACMESDS
