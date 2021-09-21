<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8" />
		<meta http-equiv="X-UA-Compatible" content="IE=edge" />
		<meta name="viewport" content="width=device-width, initial-scale=1.0" />
		<title>Stardate</title>

		<style>
			* {
				margin: 0;
				padding: 0;
				box-sizing: border-box;
			}
			html,
			body {
				width: 100vw;
				height: 100vh;
			}
			#monitor {
				position: fixed;
				top: 0;
				left: 0;
				width: 100vw;
				height: 100vh;
				display: flex;
				padding: 15px;
				background: #eee;
				border: 1px solid #ccc;
				font-family: Futura, "Trebuchet MS", Arial, sans-serif;
			}

			#monitor div {
				flex: 1;
			}

			.palette {
				list-style: none;
				width: 200px;
				overflow: hidden;
			}

			.palette li {
				margin: 1px;
				padding: 5px;
				font-size: 10px;
			}

			h2 {
				font-size: 12px;
				margin: 0.5em 0;
				color: #ccc;
			}
			h3 {
				font-size: 10px;
				margin: 0.5em 0;
			}
			p {
				font-size: 10px;
			}
		</style>
	</head>
	<body>
		<div id="monitor">
			<div>
				<div>
					<h3><strong>Date: </strong> <span id="date-1"></span></h3>

					<h3>
						<strong>Timestamp: </strong>
						<span id="time-1"></span>
					</h3>

					<h3>
						<strong>Location:</strong>
						<span id="longitude-1"></span>
						<span id="latitude-1"></span>
					</h3>
				</div>
				<div>
					<h3>Palette</h3>
					<ul class="palette" id="palette-1"></ul>
				</div>
			</div>
			<div>
				<div>
					<h3><strong>Date: </strong> <span id="date-2"></span></h3>

					<h3>
						<strong>Timestamp: </strong>
						<span id="time-2"></span>
					</h3>

					<h3>
						<strong>Location:</strong>
						<span id="longitude-2"></span>
						<span id="latitude-2"></span>
					</h3>
				</div>
				<div>
					<h3>Palette</h3>
					<ul class="palette" id="palette-2"></ul>
				</div>
			</div>
			<div>
				<div>
					<h3><strong>Date: </strong> <span id="date-3"></span></h3>

					<h3>
						<strong>Timestamp: </strong>
						<span id="time-3"></span>
					</h3>

					<h3>
						<strong>Location:</strong>
						<span id="longitude-3"></span>
						<span id="latitude-3"></span>
					</h3>
				</div>
				<div>
					<h3>Palette</h3>
					<ul class="palette" id="palette-3"></ul>
				</div>
			</div>
		</div>
		<script>
			//Static input

			const input = [
				{
					date: "01.01.13",
					time: 198250476,
					location: {
						long: 51.445935659134356,
						lat: 0.20976172627133266,
					},
				},
				{
					date: "17.05.1983",
					time: 198250476,
					location: {
						long: 51.445935659134356,
						lat: 0.20976172627133266,
					},
				},
				{
					date: "29.10.9903",
					time: 198250476,
					location: {
						long: 51.445935659134356,
						lat: 0.20976172627133266,
					},
				},
			];

			let palettes = [[], [], [], []];

			//Generate palette
			input.map((input, index) => {
				const generatePalette = (testNo) => {
					const splitAt = (index) => (x) =>
						[x.slice(0, index), x.slice(index)];
					let dateArray = input.date.split("."),
						dateArray2 = splitAt(2)(dateArray[2]),
						century = dateArray2[0],
						year = dateArray2[1],
						month = dateArray[1],
						day = dateArray[0],
						colorRanges = [[], [], [], []],
						exclusionRange;
					exclusionAmount = 300;

					colorRanges.map((item, index) => {
						switch (index) {
							case 0:
								exclusionRange = Math.floor(360 / century);
								break;
							case 1:
								exclusionRange = Math.floor(360 / year);
								break;
							case 2:
								exclusionRange = Math.floor(360 / month);
								break;
							case 3:
								exclusionRange = Math.floor(360 / day);
								break;
							default:
								// console.log("Falling through");
								break;
						}

						for (let i = 1; i < 360; i++) {
							if (
								i < exclusionRange ||
								i > exclusionRange + exclusionAmount
							) {
								colorRanges[index].push(i);
							}
						}
						// console.log("colorRanges[index]: ", colorRanges[index]);
					});

					for (let sp = 1; sp < 5; sp++) {
						//How many sub-palettes we want

						for (let i = 0; i < 3; i++) {
							//How many colours we want in each sub-palette
							let hue = null,
								sat = null,
								lig = null;

							switch (sp) {
								case 1:
									hue =
										colorRanges[0][
											Math.floor(
												Math.random() *
													colorRanges[0].length
											)
										];
									sat = Math.floor(
										Math.random() * (25 - 1) + 1 //Between 1 and 25
									);
									lig = Math.floor(
										Math.random() * (100 - 75) + 75 //Between 75 and 100
									);
									break;
								case 2:
									hue =
										colorRanges[1][
											Math.floor(
												Math.random() *
													colorRanges[1].length
											)
										];
									sat = Math.floor(
										Math.random() * (50 - 26) + 26 //Between 26 and 50
									);
									lig = Math.floor(
										Math.random() * (75 - 51) + 51 //Between 51 and 75
									);
									break;
								case 3:
									hue =
										colorRanges[2][
											Math.floor(
												Math.random() *
													colorRanges[2].length
											)
										];
									sat = Math.floor(
										Math.random() * (75 - 51) + 51 //Between 51 and 75
									);
									lig = Math.floor(
										Math.random() * (50 - 26) + 26 //Between 26 and 50
									);
									break;
								case 4:
									hue =
										colorRanges[3][
											Math.floor(
												Math.random() *
													colorRanges[3].length
											)
										];
									sat = Math.floor(
										Math.random() * (100 - 75) + 75 //Between 75 and 100
									);
									lig = Math.floor(
										Math.random() * (25 - 1) + 1 //Between 1 and 25
									);
									break;
							}

							const colorHSL = `hsl(${hue},${sat}%,${lig}%)`;

							function hslToHex(h, s, l) {
								l /= 100;
								const a = (s * Math.min(l, 1 - l)) / 100;
								const f = (n) => {
									const k = (n + h / 30) % 12;
									const color =
										l -
										a *
											Math.max(
												Math.min(k - 3, 9 - k, 1),
												-1
											);
									return Math.round(255 * color)
										.toString(16)
										.padStart(2, "0"); // convert to Hex and prefix "0" if needed
								};
								return `#${f(0)}${f(8)}${f(4)}`;
							}
							const colorHEX = hslToHex(hue, sat, lig);

							const date = document.getElementById(
								`date-${testNo}`
							);
							date.innerText = input.date;

							const time = document.getElementById(
								`time-${testNo}`
							);
							time.innerText = input.time;

							const long = document.getElementById(
								`longitude-${testNo}`
							);
							long.innerText = `${input.location.long},`;

							const lat = document.getElementById(
								`latitude-${testNo}`
							);
							lat.innerText = input.location.lat;

							const palette = document.getElementById(
								`palette-${testNo}`
							);

							let html = document.createElement("li");
							html.style.backgroundColor = colorHSL;
							html.innerText = `${sp} - ${colorHSL}`;
							palette.appendChild(html);

							palettes[sp - 1].push({
								hsl: colorHSL,
								colorHex: colorHEX,
							});
						}
					}
				};
				generatePalette(index + 1);
			});

			console.log({ palettes });

			//Generate elements base on static input?
			//Allow webcam input?
		</script>
	</body>
</html>
