(function($){
	$.fn.extend({
		"goTop":function(option){
			//传参使代码更灵活
				var DEFAULT = {
					"speed":1000,
					"showHeight":50
				};
				var setting=$.extend(DEFAULT,option);
				  
			this.each(function(index,element){
				$(window).scroll(function(){
				var st=$(window).scrollTop();
				if(st>=100){
					$(element).show()
				}else{
					$(element).hide()
				}
			});
				$(element).on("click",function(){
					$("body").animate({"scrollTop":0},2000);
				});
				
			})
		}
	})
})(jQuery);
