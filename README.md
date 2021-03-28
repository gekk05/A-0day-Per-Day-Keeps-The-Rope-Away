# A Zero Day Per Day Keeps The Rope Away

## Status 

**Start date: 3/28/2021**

**0day count: 3**

**End date: ??**

## Goal 

* Find a "0day" every day, no matter how impactful the findings are. Everything ranging from trivial open redirects to code execution will be reported. All findings will be responsibly disclosed.
* Have fun
* Learn, stay current


<h1> Findings </h1>

### WeBid 1.2.2

* Reflected XSS within *install.php* [3/28/2021]
* Authenticated file upload -> RCE within *logo_upload.php* [3/28/2021]
* Unauthenticated SQL injection within *adsearch.php* (category parameter) [3/28/2021]
