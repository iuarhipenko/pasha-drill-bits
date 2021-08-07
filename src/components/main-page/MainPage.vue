<template>
	<Navigation/>
	<header class="header">
		<div class="titles">
			<h1>Буровой инстумент</h1>
			<span>Купим в&nbsp;рабочем состоянии</span>
		</div>
	</header>
	<ContentInfo />
	<Footer />
</template>

<script>
import Navigation from '../navigation/Navigation.vue'
import ContentInfo from '../contentInfo/ContentInfo.vue'
import Footer from '../footer/Footer.vue'

export default {
	name:       "MainPage",
	components: {
		Navigation,
		ContentInfo,
		Footer
	}
}
</script>

<style>
.header {
	background: no-repeat center/100% url("img/Tricone-Drill-Bits.png");
	height:     33.9rem;
	width:      100vw;
	display:    flex;
	position:   relative;
}

.header::after {
	position:         absolute;
	background-color: #aaaa;
	content:          '';
	width:            100vw;
	height:           100%;

	left:             0;
	opacity:          .7;

}

.titles {
	display:         flex;
	flex-direction:  column;
	margin-right:    auto;
	width:           29rem;
	justify-content: center;
	z-index:         10;
	margin-left:     3rem;
	text-align:      left;
}

h1 {
	font-size:      3.625rem;
	font-weight:    600;
	color:          #fff;
	margin-bottom:  15px;
}

h1 span {
	color:       rgba(255, 255, 255, .8);
	font-size:   1rem;
	font-weight: 400;
	line-height: 1.625;
}
</style>