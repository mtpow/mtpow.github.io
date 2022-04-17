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
						I started with web development as a child. Our first PC was a used windows 98 PC from Ebay.
						I toyed around with Angelfire and started hosting a pokemon website where I taught myself
						HTML/CSS.
						<br><br>
						As I grew older, I got more involved with competitive gaming and web development. The various
						gaming teams I was apart of needed servers and websites. I happened to know a bit about these
						technologies and started hosting a few of them. This is where I further progressed my skills
						from basic HTML/CSS to JS/PHP/MySQL. I felt like I could create anything I'd need with these
						essential tools and I did. I made a competitive multi-gaming community that hosted images, forums
						and other services. It was rather successful and had thousands of hits per month.
						<br><br>
						Now I'm in school for Computer Science at Southern New Hampshire University, I would like to learn
						more about lower level languages, design patterns and object orientated programming. 
						<br><br>
						I enjoy learning new things and utilizing them. I am currently hosting a minecraft community
						at <a href="http://salvossmp.com">www.SalvosSMP.com</a> where I'm managing the server and
						editing plugins to tailor the game to foster a community that I'd want to be apart of.
						<br><br>
						You can view some of my projects on my Github or look below for some choice ones I've selected
						to show off. 
						<br>
						<br>
						Thanks for reading, Mike.
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
