<script>
	import {navigation} from '$shared';
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
					{#each navigation as link}
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


<style>
.nav_menu{
    align-items:center;
    font-weight:600;
    display:flex
}

.nav_menu-icon{
    width:50px;
    height:50px;
    cursor:pointer;
    flex-direction:column;
    justify-content:center;
    padding:12px 8px 8px;
    display:flex;
    overflow:hidden
}
.nav_menu-icon-bar{
    width:100%;
    height:2px;
    background-color:#000;
    margin-bottom:6px
}

@media screen and (max-width:991px){
    .nav_menu{
		display: none;
        /* z-index:2147483647;
        width:100vw;
        height:100vh;
        background-color:#ffecd9;
        justify-content:center;
        align-items:center;
        top:0%;
        bottom:0%;
        left:0%;
        right:0% */
    }

	.nav_menu-button{
        width:50px;
        height:50px;
        background-color:#a56354;
        border:2px #452d27;
        border-radius:100%;
        flex-direction:row;
        justify-content:center;
        align-items:center;
        padding:0;
        position:relative
    }
    .nav_menu-button.w--open{
        z-index:999;
        color:#fff;
        background-color:#452d27;
        border-style:none
    }

    .nav_menu-icon{
        width:100%;
        height:100%;
        padding-left:12px;
        padding-right:12px
    }
    .nav_menu-icon-bar{
        background-color:#fff;
        margin-bottom:6px
    }
}
</style>