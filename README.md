# Use the following JavaScript in Storyline


// Script that appends scripts to body of Storyline file

var appendBody = '<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script><script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/crypto-js/3.1.9-1/crypto-js.min.js"></script><script type="text/javascript" src="xapiwrapper.min.js"></script><script src="xapi.js"></script>';

// Append the header with the code contained in the variable

$('body').append(appendBody);


// Statement function without results field
sendStatement('http://adlnet.gov/expapi/verbs/experienced','experienced','http://example.com/activity-id','main page','in accordion example');
