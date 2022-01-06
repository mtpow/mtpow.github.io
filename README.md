<html>
	<head>
		<title>Michael Powell - Portfolio</title>
		<link rel="stylesheet" href="reset.css">
		<link rel="stylesheet" href="styles.css">
		<link rel="preconnect" href="https://fonts.googleapis.com">
		<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
		<link href="https://fonts.googleapis.com/css2?family=Cinzel+Decorative&family=Open+Sans&family=Poppins:wght@100;400&family=Source+Code+Pro:wght@200&family=UnifrakturMaguntia&display=swap" rel="stylesheet">
		</head>
	<body>
		<div id="container">
			<div id="left">
					<div id="head">
			<h1><span class="bold">Mike</span></br>Powell</h1>
		</div>
				<ul id="nav">
					<li><a href="#jump-about">About</a></li>
					<li><a href="#jump-skills">Skills</a></li>
					<li><a href="#jump-projects">Projects</a></li>
					<li><a href="#jump-utilities">Utilities</a></li>
					<li><a href="http://github.com/mtpow">Github</a></li>
				</ul>
			</div>
			<div id="right">
				<div class="content">
					<h1 id="jump-about">About</h1>
					<p>
						The first time I ever touched anything related to coding was in the late 90s, when I was 10 years old.
						I started a Pokemon website on Angelfire. Since then, it's been 20 years and I continue to learn and grown
						in the ways of web development. I've picked up a few new languages and have been programming pretty 
						consistently over the years, always learning. 
						<br /><br />
						My first real website was a multigaming community back in 2006
						for the game Unreal Tournament 2004. It had a lot of cool features like a gallery and message board, it was
						pretty popular and netted over 5k hits per month and had hundreds of users. That was when I really fell in
						love with web design, being able to create and foster a community and see people utilize it.
						<br /> <br/>
						Since then I've been learning more about Object Orientated Programming, front end technologies like Javascript 
						and it's frameworks, and the Docker/Linux stack. I always seem to be able to pick up a new language relatively
						easily, from DM(a C based language an open source game I play is programmed in) to things like PHP or Autoit.
						I'm a firm believer in the right tool for the job and I'm ever increasing my toolset.
					</p>
				</div>
				<div class="content">
					<h1 id="jump-skills">Skills</h1>
					<div class="skill">
						<div class="outline">
							<div class="bar" style="width: 95%; "><h1>HTML/CSS</h1></div>
						</div>
					</div>
					<div class="skill">
						<div class="outline">
							<div class="bar" style="width: 75%; "><h1>Javascript</h1></div>
						</div>
					</div>
					<div class="skill">
						<div class="outline">
							<div class="bar" style="width: 90%; "><h1>PHP</h1></div>
						</div>
					</div>
					<div class="skill">
						<div class="outline">
							<div class="bar" style="width: 85%; "><h1>SQL</h1></div>
						</div>
					</div>
					<div class="skill">
						<div class="outline">
							<div class="bar" style="width: 70%; "><h1>OOP</h1></div>
						</div>
					</div>
					<div class="skill">
						<div class="outline">
							<div class="bar" style="width: 80%; "><h1>Version Control (Git etc.)</h1></div>
						</div>
					</div>
					<div class="skill">
						<div class="outline">
							<div class="bar" style="width: 70%; "><h1>Linux (Solus)</h1></div>
						</div>
					</div>
					<div class="skill">
						<div class="outline">
							<div class="bar" style="width: 80%; "><h1>Docker</h1></div>
						</div>
					</div>
					<div class="skill">
						<div class="outline">
							<div class="bar" style="width: 80%; "><h1>Package Manager (Composer)</h1></div>
						</div>
					</div>
				</div>
				<div class="content">
					<h1 id="jump-projects">Projects</h1>
					<div class="project">
						<h1><span class="demonic">Demonic</span></h1>
						<p>Demonic is an upcoming browser based 2d sprited roguelike in a grim dark setting. It has character creation, random generated loot, levels and enemies, a full crafting system, skill system and much more.</p>
						<span class="link">Link: <a href="#">Demonic</a></span><br />
						<span class="tech">Technologies Utilized: HTML, CSS, Javascript, SQL, PHP, Sockets</span>
					</div>
					<div class="project">
						<h1><span class="revival">Revival</span></h1>
						<p>Revival is a platform for competitive gamers to compete in classic games that aren't in the spotlight anymore. It features a ladder system, tournies, profiles, message boards, prizes and supports multiple games.</p>
						<span class="link">Link: <a href="#">Revival</a></span><br />
						<span class="tech">Technologies Utilized: HTML, CSS, SQL, PHP</span>
					</div>
				</div>
				<div class="content">
					<h1 id="jump-utilities">Utilities</h1>
					<div class="project">
						<h1 class="utility">Robusto</h1>
						<p>An advanced hotkey targetting program for the game Space Station 13.</p>
						<span class="link">Link: <a href="https://github.com/mtpow/Robusto">Robusto</a></span><br />
						<span class="tech">Technologies Utilized: Autoit</span>
					</div>
					<div class="project">
						<h1 class="utility">GenGet</h1>
						<p>Generates a persistent static link to a dynamic thread on the site 4chan.</p>
						<span class="link">Link: <a href="https://github.com/mtpow/GenGet">GenGet</a></span><br />
						<span class="tech">Technologies Utilized: PHP</span>
					</div>
				</div>
				<div class="content">
					<div style="height: 500px; "></div>
				</div>
			</div>
		</div>
		<script>
			window.onscroll = function() {myFunction()};
			var navbar = document.getElementById("left");
			var sticky = navbar.offsetTop;
			function myFunction() {
				if (window.pageYOffset >= sticky) {
					navbar.classList.add("sticky")
				} else {
					navbar.classList.remove("sticky");
				}
			}
		</script>
	</body>
</html>
