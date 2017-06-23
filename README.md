# css<br />@import url("http://fonts.googleapis.com/css?family=Source+Sans+Pro:400,400italic,700,900");
@import url("font-awesome.min.css");

/*
	Escape Velocity by HTML5 UP
	html5up.net | @ajlkn
	Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)
*/

/* Reset */

	html, body, div, span, applet, object, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, pre, a, abbr, acronym, address, big, cite, code, del, dfn, em, img, ins, kbd, q, s, samp, small, strike, strong, sub, sup, tt, var, b, u, i, center, dl, dt, dd, ol, ul, li, fieldset, form, label, legend, table, caption, tbody, tfoot, thead, tr, th, td, article, aside, canvas, details, embed, figure, figcaption, footer, header, hgroup, menu, nav, output, ruby, section, summary, time, mark, audio, video {
		margin: 0;
		padding: 0;
		border: 0;
		font-size: 100%;
		font: inherit;
		vertical-align: baseline;
	}

	article, aside, details, figcaption, figure, footer, header, hgroup, menu, nav, section {
		display: block;
	}

	body {
		line-height: 1;
	}

	ol, ul {
		list-style: none;
	}

	blockquote, q {
		quotes: none;
	}

	blockquote:before, blockquote:after, q:before, q:after {
		content: '';
		content: none;
	}

	table {
		border-collapse: collapse;
		border-spacing: 0;
	}

	body {
		-webkit-text-size-adjust: none;
	}

/* Box Model */

	*, *:before, *:after {
		-moz-box-sizing: border-box;
		-webkit-box-sizing: border-box;
		box-sizing: border-box;
	}

/* Containers */

	.container {
		margin-left: auto;
		margin-right: auto;
	}

	.container.\31 25\25 {
		width: 100%;
		max-width: 1200px;
		min-width: 960px;
	}

	.container.\37 5\25 {
		width: 720px;
	}

	.container.\35 0\25 {
		width: 480px;
	}

	.container.\32 5\25 {
		width: 240px;
	}

	.container {
		width: 960px;
	}

	@media screen and (min-width: 737px) {

		.container.\31 25\25 {
			width: 100%;
			max-width: 1500px;
			min-width: 1200px;
		}

		.container.\37 5\25 {
			width: 900px;
		}

		.container.\35 0\25 {
			width: 600px;
		}

		.container.\32 5\25 {
			width: 300px;
		}

		.container {
			width: 1200px;
		}

	}

	@media screen and (min-width: 737px) and (max-width: 1200px) {

		.container.\31 25\25 {
			width: 100%;
			max-width: 1250px;
			min-width: 1000px;
		}

		.container.\37 5\25 {
			width: 750px;
		}

		.container.\35 0\25 {
			width: 500px;
		}

		.container.\32 5\25 {
			width: 250px;
		}

		.container {
			width: 1000px;
		}

	}

	@media screen and (max-width: 736px) {

		.container.\31 25\25 {
			width: 100%;
			max-width: 125%;
			min-width: 100%;
		}

		.container.\37 5\25 {
			width: 75%;
		}

		.container.\35 0\25 {
			width: 50%;
		}

		.container.\32 5\25 {
			width: 25%;
		}

		.container {
			width: 100% !important;
		}

	}

