jQuery Tokeninput: A Tokenizing Autocomplete Text Entry
=======================================================

Overview
--------
Allow add id for custom entry.

I make small change from this brand: https://github.com/loopj/jquery-tokeninput/pull/291

Thanks for traceoutdoor to make jQuery Tokeninput can add custom entry.

Init sample
--------
$('#inputTokenId').tokenInput('/my/url/', {

'allowCustomEntry' : true

'parseCustomEntryID': function(name){
  
  //get custom entry id from it's name
  
  return "{" + name + "}";
  
}

});


Original Project
--------
Tokeninput is a jQuery plugin which allows your users to select multiple items from a predefined list, using autocompletion as they type to find each item. You may have seen a similar type of text entry when filling in the recipients field sending messages on facebook.

Documentation, Features and Demos
---------------------------------
Full details and documentation can be found on the project page here:

<http://loopj.com/jquery-tokeninput/>
