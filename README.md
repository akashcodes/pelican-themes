# Some themes I created for use with Pelican.

I use __basic1__ theme for [my website](https://akash.codes).

&nbsp;

Assuming you have a working website and you want to switch from the default theme.

&nbsp;

To use a theme with Pelican, first copy the theme folder (eg - __basic1__) to __Pelican_Project_Root/themes/__. You can also download one of the many themes from the [official repository](https://github.com/getpelican/pelican-themes). You can also learn how to create your own theme [here](http://docs.getpelican.com/en/3.6.3/themes.html)
&nbsp;

Now spicify which theme to use into your `pelicanconf.py`.

<pre><code># To use basic1 theme
# Path to theme to be used
THEME = "themes/basic1"
</code></pre>

&nbsp;

Regenerate website using `make html`. The new theme must now be applied to your website.