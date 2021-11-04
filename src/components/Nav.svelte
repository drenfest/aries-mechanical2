<script>
	export let segment;
</script>

<style>
	.bg-main-menu{
		background: linear-gradient(180deg, rgba(222,222,222,1) 0%, rgba(238,238,238,1) 49%, rgba(255,255,255,1) 100%);
	}
	.bg-image{
		width:300px;
		padding:2rem;
		align-self:center;
		display:flex;
		flex-direction:column;
		justify-content:center;
		background-color:grey;
		height:100%;
		color:#ffffff;
		text-align:center;
	}

	.bg-heatnav {
	background-size: cover;
	background-repeat: no-repeat;
	background-position: center;
	background-image: url("/assets/images/heatnav.jpg");
	}

	.bg-acnav {
	background-size: cover;
	background-repeat: no-repeat;
	background-position: center;
	background-image: url("/assets/images/acnav.jpg");
	}
	.dropdown-menu{
		min-width:600px;
		margin:0;
		padding:0;
	}
	.row{
		padding:0;
		margin:0;
	}
	.col-6{
		justify-content:center;
		display:flex;
		flex-direction:column;

	}
	.mega-content {
		padding:2em;
	}

	.nav{
		padding: 0;
	}
	.nav > li{
		min-height:50px;
		display:flex;
		flex-direction:column;
		font-family: 'Oswald', sans-serif;
		font-weight:700;


	}
	.nav > li > a{
		align-content:center;
		font-size:20px;
		text-transform:uppercase;
		color:#3d5467;
		font-weight:bold;
		border-right: 1px solid white;
		padding:1.25em 0 1.25em 0;
		border-radius:0;
		font-weight:700;
	}

	.nav > li > a:hover {
    background-color: #ffffff;
    text-decoration:none;
    }


	.nav > li:first-of-type > a{
		border-left: 1px solid white;
	}
	.nav > li > a:focus, .active{

		background-color:white !important;
	}

	.dropdown-menu {
		border:none;
		border-radius:0 0 .25rem .25rem;
	}
	.dropdown-item.active:not(*:active) {
		color: var(--primary-color);
	}
	.dropdown-item:active:not(*:active) {
		color: var(--primary-color);
	}
</style>
<section class="bg-main-menu d-none d-md-block">
	<nav class="container">
		<ul class="nav navbar navbar-dark nav-fill nav-pills justify-content-between">
			<li class="nav-item dropdown">
			<a class="nav-link dropdown-toggle" href='#' role="button" aria-haspopup="true" aria-expanded="false" data-toggle="dropdown" title="Heating">Heating</a>
				<div class="dropdown-menu">
					<div class="row">
							<div class="col-6 mega-content">
								<h3>Heating</h3>
								<a rel=prefetch class='dropdown-item {segment === "heating" ? "active" : ""}' href='heating' title="Heating">Heating</a>
								<a rel=prefetch class='dropdown-item {segment === "residential-hvac" ? "active" : ""}' href='residential-hvac' title="Residential Hvac">Residential Hvac</a>
								<a rel=prefetch class='dropdown-item {segment === "furnace-sales" ? "active" : ""}' href='furnace-sales' title="New Furnace Installation">New Furnace Installation</a>
								<a rel=prefetch class='dropdown-item {segment === "furnace-repair" ? "active" : ""}' href='furnace-repair' title="Furnace Repair">Furnace Repair</a>
								<a rel=prefetch class='dropdown-item {segment === "programmable" ? "active" : ""}' href='programmable' title="Programmable Thermostats">Programmable Thermostats</a>
							</div>
							<div class="col-6">
								<div class="bg-image bg-heatnav">

								</div>
							</div>
						</div>
				</div>
			</li>
			<li class="nav-item dropdown">
				<a class="nav-link dropdown-toggle" href='#' role="button" aria-haspopup="true" aria-expanded="false" data-toggle="dropdown" title="Cooling">Cooling</a>
				<div class="dropdown-menu">
					<div class="row">
						<div class="col-6 mega-content">
							<h3>Cooling</h3>
							<a rel=prefetch class='dropdown-item {segment === "cooling" ? "active" : ""}' href='cooling' title="Cooling">Cooling</a>
							<a rel=prefetch class='dropdown-item {segment === "conditioning" ? "active" : ""}' href='conditioning' title="Air Conditioning">Air Conditioning</a>
							<a rel=prefetch class='dropdown-item {segment === "residential-hvac" ? "active" : ""}' href='residential-hvac' title="Residential Hvac">Residential Hvac</a>
							<a rel=prefetch class='dropdown-item {segment === "new-air-sales" ? "active" : ""}' href='new-air-sales' title="New A/C Installation">New A/C Installation</a>
							<a rel=prefetch class='dropdown-item {segment === "ac-repair" ? "active" : ""}' href='ac-repair' title="A/C Repair">A/C Repair</a>
							<a rel=prefetch class='dropdown-item {segment === "programmable" ? "active" : ""}' href='programmable' title="Programmable Thermostats">Programmable Thermostats</a>
						</div>
						<div class="col-6">
							<div class="bg-image bg-acnav">

							</div>
						</div>
					</div>

				</div>
			</li>
			<li class="nav-item"><a rel=prefetch class='{segment === "humidification" ? "active" : ""}' href='humidification' title="Humidification">Humidification</a></li>
			<li class="nav-item"><a rel=prefetch class='{segment === "reviews" ? "active" : ""}' href='reviews' title="Reviews">Reviews</a></li>
			<li class="nav-item"><a rel=prefetch class='{segment === "special" ? "active" : ""}' href='special' title="Specials">Specials</a></li>
			<li class="nav-item"><a rel=prefetch class='{segment === "contact" ? "active" : ""}' href='contact' title="Contact Us">Contact</a></li>
		</ul>
	</nav>
</section>

