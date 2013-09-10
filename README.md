# Description

A simple animated counter, accepts numbers or strings

# Requirements

<p>JQuery 1.7 or later</p>

# Example
[View Examples](http://kCounter.kudoslabs.co.uk)

# Usage & Examples

### inlcude jquery and kcounter (optionally jquery ui)
    <script src="//ajax.googleapis.com/ajax/libs/jquery/1.8.3/jquery.min.js"></script>
    <script src="//ajax.googleapis.com/ajax/libs/jqueryui/1.9.2/jquery-ui.min.js"></script>
    <script src="/path/to/kcounter.js"></script>

### html
`<div id="example">12345</div>`

### initialise (uses element contents)
`$('#example').kCounter() ;`

### initialise with options
`$('#example').kCounter({ initial: 54321 }) ;`
    
### update the counter
`$('#example').kCounter('update', 12345) ;`


# Available options and defaults
<pre>
'height'         : 50, // The default height of an individual counter
'width'          : 50, // The default width of an individual counter
'initial'        : false // Override the element content if desired,
'easing'		 : 'swing' // [swing,linear] unless using easing plugin (Jquery UI)
'duration'       : 'fast' // [slow,fast,integer value]
</pre>