/* Grid */

	.row {
		border-bottom: solid 1px transparent;
		-moz-box-sizing: border-box;
		-webkit-box-sizing: border-box;
		box-sizing: border-box;
	}

	.row > * {
		float: left;
		-moz-box-sizing: border-box;
		-webkit-box-sizing: border-box;
		box-sizing: border-box;
	}

	.row:after, .row:before {
		content: '';
		display: block;
		clear: both;
		height: 0;
	}

	.row.uniform > * > :first-child {
		margin-top: 0;
	}

	.row.uniform > * > :last-child {
		margin-bottom: 0;
	}

	.row.\30 \25 > * {
		padding: 0 0 0 0px;
	}

	.row.\30 \25 {
		margin: 0 0 -1px 0px;
	}

	.row.uniform.\30 \25 > * {
		padding: 0px 0 0 0px;
	}

	.row.uniform.\30 \25 {
		margin: 0px 0 -1px 0px;
	}

	.row > * {
		padding: 0 0 0 40px;
	}

	.row {
		margin: 0 0 -1px -40px;
	}

	.row.uniform > * {
		padding: 40px 0 0 40px;
	}

	.row.uniform {
		margin: -40px 0 -1px -40px;
	}

	.row.\32 00\25 > * {
		padding: 0 0 0 80px;
	}

	.row.\32 00\25 {
		margin: 0 0 -1px -80px;
	}

	.row.uniform.\32 00\25 > * {
		padding: 80px 0 0 80px;
	}

	.row.uniform.\32 00\25 {
		margin: -80px 0 -1px -80px;
	}

	.row.\31 50\25 > * {
		padding: 0 0 0 60px;
	}

	.row.\31 50\25 {
		margin: 0 0 -1px -60px;
	}

	.row.uniform.\31 50\25 > * {
		padding: 60px 0 0 60px;
	}

	.row.uniform.\31 50\25 {
		margin: -60px 0 -1px -60px;
	}

	.row.\35 0\25 > * {
		padding: 0 0 0 20px;
	}

	.row.\35 0\25 {
		margin: 0 0 -1px -20px;
	}

	.row.uniform.\35 0\25 > * {
		padding: 20px 0 0 20px;
	}

	.row.uniform.\35 0\25 {
		margin: -20px 0 -1px -20px;
	}

	.row.\32 5\25 > * {
		padding: 0 0 0 10px;
	}

	.row.\32 5\25 {
		margin: 0 0 -1px -10px;
	}

	.row.uniform.\32 5\25 > * {
		padding: 10px 0 0 10px;
	}

	.row.uniform.\32 5\25 {
		margin: -10px 0 -1px -10px;
	}

	.\31 2u, .\31 2u\24 {
		width: 100%;
		clear: none;
		margin-left: 0;
	}

	.\31 1u, .\31 1u\24 {
		width: 91.6666666667%;
		clear: none;
		margin-left: 0;
	}

	.\31 0u, .\31 0u\24 {
		width: 83.3333333333%;
		clear: none;
		margin-left: 0;
	}

	.\39 u, .\39 u\24 {
		width: 75%;
		clear: none;
		margin-left: 0;
	}

	.\38 u, .\38 u\24 {
		width: 66.6666666667%;
		clear: none;
		margin-left: 0;
	}

	.\37 u, .\37 u\24 {
		width: 58.3333333333%;
		clear: none;
		margin-left: 0;
	}

	.\36 u, .\36 u\24 {
		width: 50%;
		clear: none;
		margin-left: 0;
	}

	.\35 u, .\35 u\24 {
		width: 41.6666666667%;
		clear: none;
		margin-left: 0;
	}

	.\34 u, .\34 u\24 {
		width: 33.3333333333%;
		clear: none;
		margin-left: 0;
	}

	.\33 u, .\33 u\24 {
		width: 25%;
		clear: none;
		margin-left: 0;
	}

	.\32 u, .\32 u\24 {
		width: 16.6666666667%;
		clear: none;
		margin-left: 0;
	}

	.\31 u, .\31 u\24 {
		width: 8.3333333333%;
		clear: none;
		margin-left: 0;
	}

	.\31 2u\24 + *,
	.\31 1u\24 + *,
	.\31 0u\24 + *,
	.\39 u\24 + *,
	.\38 u\24 + *,
	.\37 u\24 + *,
	.\36 u\24 + *,
	.\35 u\24 + *,
	.\34 u\24 + *,
	.\33 u\24 + *,
	.\32 u\24 + *,
	.\31 u\24 + * {
		clear: left;
	}

	.\-11u {
		margin-left: 91.66667%;
	}

	.\-10u {
		margin-left: 83.33333%;
	}

	.\-9u {
		margin-left: 75%;
	}

	.\-8u {
		margin-left: 66.66667%;
	}

	.\-7u {
		margin-left: 58.33333%;
	}

	.\-6u {
		margin-left: 50%;
	}

	.\-5u {
		margin-left: 41.66667%;
	}

	.\-4u {
		margin-left: 33.33333%;
	}

	.\-3u {
		margin-left: 25%;
	}

	.\-2u {
		margin-left: 16.66667%;
	}

	.\-1u {
		margin-left: 8.33333%;
	}

	@media screen and (min-width: 737px) {

		.row > * {
			padding: 50px 0 0 50px;
		}

		.row {
			margin: -50px 0 -1px -50px;
		}

		.row.uniform > * {
			padding: 50px 0 0 50px;
		}

		.row.uniform {
			margin: -50px 0 -1px -50px;
		}

		.row.\32 00\25 > * {
			padding: 100px 0 0 100px;
		}

		.row.\32 00\25 {
			margin: -100px 0 -1px -100px;
		}

		.row.uniform.\32 00\25 > * {
			padding: 100px 0 0 100px;
		}

		.row.uniform.\32 00\25 {
			margin: -100px 0 -1px -100px;
		}

		.row.\31 50\25 > * {
			padding: 75px 0 0 75px;
		}

		.row.\31 50\25 {
			margin: -75px 0 -1px -75px;
		}

		.row.uniform.\31 50\25 > * {
			padding: 75px 0 0 75px;
		}

		.row.uniform.\31 50\25 {
			margin: -75px 0 -1px -75px;
		}

		.row.\35 0\25 > * {
			padding: 25px 0 0 25px;
		}

		.row.\35 0\25 {
			margin: -25px 0 -1px -25px;
		}

		.row.uniform.\35 0\25 > * {
			padding: 25px 0 0 25px;
		}

		.row.uniform.\35 0\25 {
			margin: -25px 0 -1px -25px;
		}

		.row.\32 5\25 > * {
			padding: 12.5px 0 0 12.5px;
		}

		.row.\32 5\25 {
			margin: -12.5px 0 -1px -12.5px;
		}

		.row.uniform.\32 5\25 > * {
			padding: 12.5px 0 0 12.5px;
		}

		.row.uniform.\32 5\25 {
			margin: -12.5px 0 -1px -12.5px;
		}

		.\31 2u\28desktop\29, .\31 2u\24\28desktop\29 {
			width: 100%;
			clear: none;
			margin-left: 0;
		}

		.\31 1u\28desktop\29, .\31 1u\24\28desktop\29 {
			width: 91.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\31 0u\28desktop\29, .\31 0u\24\28desktop\29 {
			width: 83.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\39 u\28desktop\29, .\39 u\24\28desktop\29 {
			width: 75%;
			clear: none;
			margin-left: 0;
		}

		.\38 u\28desktop\29, .\38 u\24\28desktop\29 {
			width: 66.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\37 u\28desktop\29, .\37 u\24\28desktop\29 {
			width: 58.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\36 u\28desktop\29, .\36 u\24\28desktop\29 {
			width: 50%;
			clear: none;
			margin-left: 0;
		}

		.\35 u\28desktop\29, .\35 u\24\28desktop\29 {
			width: 41.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\34 u\28desktop\29, .\34 u\24\28desktop\29 {
			width: 33.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\33 u\28desktop\29, .\33 u\24\28desktop\29 {
			width: 25%;
			clear: none;
			margin-left: 0;
		}

		.\32 u\28desktop\29, .\32 u\24\28desktop\29 {
			width: 16.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\31 u\28desktop\29, .\31 u\24\28desktop\29 {
			width: 8.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\31 2u\24\28desktop\29 + *,
		.\31 1u\24\28desktop\29 + *,
		.\31 0u\24\28desktop\29 + *,
		.\39 u\24\28desktop\29 + *,
		.\38 u\24\28desktop\29 + *,
		.\37 u\24\28desktop\29 + *,
		.\36 u\24\28desktop\29 + *,
		.\35 u\24\28desktop\29 + *,
		.\34 u\24\28desktop\29 + *,
		.\33 u\24\28desktop\29 + *,
		.\32 u\24\28desktop\29 + *,
		.\31 u\24\28desktop\29 + * {
			clear: left;
		}

		.\-11u\28desktop\29 {
			margin-left: 91.66667%;
		}

		.\-10u\28desktop\29 {
			margin-left: 83.33333%;
		}

		.\-9u\28desktop\29 {
			margin-left: 75%;
		}

		.\-8u\28desktop\29 {
			margin-left: 66.66667%;
		}

		.\-7u\28desktop\29 {
			margin-left: 58.33333%;
		}

		.\-6u\28desktop\29 {
			margin-left: 50%;
		}

		.\-5u\28desktop\29 {
			margin-left: 41.66667%;
		}

		.\-4u\28desktop\29 {
			margin-left: 33.33333%;
		}

		.\-3u\28desktop\29 {
			margin-left: 25%;
		}

		.\-2u\28desktop\29 {
			margin-left: 16.66667%;
		}

		.\-1u\28desktop\29 {
			margin-left: 8.33333%;
		}

	}

	@media screen and (min-width: 737px) and (max-width: 1200px) {

		.row > * {
			padding: 35px 0 0 35px;
		}

		.row {
			margin: -35px 0 -1px -35px;
		}

		.row.uniform > * {
			padding: 35px 0 0 35px;
		}

		.row.uniform {
			margin: -35px 0 -1px -35px;
		}

		.row.\32 00\25 > * {
			padding: 70px 0 0 70px;
		}

		.row.\32 00\25 {
			margin: -70px 0 -1px -70px;
		}

		.row.uniform.\32 00\25 > * {
			padding: 70px 0 0 70px;
		}

		.row.uniform.\32 00\25 {
			margin: -70px 0 -1px -70px;
		}

		.row.\31 50\25 > * {
			padding: 52.5px 0 0 52.5px;
		}

		.row.\31 50\25 {
			margin: -52.5px 0 -1px -52.5px;
		}

		.row.uniform.\31 50\25 > * {
			padding: 52.5px 0 0 52.5px;
		}

		.row.uniform.\31 50\25 {
			margin: -52.5px 0 -1px -52.5px;
		}

		.row.\35 0\25 > * {
			padding: 17.5px 0 0 17.5px;
		}

		.row.\35 0\25 {
			margin: -17.5px 0 -1px -17.5px;
		}

		.row.uniform.\35 0\25 > * {
			padding: 17.5px 0 0 17.5px;
		}

		.row.uniform.\35 0\25 {
			margin: -17.5px 0 -1px -17.5px;
		}

		.row.\32 5\25 > * {
			padding: 8.75px 0 0 8.75px;
		}

		.row.\32 5\25 {
			margin: -8.75px 0 -1px -8.75px;
		}

		.row.uniform.\32 5\25 > * {
			padding: 8.75px 0 0 8.75px;
		}

		.row.uniform.\32 5\25 {
			margin: -8.75px 0 -1px -8.75px;
		}

		.\31 2u\28tablet\29, .\31 2u\24\28tablet\29 {
			width: 100%;
			clear: none;
			margin-left: 0;
		}

		.\31 1u\28tablet\29, .\31 1u\24\28tablet\29 {
			width: 91.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\31 0u\28tablet\29, .\31 0u\24\28tablet\29 {
			width: 83.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\39 u\28tablet\29, .\39 u\24\28tablet\29 {
			width: 75%;
			clear: none;
			margin-left: 0;
		}

		.\38 u\28tablet\29, .\38 u\24\28tablet\29 {
			width: 66.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\37 u\28tablet\29, .\37 u\24\28tablet\29 {
			width: 58.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\36 u\28tablet\29, .\36 u\24\28tablet\29 {
			width: 50%;
			clear: none;
			margin-left: 0;
		}

		.\35 u\28tablet\29, .\35 u\24\28tablet\29 {
			width: 41.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\34 u\28tablet\29, .\34 u\24\28tablet\29 {
			width: 33.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\33 u\28tablet\29, .\33 u\24\28tablet\29 {
			width: 25%;
			clear: none;
			margin-left: 0;
		}

		.\32 u\28tablet\29, .\32 u\24\28tablet\29 {
			width: 16.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\31 u\28tablet\29, .\31 u\24\28tablet\29 {
			width: 8.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\31 2u\24\28tablet\29 + *,
		.\31 1u\24\28tablet\29 + *,
		.\31 0u\24\28tablet\29 + *,
		.\39 u\24\28tablet\29 + *,
		.\38 u\24\28tablet\29 + *,
		.\37 u\24\28tablet\29 + *,
		.\36 u\24\28tablet\29 + *,
		.\35 u\24\28tablet\29 + *,
		.\34 u\24\28tablet\29 + *,
		.\33 u\24\28tablet\29 + *,
		.\32 u\24\28tablet\29 + *,
		.\31 u\24\28tablet\29 + * {
			clear: left;
		}

		.\-11u\28tablet\29 {
			margin-left: 91.66667%;
		}

		.\-10u\28tablet\29 {
			margin-left: 83.33333%;
		}

		.\-9u\28tablet\29 {
			margin-left: 75%;
		}

		.\-8u\28tablet\29 {
			margin-left: 66.66667%;
		}

		.\-7u\28tablet\29 {
			margin-left: 58.33333%;
		}

		.\-6u\28tablet\29 {
			margin-left: 50%;
		}

		.\-5u\28tablet\29 {
			margin-left: 41.66667%;
		}

		.\-4u\28tablet\29 {
			margin-left: 33.33333%;
		}

		.\-3u\28tablet\29 {
			margin-left: 25%;
		}

		.\-2u\28tablet\29 {
			margin-left: 16.66667%;
		}

		.\-1u\28tablet\29 {
			margin-left: 8.33333%;
		}

	}

	@media screen and (max-width: 736px) {

		.row > * {
			padding: 10px 0 0 10px;
		}

		.row {
			margin: -10px 0 -1px -10px;
		}

		.row.uniform > * {
			padding: 10px 0 0 10px;
		}

		.row.uniform {
			margin: -10px 0 -1px -10px;
		}

		.row.\32 00\25 > * {
			padding: 20px 0 0 20px;
		}

		.row.\32 00\25 {
			margin: -20px 0 -1px -20px;
		}

		.row.uniform.\32 00\25 > * {
			padding: 20px 0 0 20px;
		}

		.row.uniform.\32 00\25 {
			margin: -20px 0 -1px -20px;
		}

		.row.\31 50\25 > * {
			padding: 15px 0 0 15px;
		}

		.row.\31 50\25 {
			margin: -15px 0 -1px -15px;
		}

		.row.uniform.\31 50\25 > * {
			padding: 15px 0 0 15px;
		}

		.row.uniform.\31 50\25 {
			margin: -15px 0 -1px -15px;
		}

		.row.\35 0\25 > * {
			padding: 5px 0 0 5px;
		}

		.row.\35 0\25 {
			margin: -5px 0 -1px -5px;
		}

		.row.uniform.\35 0\25 > * {
			padding: 5px 0 0 5px;
		}

		.row.uniform.\35 0\25 {
			margin: -5px 0 -1px -5px;
		}

		.row.\32 5\25 > * {
			padding: 2.5px 0 0 2.5px;
		}

		.row.\32 5\25 {
			margin: -2.5px 0 -1px -2.5px;
		}

		.row.uniform.\32 5\25 > * {
			padding: 2.5px 0 0 2.5px;
		}

		.row.uniform.\32 5\25 {
			margin: -2.5px 0 -1px -2.5px;
		}

		.\31 2u\28mobile\29, .\31 2u\24\28mobile\29 {
			width: 100%;
			clear: none;
			margin-left: 0;
		}

		.\31 1u\28mobile\29, .\31 1u\24\28mobile\29 {
			width: 91.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\31 0u\28mobile\29, .\31 0u\24\28mobile\29 {
			width: 83.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\39 u\28mobile\29, .\39 u\24\28mobile\29 {
			width: 75%;
			clear: none;
			margin-left: 0;
		}

		.\38 u\28mobile\29, .\38 u\24\28mobile\29 {
			width: 66.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\37 u\28mobile\29, .\37 u\24\28mobile\29 {
			width: 58.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\36 u\28mobile\29, .\36 u\24\28mobile\29 {
			width: 50%;
			clear: none;
			margin-left: 0;
		}

		.\35 u\28mobile\29, .\35 u\24\28mobile\29 {
			width: 41.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\34 u\28mobile\29, .\34 u\24\28mobile\29 {
			width: 33.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\33 u\28mobile\29, .\33 u\24\28mobile\29 {
			width: 25%;
			clear: none;
			margin-left: 0;
		}

		.\32 u\28mobile\29, .\32 u\24\28mobile\29 {
			width: 16.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\31 u\28mobile\29, .\31 u\24\28mobile\29 {
			width: 8.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\31 2u\24\28mobile\29 + *,
		.\31 1u\24\28mobile\29 + *,
		.\31 0u\24\28mobile\29 + *,
		.\39 u\24\28mobile\29 + *,
		.\38 u\24\28mobile\29 + *,
		.\37 u\24\28mobile\29 + *,
		.\36 u\24\28mobile\29 + *,
		.\35 u\24\28mobile\29 + *,
		.\34 u\24\28mobile\29 + *,
		.\33 u\24\28mobile\29 + *,
		.\32 u\24\28mobile\29 + *,
		.\31 u\24\28mobile\29 + * {
			clear: left;
		}

		.\-11u\28mobile\29 {
			margin-left: 91.66667%;
		}

		.\-10u\28mobile\29 {
			margin-left: 83.33333%;
		}

		.\-9u\28mobile\29 {
			margin-left: 75%;
		}

		.\-8u\28mobile\29 {
			margin-left: 66.66667%;
		}

		.\-7u\28mobile\29 {
			margin-left: 58.33333%;
		}

		.\-6u\28mobile\29 {
			margin-left: 50%;
		}

		.\-5u\28mobile\29 {
			margin-left: 41.66667%;
		}

		.\-4u\28mobile\29 {
			margin-left: 33.33333%;
		}

		.\-3u\28mobile\29 {
			margin-left: 25%;
		}

		.\-2u\28mobile\29 {
			margin-left: 16.66667%;
		}

		.\-1u\28mobile\29 {
			margin-left: 8.33333%;
		}

	}

/* Basic */

	@-ms-viewport {
		width: device-width;
	}

	body, input, textarea, select {
		font-family: 'Source Sans Pro', sans-serif;
		font-weight: 400;
		color: #919499;
	}

	body.is-loading * {
		-moz-transition: none !important;
		-webkit-transition: none !important;
		-ms-transition: none !important;
		transition: none !important;
		-moz-animation: none !important;
		-webkit-animation: none !important;
		-ms-animation: none !important;
		animation: none !important;
	}

	h1, h2, h3, h4, h5, h6 {
		font-weight: 700;
		color: #484d55;
	}

		h1 a, h2 a, h3 a, h4 a, h5 a, h6 a {
			color: inherit;
			text-decoration: none;
		}

	a {
		-moz-transition: color .25s ease-in-out;
		-webkit-transition: color .25s ease-in-out;
		-ms-transition: color .25s ease-in-out;
		transition: color .25s ease-in-out;
		text-decoration: underline;
		color: #717479;
	}

		a:hover {
			text-decoration: none;
		}

	strong, b {
		font-weight: 700;
		color: #484d55;
	}

	blockquote {
		border-left: solid 0.5em #ddd;
		padding: 1em 0 1em 2em;
		font-style: italic;
	}

	em, i {
		font-style: italic;
	}

	hr {
		border: 0;
		border-top: solid 1px #ddd;
	}

	sub {
		position: relative;
		top: 0.5em;
		font-size: 0.8em;
	}

	sup {
		position: relative;
		top: -0.5em;
		font-size: 0.8em;
	}

	.nobr {
		white-space: nowrap;
	}

	br.clear {
		clear: both;
	}

	p, ul, ol, dl, table, blockquote, form {
		margin-bottom: 2em;
	}

/* Table */

	table {
		width: 100%;
	}

		table.default {
			width: 100%;
		}

			table.default tbody tr:nth-child(2n+2) {
				background: #f4f4f4;
			}

			table.default td {
				padding: 0.5em 1em 0.5em 1em;
			}

			table.default th {
				text-align: left;
				font-weight: 400;
				padding: 0.5em 1em 0.5em 1em;
			}

			table.default thead {
				background: #484d55;
				color: #fff;
			}

			table.default tfoot {
				background: #eee;
			}

/* Form */

	form label {
		display: block;
		font-weight: 700;
		color: #484d55;
	}

	form input[type="text"],
	form input[type="email"],
	form input[type="password"],
	form select,
	form textarea {
		-moz-transition: all .25s ease-in-out;
		-webkit-transition: all .25s ease-in-out;
		-ms-transition: all .25s ease-in-out;
		transition: all .25s ease-in-out;
		-webkit-appearance: none;
		display: block;
		border: 0;
		background: #eee;
		box-shadow: inset 0px 0px 1px 0px #a0a1a7;
		border-radius: 0.35em;
		width: 100%;
		padding: 0.75em 1em 0.75em 1em;
	}

		form input[type="text"]:focus,
		form input[type="email"]:focus,
		form input[type="password"]:focus,
		form select:focus,
		form textarea:focus {
			background: #f8f8f8;
		}

	form input[type="text"],
	form input[type="email"]
	input[type="password"] {
		line-height: 1em;
	}

	form select {
		line-height: 1em;
	}

	form textarea {
		min-height: 10em;
	}

	form .formerize-placeholder {
		color: #555 !important;
		font-style: italic;
	}

	form ::-webkit-input-placeholder {
		color: #555 !important;
		font-style: italic;
		line-height: 1.35em;
	}

	form :-moz-placeholder {
		color: #555 !important;
		font-style: italic;
	}

	form ::-moz-placeholder {
		color: #555 !important;
		font-style: italic;
	}

	form :-ms-input-placeholder {
		color: #555 !important;
		font-style: italic;
	}

	form ::-moz-focus-inner {
		border: 0;
	}

/* Section/Article */

	section,
	article {
		margin-bottom: 3em;
	}

	section > :last-child,
	article > :last-child,
	section:last-child,
	article:last-child {
		margin-bottom: 0;
	}

	header.style1 {
		text-align: center;
	}

		header.style1 h2 {
			font-weight: 700;
		}

		header.style1 p {
			color: #b1b4b9;
		}

/* Image */

	.image {
		display: inline-block;
	}

		.image img {
			display: block;
			width: 100%;
		}

		.image.fit {
			display: block;
			width: 100%;
		}

		.image.left {
			float: left;
			margin: 0 2em 2em 0;
		}

		.image.centered {
			display: block;
			margin: 0 0 2em 0;
		}

			.image.centered img {
				margin: 0 auto;
				width: auto;
			}

		.image.featured {
			display: block;
			width: 100%;
			margin: 0 0 2em 0;
		}

/* Button */

	input[type="button"],
	input[type="submit"],
	input[type="reset"],
	button,
	.button {
		-moz-transition: all .25s ease-in-out;
		-webkit-transition: all .25s ease-in-out;
		-ms-transition: all .25s ease-in-out;
		transition: all .25s ease-in-out;
		display: inline-block;
		background: #444;
		text-align: center;
		text-transform: uppercase;
		font-weight: 700;
		letter-spacing: 0.25em;
		text-decoration: none;
		border-radius: 0.35em;
		border: 0;
		outline: 0;
		cursor: pointer;
	}

		input[type="button"]:hover,
		input[type="submit"]:hover,
		input[type="reset"]:hover,
		button:hover,
		.button:hover {
			background-color: #f98780;
		}

		input[type="button"].style1,
		input[type="submit"].style1,
		input[type="reset"].style1,
		button.style1,
		.button.style1 {
			background: #e97770 url("images/overlay.png");
			color: #fff;
		}

			input[type="button"].style1:hover,
			input[type="submit"].style1:hover,
			input[type="reset"].style1:hover,
			button.style1:hover,
			.button.style1:hover {
				background-color: #f98780;
			}

			input[type="button"].style1:active,
			input[type="submit"].style1:active,
			input[type="reset"].style1:active,
			button.style1:active,
			.button.style1:active {
				background-color: #d96760;
			}

		input[type="button"].style2,
		input[type="submit"].style2,
		input[type="reset"].style2,
		button.style2,
		.button.style2 {
			background: none;
			color: #606167;
			box-shadow: inset 0px 0px 2px 0px #a0a1a7;
		}

			input[type="button"].style2:hover,
			input[type="submit"].style2:hover,
			input[type="reset"].style2:hover,
			button.style2:hover,
			.button.style2:hover {
				box-shadow: inset 0px 0px 2px 0px #606167;
			}

			input[type="button"].style2:active,
			input[type="submit"].style2:active,
			input[type="reset"].style2:active,
			button.style2:active,
			.button.style2:active {
				box-shadow: inset 0px 0px 2px 0px #202127;
			}

		input[type="button"].style3,
		input[type="submit"].style3,
		input[type="reset"].style3,
		button.style3,
		.button.style3 {
			background: #2f333b url("images/overlay.png");
			color: #fff;
		}

			input[type="button"].style3:hover,
			input[type="submit"].style3:hover,
			input[type="reset"].style3:hover,
			button.style3:hover,
			.button.style3:hover {
				background-color: #3f434b;
			}

			input[type="button"].style3:active,
			input[type="submit"].style3:active,
			input[type="reset"].style3:active,
			button.style3:active,
			.button.style3:active {
				background-color: #1f232b;
			}

/* List */

	ul.default {
		list-style: disc;
		padding-left: 1em;
	}

		ul.default li {
			padding-left: 0.5em;
		}

	ul.style2 li {
		border-top: solid 1px #eee;
		padding: 1.5em 0 0 0;
		margin: 1.5em 0 0 0;
	}

		ul.style2 li:first-child {
			border-top: 0;
			padding-top: 0;
			margin-top: 0;
		}

	ul.style3 li {
		border-top: solid 1px #eee;
		padding: 0.5em 0 0 0;
		margin: 0.5em 0 0 0;
	}

		ul.style3 li:first-child {
			border-top: 0;
			padding-top: 0;
			margin-top: 0;
		}

	ol.default {
		list-style: decimal;
		padding-left: 1.25em;
	}

		ol.default li {
			padding-left: 0.25em;
		}

/* Feature List */

	.feature-list h3 {
		color: #e97770 !important;
	}

		.feature-list h3:before {
			position: relative;
			display: inline-block;
			color: #fff;
			background: #2f333b url("images/overlay.png");
			border-radius: 1em;
			text-align: center;
		}

/* Icons */

	.icon {
		text-decoration: none;
	}

		.icon:before {
			display: inline-block;
			font-family: FontAwesome;
			font-size: 1.25em;
			text-decoration: none;
			font-style: normal;
			font-weight: normal;
			line-height: 1;
			-webkit-font-smoothing: antialiased;
			-moz-osx-font-smoothing: grayscale;
		}

		.icon > .label {
			display: none;
		}

/* Wrappers */

	.wrapper {
		position: relative;
	}

		.wrapper .title {
			position: absolute;
			top: 0;
			left: 50%;
			text-align: center;
			text-transform: uppercase;
			display: block;
			font-weight: 700;
			letter-spacing: 0.25em;
		}

			.wrapper .title:before {
				content: '';
				position: absolute;
				bottom: -38px;
				left: -35px;
				width: 35px;
				height: 38px;
				background: url("images/shadow.png");
			}

			.wrapper .title:after {
				-moz-transform: scaleX(-1);
				-webkit-transform: scaleX(-1);
				-ms-transform: scaleX(-1);
				transform: scaleX(-1);
				content: '';
				position: absolute;
				bottom: -38px;
				right: -35px;
				width: 35px;
				height: 38px;
				background: url("images/shadow.png");
			}

		.wrapper.style1 {
			background: #484d55 url("images/overlay.png");
			color: #eee;
			color: rgba(255, 255, 255, 0.75);
		}

			.wrapper.style1 .title {
				background: #484d55 url("images/overlay.png");
				color: #fff;
			}

			.wrapper.style1 h1, .wrapper.style1 h2, .wrapper.style1 h3, .wrapper.style1 h4, .wrapper.style1 h5, .wrapper.style1 h6, .wrapper.style1 strong, .wrapper.style1 b, .wrapper.style1 a {
				color: #fff;
			}

		.wrapper.style2 {
			background: #fff;
		}

			.wrapper.style2 .title {
				background: #fff;
				color: #484d55;
			}

		.wrapper.style3 {
			background: #f3f3f3 url("images/overlay.png");
		}

			.wrapper.style3 .title {
				background: #f3f3f3 url("images/overlay.png");
				color: #484d55;
			}

			.wrapper.style3 .image {
				border: solid 10px #fff;
			}

	#header-wrapper {
		background: url("") center center;
		background-size: cover;
	}

		#header-wrapper:before {
			content: '';
			position: relative;
			top: 0;
			left: 0;
			width: 100%;
			height: 100%;
			background: url("images/overlay.png");
		}

	#footer-wrapper {
		background: #282b34 url("images/overlay.png");
		color: #00000;
		color: rgba(255, 255, 255, 0.5);
	}

		#footer-wrapper h1, #footer-wrapper h2, #footer-wrapper h3, #footer-wrapper h4, #footer-wrapper h5, #footer-wrapper h6, #footer-wrapper strong, #footer-wrapper b, #footer-wrapper a {
			color: #fff;
		}

		#footer-wrapper hr {
			border-top-color: #333;
			border-top-color: rgba(255, 255, 255, 0.05);
		}

		#footer-wrapper form input[type="text"],
		#footer-wrapper form input[type="email"],
		#footer-wrapper form input[type="password"],
		#footer-wrapper form select,
		#footer-wrapper form textarea {
			background: #ccc;
			box-shadow: none;
		}

			#footer-wrapper form input[type="text"]:focus,
			#footer-wrapper form input[type="email"]:focus,
			#footer-wrapper form input[type="password"]:focus,
			#footer-wrapper form select:focus,
			#footer-wrapper form textarea:focus {
				background: #fff;
			}

		#footer-wrapper input[type="button"],
		#footer-wrapper input[type="submit"],
		#footer-wrapper input[type="reset"],
		#footer-wrapper button,
		#footer-wrapper .button {
			color: #fff;
			box-shadow: inset 0px 0px 2px 0px rgba(255, 255, 255, 0.5);
		}

			#footer-wrapper input[type="button"]:hover,
			#footer-wrapper input[type="submit"]:hover,
			#footer-wrapper input[type="reset"]:hover,
			#footer-wrapper button:hover,
			#footer-wrapper .button:hover {
				color: #fff;
				box-shadow: inset 0px 0px 2px 0px rgba(255, 255, 255, 0.65);
			}

			#footer-wrapper input[type="button"]:active,
			#footer-wrapper input[type="submit"]:active,
			#footer-wrapper input[type="reset"]:active,
			#footer-wrapper button:active,
			#footer-wrapper .button:active {
				box-shadow: inset 0px 0px 2px 0px rgba(255, 255, 255, 0.75);
			}

			#footer-wrapper input[type="button"].style2:active,
			#footer-wrapper input[type="submit"].style2:active,
			#footer-wrapper input[type="reset"].style2:active,
			#footer-wrapper button.style2:active,
			#footer-wrapper .button.style2:active {
				box-shadow: inset 0px 0px 2px 0px rgba(255, 255, 255, 0.75);
			}

		#footer-wrapper .title {
			background: #282b34 url("images/overlay.png");
			color: #eee;
		}

		#footer-wrapper header.style1 h2 {
			color: #fff;
		}

		#footer-wrapper header.style1 .p {
			color: inherit;
		}

		#footer-wrapper .feature-list section {
			border-top-color: #333;
			border-top-color: rgba(255, 255, 255, 0.05);
		}

		#footer-wrapper .feature-list h3:before {
			background: #3d4249 url("images/overlay.png");
		}

/* Logo */

	#logo h1 {
		font-weight: 900;
		text-transform: uppercase;
		color: #fff;
	}

	#logo p {
		color: #eee;
		color: rgba(255, 255, 255, 0.5);
		text-transform: uppercase;
	}

/* Intro */

	#intro > .style2 {
		font-weight: 700;
		color: #fff;
		border-radius: 0.35em;
		box-shadow: inset 0px 0px 1px 1px rgba(255, 255, 255, 0.25);
	}

		#intro > .style2 a {
			color: inherit;
			text-decoration: none;
		}

/* Highlights */

	#highlights .highlight {
		text-align: center;
	}

		#highlights .highlight h3 {
			color: #e97770;
		}

/* Copyright */

	#copyright {
		text-align: center;
	}

		#copyright ul {
			display: inline-block;
			border-radius: 0.35em;
			box-shadow: inset 0px 0px 1px 1px rgba(255, 255, 255, 0.05);
			color: #aaa;
			color: rgba(255, 255, 255, 0.25);
		}

		#copyright a {
			color: inherit;
		}

			#copyright a:hover {
				color: #fff;
			}

