<template>
	<nav>
		<ul class="list">
			<li class="city">
				<p class="ardess">Russia, Saint-Petersburg</p>
			</li>
			<li>
				Phone: <a href="tel:+7 921 445 45 77">+7 921 445 45 77</a>
			</li>
			<li>
				Mail:
				<a href="mailto:vegetables@mail.com" class="mail">
					pasha@mail.com</a>
			</li>
		</ul>
	</nav>
</template>

<script>
export default {
	name: "Navigation"
}
</script>

<style scoped>
nav {
	width:              100vw;
	background-color:   #27272c;
	height:             2rem;
	position:           absolute;
	top:                0;
	box-shadow:         1px 92px 52px 33px rgba(0, 0, 0, 0.2);
	-webkit-box-shadow: 1px 92px 52px 33px rgba(0, 0, 0, 0.2);
	-moz-box-shadow:    1px 92px 52px 33px rgba(0, 0, 0, 0.2);
	display:            flex;
	z-index:            10;
}

p {
	padding: 0;
	margin:  0;
}

ul {
	position:    absolute;
	top:         2px;
	margin:      0;
	list-style:  none;
	padding:     0;
	display:     flex;
	color:       #888;
	font-size:   16px;
	line-height: 25px;
}

li {
	margin-right: 20px;
}

a {
	font-weight: normal;
	font-size:   16px;
	line-height: 25px;
	color:       #888;
}

.city {
	width:        14rem;
	margin-right: calc(54vw - 20px);
}

</style>