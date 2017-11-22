<!-- Background color of nav when scrolling the page jQuery -->

var a = $(".main-nav").offset().top;

		$(document).scroll(function(){
		    if($(this).scrollTop() > a)
		    {   
		       $('.main-nav').css({"background":"#525c6f"});
		    } else {
		       $('.main-nav').css({"background":"transparent"});
		    }
		});