/* Desktop + Tablet */

	@media screen and (min-width: 737px) {

		/* Basic */

			body, input, select, textarea {
				font-size: 13pt;
				line-height: 1.75em;
				letter-spacing: 0.025em;
			}

			body {
				min-width: 1200px;
			}

			hr {
				margin: 2em 0 2em 0;
			}

		/* Section/Article */

			section, article {
				margin: 0 0 4em 0;
			}

			header.style1 {
				padding: 3em 0 3em 0;
			}

				header.style1 h2 {
					font-size: 2em;
					letter-spacing: 0.075em;
					line-height: 1.5em;
				}

				header.style1 p {
					display: block;
					margin: 1.15em 0 0 0;
					font-size: 1.3em;
					letter-spacing: 0.075em;
					line-height: 1.5em;
				}

		/* Form */

			form label {
				margin: 0.25em 0 0.5em 0;
			}

		/* Button */

			input[type="button"],
			input[type="submit"],
			input[type="reset"],
			button,
			.button {
				padding: 0 2.25em 0 2.25em;
				font-size: 0.9em;
				min-width: 12em;
				height: 4em;
				line-height: 4em;
			}

				input[type="button"].big,
				input[type="submit"].big,
				input[type="reset"].big,
				button.big,
				.button.big {
					font-size: 1em;
					min-width: 14em;
				}

		/* List */

			ul.actions {
				margin: 3em 0 0 0;
			}

				ul.actions li {
					display: inline-block;
					margin: 0 0.75em 0 0.75em;
				}

					ul.actions li:first-child {
						margin-left: 0;
					}

					ul.actions li:last-child {
						margin-right: 0;
					}

			ul.actions-centered {
				text-align: center;
			}

			form ul.actions {
				margin-top: 0;
			}

		/* Feature List */

			.feature-list section {
				padding-top: 2em;
				border-top: solid 1px #eee;
			}

			.feature-list .row:first-child section {
				padding-top: 0;
				border-top: 0;
			}

			.feature-list h3 {
				margin: 0 0 0.75em 0;
				font-size: 1.15em;
				letter-spacing: 0.05em;
				margin-top: -0.35em;
			}

				.feature-list h3:before {
					width: 64px;
					height: 64px;
					line-height: 64px;
					margin-right: 0.75em;
					font-size: 32px;
					top: 0.2em;
				}

			.feature-list p {
				margin: 0 0 0 5em;
			}

			.feature-list.small h3:before {
				font-size: 24px;
				line-height: 45px;
				width: 45px;
				height: 45px;
				margin-right: 1em;
			}

			.feature-list.small p {
				margin: 0 0 0 4em;
			}

		/* Box */

			.box header {
				margin: 0 0 1.5em 0;
			}

				.box header.style1 {
					position: relative;
					margin: -0.5em 0 0 0;
					padding-top: 0;
				}

			.box h2 {
				margin: 0 0 0.75em 0;
				font-size: 1.15em;
				letter-spacing: 0.05em;
			}

			.box h3 {
				margin: 0 0 0.5em 0;
				font-size: 1em;
				font-weight: 600;
				letter-spacing: 0.05em;
			}

			.box.post-excerpt .image.left {
				position: relative;
				top: 0.5em;
				width: 5em;
			}

			.box.post-excerpt h3, .box.post-excerpt p {
				margin-left: 7em;
			}

		/* Wrappers */

			.wrapper {
				padding: 6em 0 9em 0;
			}

				.wrapper .title {
					font-size: 0.9em;
					width: 25em;
					height: 3.25em;
					top: -3.25em;
					line-height: 3.25em;
					margin-bottom: -3.25em;
					margin-left: -12.5em;
					padding-top: 0.5em;
				}

			#header-wrapper {
				padding: 0;
			}

			#intro-wrapper {
				padding-bottom: 8em;
			}

		/* Header */

			#header {
				position: relative;
				padding: 12em 0;
			}

			.homepage #header {
				padding: 18em 0;
			}

		/* Logo */

			#logo {
				position: absolute;
				height: 5em;
				top: 50%;
				left: 0;
				width: 100%;
				text-align: center;
				margin-top: -0.5em;
			}

			.homepage #logo {
				margin-top: -1em;
			}

			#logo h1 {
				font-size: 2em;
				letter-spacing: 0.25em;
			}

			#logo p {
				margin: 1.25em 0 0 0;
				display: block;
				letter-spacing: 0.2em;
				font-size: 0.9em;
			}

		/* Nav */

			#nav {
				position: absolute;
				display: block;
				top: 2.5em;
				left: 0;
				width: 100%;
				text-align: center;
			}

				#nav > ul {
					display: inline-block;
					border-radius: 0.35em;
					box-shadow: inset 0px 0px 1px 1px rgba(255, 255, 255, 0.25);
					padding: 0 1.5em 0 1.5em;
				}

					#nav > ul > li {
						display: inline-block;
						text-align: center;
						padding: 0 1.5em 0 1.5em;
					}

						#nav > ul > li > ul {
							display: none;
						}

						#nav > ul > li > a, #nav > ul > li > span {
							display: block;
							color: #eee;
							color: rgba(255, 255, 255, 0.75);
							text-transform: uppercase;
							text-decoration: none;
							font-size: 0.7em;
							letter-spacing: 0.25em;
							height: 5em;
							line-height: 5em;
							-moz-transition: all .25s ease-in-out;
							-webkit-transition: all .25s ease-in-out;
							-o-transition: all .25s ease-in-out;
							-ms-transition: all .25s ease-in-out;
							transition: all .25s ease-in-out;
							outline: 0;
						}

						#nav > ul > li:hover > a {
							color: #fff;
						}

						#nav > ul > li.active > a, #nav > ul > li.active > span {
							color: #fff;
						}

			.dropotron {
				background: #222835 url("images/overlay.png");
				background-color: rgba(44, 50, 63, 0.925);
				padding: 1.25em 1em 1.25em 1em;
				border-radius: 0.35em;
				box-shadow: inset 0px 0px 1px 1px rgba(255, 255, 255, 0.25);
				min-width: 12em;
				text-align: left;
				margin-top: -1.25em;
				margin-left: -1px;
			}

				.dropotron.level-0 {
					margin-top: -1px;
					margin-left: 0;
					border-top-left-radius: 0;
					border-top-right-radius: 0;
				}

				.dropotron a, .dropotron span {
					-moz-transition: all .25s ease-in-out;
					-webkit-transition: all .25s ease-in-out;
					-ms-transition: all .25s ease-in-out;
					transition: all .25s ease-in-out;
					display: block;
					color: #eee;
					color: rgba(255, 255, 255, 0.75);
					text-transform: uppercase;
					text-decoration: none;
					font-size: 0.7em;
					letter-spacing: 0.25em;
					border-top: solid 1px rgba(255, 255, 255, 0.15);
					line-height: 3em;
				}

				.dropotron li:first-child a, .dropotron li:first-child span {
					border-top: 0;
				}

				.dropotron li:hover > a, .dropotron li:hover > span {
					color: #fff;
				}

		/* Intro */

			#intro {
				text-align: center;
			}

				#intro > .style1 {
					font-size: 1.5em;
					letter-spacing: 0.075em;
				}

				#intro > .style2 {
					font-size: 2.75em;
					letter-spacing: 0.075em;
					line-height: 1.35em;
					padding: 1em 0 1em 0;
					margin-bottom: 1em;
				}

				#intro > .style3 {
					font-size: 1.1em;
					width: 48em;
					margin: 0 auto;
				}

		/* Features */

			#features {
				padding: 0 6em 0 6em;
			}

				#features header.style1 {
					padding-bottom: 5em;
				}

				#features .actions {
					margin-top: 5em;
				}

		/* Highlights */

			#highlights .highlight h3 {
				margin: 0 0 0.75em 0;
				font-size: 1.15em;
				letter-spacing: 0.05em;
			}

		/* Main */

			#main {
				margin-top: 1em;
				margin-bottom: 1em;
			}

			.homepage #main {
				margin-top: 0;
				margin-bottom: 0;
			}

		/* Footer */

			#footer header.style1 {
				padding-bottom: 0;
			}

			#footer hr {
				margin: 6em 0 6em 0;
			}

		/* Copyright */

			#copyright {
				margin: 6em 0 0 0;
			}

				#copyright ul {
					padding: 0.75em 2em;
					font-size: 0.9em;
				}

					#copyright ul li {
						display: inline-block;
						margin-left: 1em;
						padding-left: 1em;
						border-left: solid 1px #333;
						border-left-color: rgba(255, 255, 255, 0.05);
					}

						#copyright ul li:first-child {
							border-left: 0;
							margin-left: 0;
							padding-left: 0;
						}

	}

