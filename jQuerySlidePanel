/*
 * jQuery Slide Panel
 * http://panel.gearedgraphic.com
 *
 * Copyright 2013, Geared Graphic
 * Free to use and abuse under the MIT license.
 * http://www.opensource.org/licenses/mit-license.php
 */
$(document).ready(function() {
   

$("a[data-toggle]").on("click", function(e) {
  e.preventDefault();  // prevent navigating
  var selector = $(this).data("toggle");  // get corresponding element
  $("div.slider").hide();
  $(selector).slideToggle('slow')
});

$('span.close').click(
    function(){
        $(this).closest('.slider').slideUp(1000);
    });
});
