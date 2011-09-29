Bookmarklets:
-------------

Drag the link to your bookmark bar : 

* [show only cards](javascript:(function () {$('.js li').hide();$('[data-type=card]').show();$('.js').ajaxComplete(function(e){$('.js li').hide();$('[data-type=card]').show()});}());) -- `This will show only card creation`