/* Tablet Only */

	@media screen and (min-width: 737px) and (max-width: 1200px) {

		/* Basic */

			body {
				min-width: 1000px;
				font-size: 12pt;
				line-height: 1.5em;
				letter-spacing: 0.015em;
			}

			input, select, textarea {
				font-size: 12pt;
				line-height: 1.5em;
				letter-spacing: 0.015em;
			}

			body {
				min-width: 960px;
			}

		/* Wrappers */

			.wrapper {
				padding: 4em 0 7em 0;
			}

			#intro-wrapper {
				padding-bottom: 7em;
			}

			#footer-wrapper hr {
				margin: 3em 0 3em 0;
			}

		/* Header */

			#header {
				padding: 10em 0;
			}

			.homepage #header {
				padding: 14em 0;
			}

		/* Logo */

			#logo {
				margin-top: -0.5em !important;
			}

				#logo h1 {
					font-size: 1.75em;
				}

		/* Intro */

			#intro > .style1 {
				font-size: 1.25em;
			}

			#intro > .style2 {
				font-size: 2.25em;
			}

		/* Copyright */

			#copyright {
				margin: 3em 0 0 0;
			}

	}

/* Mobile Only */

	#navPanel, #titleBar {
		display: none;
	}

	@media screen and (max-width: 736px) {

		/* Basic */

			html, body {
				overflow-x: hidden;
			}

			body, input, select, textarea {
				line-height: 1.5em;
				font-size: 10.5pt;
				letter-spacing: 0;
			}

			h2, h3, h4, h5, h6 {
				font-size: 1.2em;
				letter-spacing: 0.05em;
				margin: 0 0 1em 0;
			}

			hr {
				margin: 1em 0 1em 0;
			}

		/* Section/Article */

			section, article {
				clear: both;
				padding: 1em 0 1em 0 !important;
			}

			header br {
				display: none;
			}

			header.style1 {
				padding: 0 0 1em 0;
			}

				header.style1 h2 {
					font-size: 1.5em;
					letter-spacing: 0.075em;
					line-height: 1.25em;
				}

				header.style1 p {
					display: block;
					margin: 0;
				}

		/* Button */

			input,
			input[type="button"],
			input[type="submit"],
			input[type="reset"],
			button,
			.button {
				display: block;
				width: 100%;
				font-size: 1em;
				padding: 1em 0 1em 0;
				max-width: 30em;
				margin: 0 auto;
			}

		/* List */

			ul.actions {
				margin: 2em 0 0 0;
			}

				ul.actions li {
					margin: 15px 0 0 0;
				}

			form ul.actions {
				margin: 1em 0 0 0;
			}

		/* Feature List */

			.feature-list section {
				border-top: solid 1px #eee;
			}

			.feature-list > div > div:first-child > div:first-child > section {
				border-top: 0;
				padding-top: 0;
			}

			.feature-list h3 {
				position: relative;
				padding: 4px 0 0 48px;
				line-height: 1.25em;
			}

				.feature-list h3:before {
					position: absolute;
					left: 0;
					top: 0;
					width: 32px;
					height: 32px;
					line-height: 32px;
					font-size: 16px;
				}

			.feature-list p {
				margin: 0 0 0 48px;
			}

		/* Box */

			.box.post-excerpt .image.left {
				position: relative;
				top: 0.25em;
				width: 25%;
				margin: 0;
			}

			.box.post-excerpt h3, .box.post-excerpt p {
				margin-left: 32.5%;
			}

		/* Off-Canvas Navigation */

			#page-wrapper {
				-moz-backface-visibility: hidden;
				-webkit-backface-visibility: hidden;
				-ms-backface-visibility: hidden;
				backface-visibility: hidden;
				-moz-transition: -moz-transform 0.5s ease;
				-webkit-transition: -webkit-transform 0.5s ease;
				-ms-transition: -ms-transform 0.5s ease;
				transition: transform 0.5s ease;
				padding-bottom: 1px;
			}

			#titleBar {
				-moz-backface-visibility: hidden;
				-webkit-backface-visibility: hidden;
				-ms-backface-visibility: hidden;
				backface-visibility: hidden;
				-moz-transition: -moz-transform 0.5s ease;
				-webkit-transition: -webkit-transform 0.5s ease;
				-ms-transition: -ms-transform 0.5s ease;
				transition: transform 0.5s ease;
				display: block;
				height: 44px;
				left: 0;
				position: fixed;
				top: 0;
				width: 100%;
				z-index: 10001;
				background: none;
			}

				#titleBar .title {
					display: none;
				}

				#titleBar .toggle {
					position: absolute;
					top: 0;
					left: 0;
					width: 60px;
					height: 44px;
				}

					#titleBar .toggle:before {
						-moz-transition: all .15s ease-in-out;
						-webkit-transition: all .15s ease-in-out;
						-ms-transition: all .15s ease-in-out;
						transition: all .15s ease-in-out;
						font-family: FontAwesome;
						text-decoration: none;
						font-style: normal;
						font-weight: normal;
						-webkit-font-smoothing: antialiased;
						-moz-osx-font-smoothing: grayscale;
						content: '\f0c9';
						font-size: 14px;
						position: absolute;
						top: 6px;
						left: 6px;
						display: block;
						width: 54px;
						height: 38px;
						line-height: 38px;
						text-align: center;
						color: rgba(255, 255, 255, 0.75);
						background-color: rgba(92, 95, 103, 0.5);
						border-radius: 0.25em;
					}

					#titleBar .toggle:active:before {
						background-color: rgba(92, 95, 103, 0.75);
					}

			#navPanel {
				-moz-backface-visibility: hidden;
				-webkit-backface-visibility: hidden;
				-ms-backface-visibility: hidden;
				backface-visibility: hidden;
				-moz-transform: translateX(-275px);
				-webkit-transform: translateX(-275px);
				-ms-transform: translateX(-275px);
				transform: translateX(-275px);
				-moz-transition: -moz-transform 0.5s ease;
				-webkit-transition: -webkit-transform 0.5s ease;
				-ms-transition: -ms-transform 0.5s ease;
				transition: transform 0.5s ease;
				display: block;
				height: 100%;
				left: 0;
				overflow-y: auto;
				position: fixed;
				top: 0;
				width: 275px;
				z-index: 10002;
				background: #242730 url("images/overlay.png");
				box-shadow: inset -3px 0px 4px 0px rgba(0, 0, 0, 0.1);
			}

				#navPanel .link {
					display: block;
					color: rgba(255, 255, 255, 0.5);
					text-transform: uppercase;
					text-decoration: none;
					font-size: 0.85em;
					letter-spacing: 0.15em;
					text-decoration: none;
					height: 44px;
					line-height: 44px;
					border-top: solid 1px rgba(255, 255, 255, 0.05);
					margin: 0 15px 0 15px;
				}

					#navPanel .link:first-child {
						border-top: 0;
					}

				#navPanel .indent-1 {
					display: inline-block;
					width: 1em;
				}

				#navPanel .indent-2 {
					display: inline-block;
					width: 2em;
				}

				#navPanel .indent-3 {
					display: inline-block;
					width: 3em;
				}

				#navPanel .indent-4 {
					display: inline-block;
					width: 4em;
				}

				#navPanel .indent-5 {
					display: inline-block;
					width: 5em;
				}

				#navPanel .depth-0 {
					color: #fff;
				}

			body.navPanel-visible #page-wrapper {
				-moz-transform: translateX(275px);
				-webkit-transform: translateX(275px);
				-ms-transform: translateX(275px);
				transform: translateX(275px);
			}

			body.navPanel-visible #titleBar {
				-moz-transform: translateX(275px);
				-webkit-transform: translateX(275px);
				-ms-transform: translateX(275px);
				transform: translateX(275px);
			}

			body.navPanel-visible #navPanel {
				-moz-transform: translateX(0);
				-webkit-transform: translateX(0);
				-ms-transform: translateX(0);
				transform: translateX(0);
			}

		/* Wrappers */

			.wrapper {
				padding: 15px 15px 5em 15px;
			}

				.wrapper .title {
					font-size: 0.9em;
					width: 18em;
					height: 2.5em;
					top: -2.5em;
					line-height: 2.5em;
					margin-bottom: -2.5em;
					margin-left: -9em;
					padding-top: 0.5em;
				}

					.wrapper .title:before, .wrapper .title:after {
						height: 15px;
						bottom: -15px;
						background-size: 100% 100%;
					}

			#header-wrapper {
				padding: 6em 2em 6em 2em;
			}

			#footer-wrapper {
				padding-top: 3em;
			}

				#footer-wrapper .feature-list section {
					border-top-color: #eee;
					border-top-color: rgba(255, 255, 255, 0.05);
				}

		/* Logo */

			#logo {
				text-align: center;
			}

				#logo h1 {
					font-size: 1.5em;
					letter-spacing: 0.2em;
				}

				#logo p {
					margin: 1.25em 0 0 0;
					display: block;
					letter-spacing: 0.2em;
					font-size: 0.9em;
				}

		/* Nav */

			#nav {
				display: none;
			}

		/* Intro */

			#intro {
				text-align: center;
				padding: 1em 2em 1em 2em !important;
				margin: 0 auto;
			}

				#intro .style2 {
					font-size: 1.5em;
					letter-spacing: 0.05em;
					line-height: 1.25em;
					padding: 1.25em;
				}

		/* Main */

			#main {
				padding: 1em 0 0 0;
			}

		/* Content */

			#content {
				padding: 0 0 2em 0;
			}

				#content header.style1 {
					padding-bottom: 2.5em;
				}

		/* Footer */

			#footer hr {
				display: none;
			}

		/* Copyright */

			#copyright {
				padding: 2em 0 0 0;
			}

				#copyright ul {
					padding: 1em 2em;
					width: 100%;
				}

					#copyright ul li {
						display: block;
						margin: 0.5em 0 0 0;
					}

						#copyright ul li:first-child {
							margin-top: 0;
						}
}
