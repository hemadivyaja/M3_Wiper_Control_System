**<h1>FINAL REPORT:<h1>**

<h1>ABSTRACT:</h1>

Vehicle windshield wipers play a important role during extreme weather conditions by wiping the rain water, dust, fog, mist continuously over the course of time and they help us give a clear vision to the driver. Wipers are designed and made to clear the unwanted dust, water etc. from a windscreen. It is Prime duty to improve the safety facilities in all automobiles and vehicles. The system is used to activate the Wipers manually. Due to this issue many engineers and designers and developers have contributed to the research and developement of Automatic Windshield Wiper Functionality in automobiles. The Windshield Wiper Functionality of domestic cars primarily consists of three systems,

* Two wipers and theis respecive arms
* A mechanism
* An electronic Motor

The concept of this proposed wiper system is similar to that of all the other exesting wiper systems. A wiper normally consists of metal arm, one end pivots and the other end has a long rubber blade-attached to it. The purpose of the project is to design the windshield wiper control system for the safetiness of the people who drive heavy automobiles and domestic four-wheeler vehicles.


<h1>RESEARCH PROGRESS:</h1>

The automated Wiper system is used to detect rainfall and activate the wiper system automatically without the drivers inuput contol


<h1>KEY TERMS:</h1>

* STM32 Discovery Board
* Microcontroller
* Electric Motor
* Wiper arm
* Wiper Blade

<h1>BASIC REQUIREMENTS:</h1>

<h2>INTRODUCTION:</h2>

Wiper system is a inseperable aspect is modern automobiles especially 4-wheelers. They are designed and made to clear the dust, water, fog, mist from the windshield and give driver a better and clear vision of the road ahead. The parts are visible from outside the car. It has a rubber blade made of silicon, wiper arm attached to the silicon blade, extendable linkage, pivots. Existing system used manually used to activate the wiper and the process of pulling up wiper and the driver needs to switch ON and OFF the control system.

<h2>OBJECTIVES:</h2>

* To design and implement a new mechanism to cover the area of automobile's windshield.
* The purpose of the wiper system is to clean the windshield effectively to provide clear vision for the driver.
* The system contains a microcontroller that takes input signals from the sensor and controls the operation.

<h1>4W's AND 1H:</h1>

<h2>WHAT:</h2>

* The windshield wiper sontrol system consists of wipers and wiper arms

<h2>WHEN:</h2>

* It can be used when there is rainfall, cleaning the winshield after a long time, dusty conditions etc.

<h2>WHERE:</h2>

* It is used to remove water, dirt, dust, smoke, fog, mist etc.

<h2>WHO:</h2>

* It is used by the drivers of heavy automobiles and domestic 4-wheelers.

<h2>HOW:</h2>

* They can be operated by electric motors.

<h2>SWOT ANALYSIS:</h2>

