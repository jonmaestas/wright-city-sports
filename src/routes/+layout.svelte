<svelte:head>
	<title>Wright City Sports</title>
	<meta
		name="description"
		content="Information and resources about the sports offered at Wright City. Wright City Sports offers baseball, softball, tball, soccer, basketball, and cheerleading."
	/>
</svelte:head>

<header>
	<article>
		<hgroup>
			<h1>Wright City Sports</h1>
			<p>Promoting Youth Sports in Our Community</p>
		</hgroup>
		<nav>
			<ul>
				<li>
					<details role="list">
						<summary aria-haspopup="listbox" role="button">Menu</summary>
						<ul role="listbox">
							<li>
								<a href="/baseball">⚾ Baseball</a>
							</li>
							<li>
								<a href="/softball">🥎 Softball</a>
							</li>
							<li>
								<a href="/basketball">🏀 Basketball</a>
							</li>
							<li>
								<a href="/cheer">📣 Cheer</a>
							</li>
							<li>
								<a href="/soccer">⚽ Soccer</a>
							</li>
							<li>
								<a href="/sponsors">Sponsors</a>
							</li>
							<li>
								<a href="/jobs">Job Openings</a>
							</li>
						</ul>
					</details>
				</li>
			</ul>
		</nav>
	</article>
</header>

<div class="container-fluid">
	<slot />
	<nav>
		<ul />
		<ul>
			<li>
				© {new Date().getFullYear()} <a href="wrightcitysports.org">WrightCitySports.org</a>
			</li>
		</ul>
		<ul />
	</nav>
</div>
