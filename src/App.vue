<template>
  <div id="app">
    <!-- / Site Header -->
	<div class="site-header">
		<!-- / Site Logo -->
		<div class="site-logo">
			<a href="" style="width:67px; height:30px">
				<!--<img style="width: 67px;" src="static/images/mln_colorful.png" />-->
				<img src="static/fonts/mln.svg" style="width: 60px;" alt="molunong">
			</a>
		</div>
		<!-- \ Site Logo -->

		<!-- / Site Menu -->
		<!--<div class="site-menu">
			<div class="icon"></div>
			<div class="menu">
				<ul>
					<li><a href="index.html">Portfolio</a></li>
					<li><a href="about.html">About</a></li>
					<li><a href="portfolio-single.html">Portfolio Single</a></li>
					<li><a href="blog.html">Blog / News</a></li>
					<li><a href="blog-single.html">Blog Single</a></li>
					<li><a href="contact.html">Contact</a></li>
					<li><a href="shortcodes.html">Shortcodes</a></li>
				</ul>
			</div>
		</div>-->
		<!-- \ Site Menu -->

		<!-- / Site Description -->
		<h1>
			小时候天真的以为全世界都喜欢我，长大后才知道<br><br>——是全宇宙！
		</h1>
		<!-- \ Site Description -->

		<!-- / Site Footer -->
		<div class="site-footer">
			<div class="site-social">
				<ul>
					<li><i class="pe-so-dribbble pe-lg pe-va" style="color:#ff78f4"></i></li>
					<li><i class="pe-so-facebook pe-lg pe-va" style="color:#ff78f4"></i></li>
					<li><i class="pe-so-twitter pe-lg pe-va" style="color:#ff78f4"></i></li>
				</ul>
			</div>

			<p>© 2017 Monica</p>
			<!--<p>HTML Theme by <a href="http://themeraid.com">ThemeRaid</a></p>-->
		</div>
		<!-- \ Site Footer -->

	</div>
	<!-- \ Site Header -->


	<!-- \ Site Main -->
	<div class="site-main">
    <router-view></router-view>
	</div>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
/*#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}*/
</style>