![swot](https://user-images.githubusercontent.com/101571637/167284529-6a3c261c-0a76-415f-9cc7-8f5a1e899f2f.png)


<h2>HIGH LEVEL REQUIREMENTS:</h2>



</head>
<body>
	<table>
		<thead>
			<tr>
				<th>I'D</th>
				<th>DESCRIPTION</th>
				<th>STATUS</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>&nbsp;HR_01</td>
				<td>Car in ACC mode&nbsp;</td>
				<td>Implemented&nbsp;</td>
			</tr>
			<tr>
				<td><span style="font-style: normal; font-weight: 400;">&nbsp;HR_02</span></td>
				<td>Car in ignition mode&nbsp;</td>
				<td>Implemented&nbsp;</td>
			</tr>
			<tr>
				<td>&nbsp;&nbsp;HR_03</td>
				<td>Turning on the wiper&nbsp;</td>
				<td>&nbsp;Implemented</td>
			</tr>
			<tr>
				<td>&nbsp;&nbsp;HR_04</td>
				<td>&nbsp;Turning off the wiper</td>
				<td>&nbsp;Implemented</td>
			</tr>
		</tbody>
	</table>
</body>
</html>


<h2>LOW LEVEL REQUIREMENTS:</h2>


</head>
<body>
	<table>
		<thead>
			<tr>
				<th>I'D</th>
				<th>DESCRIPTION</th>
				<th>STATUS</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>&nbsp;LR_01</td>
				<td>ON</td>
				<td>Implemented</td>
			</tr>
			<tr>
				<td>&nbsp;LR_02</td>
				<td>Press wiper switch&nbsp;</td>
				<td>&nbsp;Implemented</td>
			</tr>
			<tr>
				<td>&nbsp;LR_03</td>
				<td>Microcontroller supply</td>
				<td><span style="font-style: normal; font-weight: 400;">Implemented</span><br></td>
			</tr>
			<tr>
				<td>&nbsp;LR_04</td>
				<td>Activating wiper blades</td>
				<td><span style="font-style: normal; font-weight: 400;">Implemented</span><br></td>
			</tr>
			<tr>
				<td>&nbsp;LR_05</td>
				<td>OFF</td>
				<td><span style="font-style: normal; font-weight: 400;">Implemented</span>&nbsp;</td>
			</tr>
		</tbody>
	</table>
</body>
</html>

<H2>WIPER CONTROL SYSTEM:</H2>

<img width="445" alt="WIPER 2" src="https://user-images.githubusercontent.com/101571637/168222244-51c86c6f-6920-464a-9e2e-4c1bfb605bb4.PNG">

<H1>TEST PLAN:</H1>

* These are the necessary test plans for implementing this project.

<h2>HIGH LEVEL TEST PLAN:</h2>


<body>
	<table>
		<thead>
			<tr>
				<th>TEST I'D</th>
				<th>DESCRIPTION</th>
				<th>TEST TYPE</th>
				<th>OUTPUT EXPECTED</th>
				<th>FINAL STATUS</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>H_01&nbsp;</td>
				<td>Moving the wiper along windshield&nbsp;</td>
				<td>&nbsp;Secnario based test</td>
				<td>PASS&nbsp;</td>
				<td>&nbsp;IMPLEMENTED</td>
			</tr>
			<tr>
				<td>&nbsp;H_02</td>
				<td>wiper comes back to the rest position at the end&nbsp;</td>
				<td>Boundary value based test&nbsp;</td>
				<td>&nbsp;PASS</td>
				<td>IMPLEMENTED&nbsp;</td>
			</tr>
		</tbody>
	</table>
</body>
</html>






<h2>LOW LEVEL TEST PLAN:</h2>

<body>
	<table>
		<thead>
			<tr>
				<th>TEST I'D</th>
				<th>DESCRIPTION</th>
				<th>TEST TYPE</th>
				<th>OUTPUT EXPECTED</th>
				<th>FINAL STATUS</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>L_01&nbsp;</td>
				<td>Powering ON the Car</td>
				<td>&nbsp;Secnario based test</td>
				<td>PASS&nbsp;</td>
				<td>&nbsp;IMPLEMENTED</td>
			</tr>
			<tr>
				<td>&nbsp;L_02</td>
				<td>Powering OFF the Car</td>
				<td>Boundary value based test&nbsp;</td>
				<td>&nbsp;PASS</td>
				<td>IMPLEMENTED&nbsp;</td>
			</tr>
		</tbody>
	</table>
</body>
</html>


<h1>FINAL OUTPUTS:</h1>

<H2>1. EXECUTION WHEN BUTTON IS PRESSED ONCE FOR 2 SECONDS:</H2>

* Ignition mode and Car in ON

<img width="646" alt="pressed once for 2 sec" src="https://user-images.githubusercontent.com/101571637/168274481-bfc513bf-6374-4559-b423-9f6fb0c7d050.PNG">


<H2>2. EXECUTION WHEN BUTTON IS PRESSED ONCE AGAIN FOR 2 SECONDS:</H2>

* ACC mode and Car is OFF

<img width="625" alt="once again for 2 seconds" src="https://user-images.githubusercontent.com/101571637/168274842-ba783ee7-8224-4347-b81e-79bd894f1697.PNG">



<H2>3. EXECUTION WHEN BUTTON IS PRESSED FOR SECOND TIME:</H2>

* Turning ON the wiper

<img width="881" alt="Pressed for 2nd time" src="https://user-images.githubusercontent.com/101571637/168275072-0b2f84e9-75f2-4803-8ae4-9f6f778fe72f.PNG">



<H2>4. EXECUTION WHEN BUTTON IS PRESSED FOR THIRD TIME:</H2>

* Turning OFF the wiper
<img width="940" alt="pressed with third time" src="https://user-images.githubusercontent.com/101571637/168276097-0766399d-37ec-4bdd-851c-2799d9604d1e.PNG">





* This folder contains the final full report of this project. 
