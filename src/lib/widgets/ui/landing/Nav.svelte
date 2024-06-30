<script>
	const links = [
		{
			title: 'App',
			href: '/app'
		},
		{
			title: 'Features',
			href: '#features'
		},
		{
			title: 'Scenarios',
			href: '#scenarios'
		},
		{
			title: 'F.A.Q.',
			href: '#faq'
		},
		{
			title: 'Contact',
			href: '#contact'
		},

	]
</script>

<section class="nav_wrapper">
	<div
		role="banner"
		class="nav_component w-nav"
	>
		<section class="section-banner5 hide">
			<div class="container-large">
				<div class="banner5_component is-feet">
					<div class="banner5_content">
						<div class="text-color-white">
							Lorem Ipsum is simply dummy text of the printing and typesetting industry.
						</div>
					</div>
					<a
						href="/"
						class="banner5_close-button w-inline-block"
					>
						<img
							src="images/icon_close-banner.svg"
							loading="lazy"
							alt=""
							class="invert"
						/>
					</a>
				</div>
			</div>
		</section>
		<div class="nav_container">
			<a href="/" class="nav_logo-link w-inline-block w--current">
				<img
					src="images/logos/heritage-stories.svg"
					loading="lazy"
					sizes="(max-width: 991px) 100px, 120px"
					alt="THE Heritage Stories Logo"
					class="nav_logo"
				/>
			</a>
			<nav role="navigation" class="nav_menu w-nav-menu">
				<div class="div-block-4">
					{#each links as link}
						<a href="{link.href}" class="nav_link w-nav-link">{link.title}</a>
					{/each}
				</div>
			</nav>
			<div class="nav_menu-button w-nav-button">
				<div class="nav_menu-icon">
					<div class="nav_menu-icon-bar" />
					<div class="nav_menu-icon-bar" />
					<div class="nav_menu-icon-bar" />
				</div>
			</div>
		</div>
	</div>
	<div class="nav_blank-space" />
</section>
