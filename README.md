<!DOCTYPE html>
<html>
<head>
	<title>Plus</title>
<link rel="stylesheet" href="turtle/res/common.css">
	<script src="turtle/res/modernizr-2.6.2.min.js"></script>
	<script src="turtle/res/texts.js"></script>
</head>
<body id="index" class="index folder top-level">

	<div id="mainbg">&nbsp;</div>
	<div id="main" role="main"><div class="container">
	<script>if (window.location.hash && window.location.hash.length) document.getElementById('main').style['display']='none';</script>
		
	<header style="background-image:url(https://images2.imgbox.com/82/58/hzoT0PMf_o.jpg);">
			<div class="pattern">
				<div class="title clearfix">
					<div class="hgroup">
						<h1>Plus</h1>
					</div>
				</div>
			</div>
		</header>
		<div class="items">
			<div class="cont load">
				<table class="thumbs"><tr>
					<td><a href="https://images2.imgbox.com/9a/97/DqI8E3ca_o.jpg" data-tooltip="#tt0"><noscript><img src="https://thumbs2.imgbox.com/9a/97/DqI8E3ca_t.jpg" width="200" height="150"></noscript><img src="turtle/res/blank.png" width="200" height="150" alt="" data-src="https://thumbs2.imgbox.com/9a/97/DqI8E3ca_t.jpg" data-ext="jpg" data-caption="<h2>Памятный Крест на Царевом Кургане</h2>"></a><div class="caption hidden" id="tt0"><span class="nr">1</span></div></td>
					<td><a href="https://images2.imgbox.com/d0/a4/3BULFn7C_o.jpg" data-tooltip="#tt1"><noscript><img src="https://thumbs2.imgbox.com/d0/a4/3BULFn7C_t.jpg" width="200" height="150"></noscript><img src="turtle/res/blank.png" width="200" height="150" alt="" data-src="https://thumbs2.imgbox.com/d0/a4/3BULFn7C_t.jpg" data-ext="jpg" data-caption="<h2>пос. Волжский - Храм в честь Рождества Христова</h2>"></a><div class="caption hidden" id="tt1"><span class="nr">2</span></div></td>
					<td><a href="https://images2.imgbox.com/6b/5e/d6gNIcv3_o.jpg" data-tooltip="#tt2"><noscript><img src="https://thumbs2.imgbox.com/6b/5e/d6gNIcv3_t.jpg" width="200" height="150"></noscript><img src="turtle/res/blank.png" width="200" height="150" alt="" data-src="https://thumbs2.imgbox.com/6b/5e/d6gNIcv3_t.jpg" data-ext="jpg" data-caption="<h2>пос. Смышляевка - Купель с Часовней у святого источника</h2>"></a><div class="caption hidden" id="tt2"><span class="nr">3</span></div></td>
					<td><a href="https://images2.imgbox.com/91/73/IlLOTwdW_o.jpg" data-tooltip="#tt3"><noscript><img src="https://thumbs2.imgbox.com/91/73/IlLOTwdW_t.jpg" width="200" height="150"></noscript><img src="turtle/res/blank.png" width="200" height="150" alt="" data-src="https://thumbs2.imgbox.com/91/73/IlLOTwdW_t.jpg" data-ext="jpg" data-caption="<h2>пос. Фёдоровка - Мемориал</h2>"></a><div class="caption hidden" id="tt3"><span class="nr">4</span></div></td>
					</tr><tr><td><a href="https://images2.imgbox.com/64/f3/LIyDe5t7_o.jpg" data-tooltip="#tt4"><noscript><img src="https://thumbs2.imgbox.com/64/f3/LIyDe5t7_t.jpg" width="200" height="150"></noscript><img src="turtle/res/blank.png" width="200" height="150" alt="" data-src="https://thumbs2.imgbox.com/64/f3/LIyDe5t7_t.jpg" data-ext="jpg" data-caption="<h2>пос. Фёдоровка - Благовещенский скит</h2>"></a><div class="caption hidden" id="tt4"><span class="nr">5</span></div></td>
					<td><a href="https://images2.imgbox.com/82/58/hzoT0PMf_o.jpg" data-tooltip="#tt5"><noscript><img src="https://thumbs2.imgbox.com/82/58/hzoT0PMf_t.jpg" width="200" height="150"></noscript><img src="turtle/res/blank.png" width="200" height="150" alt="" data-src="https://thumbs2.imgbox.com/82/58/hzoT0PMf_t.jpg" data-ext="jpg" data-caption="<h2>Свято-Богородичный мужской монастырь Казанской иконы Божьей Матери</h2>"></a><div class="caption hidden" id="tt5"><span class="nr">6</span></div></td>
				
				</tr></table>
					
			</div>
		</div>
	</div></div>
	
<script src="turtle/res/jquery-1.10.2.min.js"></script>

<script src="turtle/res/skin.min.js"></script>
<script>
	_jaWidgetBarColor='white';
	$(document).ready(function(){			
		var enableKeys=function(){return typeof _jaWidgetFocus==='undefined' || !_jaWidgetFocus;};
		var t=$('#main');
		var i=t.find('.thumbs'),f=t.find('.folders td');
		i.turtle({
			resPath:'res',relPath:'',
			albumName:'Plus',afterLast:'startover',
			licensee:'',thumbHeight:150,
			
			cols:4
		}, {  });
		
		if (!document.touchMode) {
			t.find('.items>.cont').addScroll({focusActive:!0});
		}
		$('.helplink').turtleHelp({index:!0,slide:!0});
		var al=[1,0,1,2];
		if (document.touchMode) $('.shares>a, .search>a, .parent>a').addTooltip({pos:al});
		else { $('.controls>a, .home').addTooltip({pos:al}); $('footer .showhint, .bulkactions .showhint').addTooltip(); }
		

		initMobile();
	});
	if(location.protocol!=='file:') {
	}
	
</script>

</body>
</html>
