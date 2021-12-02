# DOGS

**DOGS** converts [TOTEM markdown](/api.view) to html.

## Installation

Clone **DOGS** from one of its repos:

	git clone https://github.com/totemstan/dogs
	git clone https://sc.appdev.proj.coe/acmesds/dogs
	git clone https://gitlab.west.nga.ic.gov/acmesds/dogs

## Manage 

	npm test [ ? || T1 || T2 || ...]	# Run unit test
	npm run redoc						# Update repo

## Usage

Require, configure and start **DOGS**:
	
	const DOGS = require("dogs");

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


* [WATCHDOGS](#module_WATCHDOGS)
    * [.repos()](#module_WATCHDOGS.repos)
    * [.daily()](#module_WATCHDOGS.daily)
    * [.weekly()](#module_WATCHDOGS.weekly)
    * [.system()](#module_WATCHDOGS.system)
    * [.detectors()](#module_WATCHDOGS.detectors)
    * [.bricks()](#module_WATCHDOGS.bricks)
    * [.catalog()](#module_WATCHDOGS.catalog)
    * [.licenses()](#module_WATCHDOGS.licenses)
    * [.voxels()](#module_WATCHDOGS.voxels)
    * [.cache()](#module_WATCHDOGS.cache)
    * [.jobs()](#module_WATCHDOGS.jobs)
    * [.email()](#module_WATCHDOGS.email)
    * [.clients()](#module_WATCHDOGS.clients)
    * [.news()](#module_WATCHDOGS.news)
    * [.notebooks()](#module_WATCHDOGS.notebooks)
    * [.users()](#module_WATCHDOGS.users)

<a name="module_WATCHDOGS.repos"></a>

### WATCHDOGS.repos()
Repository watchdog

**Kind**: static method of [<code>WATCHDOGS</code>](#module_WATCHDOGS)  
<a name="module_WATCHDOGS.daily"></a>

### WATCHDOGS.daily()
Daily watchdog to distribute email updates

**Kind**: static method of [<code>WATCHDOGS</code>](#module_WATCHDOGS)  
<a name="module_WATCHDOGS.weekly"></a>

### WATCHDOGS.weekly()
Weekly watchdog to distribute email updates

**Kind**: static method of [<code>WATCHDOGS</code>](#module_WATCHDOGS)  
<a name="module_WATCHDOGS.system"></a>

### WATCHDOGS.system()
System health and utilization watchdog

**Kind**: static method of [<code>WATCHDOGS</code>](#module_WATCHDOGS)  
<a name="module_WATCHDOGS.detectors"></a>

### WATCHDOGS.detectors()
Detector training stats watchdog

**Kind**: static method of [<code>WATCHDOGS</code>](#module_WATCHDOGS)  
<a name="module_WATCHDOGS.bricks"></a>

### WATCHDOGS.bricks()
Data brick ingesting watchdog

**Kind**: static method of [<code>WATCHDOGS</code>](#module_WATCHDOGS)  
<a name="module_WATCHDOGS.catalog"></a>

### WATCHDOGS.catalog()
Reserved watchdog for building mater catalogs

**Kind**: static method of [<code>WATCHDOGS</code>](#module_WATCHDOGS)  
<a name="module_WATCHDOGS.licenses"></a>

### WATCHDOGS.licenses()
Watchdog for monitoring code licenses

**Kind**: static method of [<code>WATCHDOGS</code>](#module_WATCHDOGS)  
<a name="module_WATCHDOGS.voxels"></a>

### WATCHDOGS.voxels()
Watchdog for monitoring data voxels

**Kind**: static method of [<code>WATCHDOGS</code>](#module_WATCHDOGS)  
<a name="module_WATCHDOGS.cache"></a>

### WATCHDOGS.cache()
Watchdog for monitoring data cache

**Kind**: static method of [<code>WATCHDOGS</code>](#module_WATCHDOGS)  
<a name="module_WATCHDOGS.jobs"></a>

### WATCHDOGS.jobs()
Watchdog for monitoring notebook jobs

**Kind**: static method of [<code>WATCHDOGS</code>](#module_WATCHDOGS)  
<a name="module_WATCHDOGS.email"></a>

### WATCHDOGS.email()
Watchdog for monitoring email

**Kind**: static method of [<code>WATCHDOGS</code>](#module_WATCHDOGS)  
<a name="module_WATCHDOGS.clients"></a>

### WATCHDOGS.clients()
Watchdog for monitoring client profiles

**Kind**: static method of [<code>WATCHDOGS</code>](#module_WATCHDOGS)  
<a name="module_WATCHDOGS.news"></a>

### WATCHDOGS.news()
Watchdog for creating system news

**Kind**: static method of [<code>WATCHDOGS</code>](#module_WATCHDOGS)  
<a name="module_WATCHDOGS.notebooks"></a>

### WATCHDOGS.notebooks()
Watchdog for monitoring notebook usage

**Kind**: static method of [<code>WATCHDOGS</code>](#module_WATCHDOGS)  
<a name="module_WATCHDOGS.users"></a>

### WATCHDOGS.users()
Watchdog for monitoring system users

**Kind**: static method of [<code>WATCHDOGS</code>](#module_WATCHDOGS)  
</details>

## Contacting, Contributing, Following

Feel free to 
* submit and status **DOGS** issues (
[WWW](http://totem.zapto.org/issues.view) 
[COE](https://totem.west.ile.nga.ic.gov/issues.view) 
[SBU](https://totem.nga.mil/issues.view)
)  
* contribute to **DOGS** notebooks (
[WWW](http://totem.zapto.org/shares/notebooks/) 
[COE](https://totem.west.ile.nga.ic.gov/shares/notebooks/) 
[SBU](https://totem.nga.mil/shares/notebooks/)
)  
* revise **DOGS** requirements (
[WWW](http://totem.zapto.org/reqts.view) 
[COE](https://totem.west.ile.nga.ic.gov/reqts.view) 
[SBU](https://totem.nga.mil/reqts.view), 
)  
* browse **DOGS** holdings (
[WWW](http://totem.zapto.org/) 
[COE](https://totem.west.ile.nga.ic.gov/) 
[SBU](https://totem.nga.mil/)
)  
* or follow **DOGS** milestones (
[WWW](http://totem.zapto.org/milestones.view) 
[COE](https://totem.west.ile.nga.ic.gov/milestones.view) 
[SBU](https://totem.nga.mil/milestones.view)
).

## License

[MIT](LICENSE)

* * *

&copy; 2012 ACMESDS
