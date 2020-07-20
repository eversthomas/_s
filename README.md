[![Build Status](https://travis-ci.org/Automattic/_s.svg?branch=master)](https://travis-ci.org/Automattic/_s)

different _s
===

Original: https://github.com/Automattic/_s/blob/master/README.md

* change hole sass structure

html structure:

'''html
<div id="page" class="site">
  <a class="skip-link screen-reader-text" href="#primary"></a>
    <header id="masthead" class="site-header">
      <div class="site-branding">
	<h1 class="site-title"><a href=""></a></h1>
	<p class="site-title"><a href=""></a></p>
	<p class="site-description"></p>
      </div><!-- .site-branding -->
      <nav id="site-navigation" class="main-navigation">
        <button class="menu-toggle" aria-controls="primary-menu" aria-expanded="false"></button>
	<ul><li><a></a></li></ul>
      </nav><!-- #site-navigation -->
    </header><!-- #masthead -->
    <main id="primary" class="site-main">
      <article id="post">
	<header class="entry-header">
	  <h1 class="entry-title"></h1>
	</header><!-- .entry-header -->
	<div class="entry-content">
	  <p></p>
	</div><!-- .entry-content -->
	<footer class="entry-footer">
          <p></p>
	</footer><!-- .entry-footer -->
      </article><!-- #post-<?php the_ID(); ?> -->
    </main><!-- #main -->
    <aside id="secondary" class="widget-area">
      <section id="%1$s" class="widget %2$s">
        <h2 class="widget-title"></h2>
      </section>
    </aside><!-- #secondary -->
    <footer id="colophon" class="site-footer">
      <div class="site-info">
      </div><!-- .site-info -->
    </footer><!-- #colophon -->
</div><!-- #page -->
'''

Good luck!
