# H5FullscreenPage
## Doc
H5FullscreenPage.init(options);

options:(default)

<pre>
{
    'type' : 1,
    'pageShow' : function(page){},
    'pageHide' : function(page){},
    'useArrow' : true,
    'useAnimation' : true,
    'useMusic' : {
        'autoPlay' : true,
        'loopPlay' : true,
        'src' : 'http://mat1.gtimg.com/news/2015/love/FadeAway.mp3'
    }
 };
</pre>
####type
This value have 8 types[1-8], every type has the different scroll animation, you can change it for yourself.
####pageShow
After every page into the screen this function will run and give a param to this page dom.
####pageHide
After every page out the screen this function will run and give a param to this page dom.
####useArrow
Is use arrow or not.
####useAnimation
Is use part animation or not.
####useMusic
Is use music or not ,if not use put this value to null.