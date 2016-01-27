#JQUERY SMOOTH SCROLL
In order to make your page scroll up and down smoothly using jquery, just paste the following code into your html file,
right before the “</body>”. Seriously, that’s it. You don’t need anything in the header, and you don’t need to host a
jquery file anywhere on your site. 

      <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>
  <script src="https://github.com/kswedberg/jquery-smooth-scroll/blob/master/jquery.smooth-scroll.min.js"></script>
 <script>
  $('.smooth').on('click', function() {
    $.smoothScroll({
        scrollElement: $('body'),
        scrollTarget: '#' + this.id
    });
    
    return false;
 });
 </script>
 
 
 When you click a link in your site that takes you somewhere else within the same page
it will slide smoothly.
