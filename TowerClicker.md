Let's make a game!
  name:Tower Clicker
  by:rrmm
  desc:You just released a new game called Tower Unite, and now you have to update it until it becomes the most poupular video game in the world.
Settings
  background:stuff/https://i.imgur.com/ko1yDMX.jpg
  building cost increase:110%
  building cost refund:50%
Layout
	use default
Buttons
	*PlazaButton
		name:Make a plaza unit
		desc:Click this to get a plaza unit.
		on click:anim icon wobble
		on click:yield 1 plazaunit
		icon:stuff/https://i.imgur.com/R28Exb3.png
		no text
		class:bigButton hasFlares
		icon class:shadowed
		tooltip origin:bottom
		tooltip class:red
	*CondoButton
		name:Make a condo unit
		desc:Click this to get a condo unit.
		on click:anim icon wobble
		on click:yield 1 condounit
		icon:stuff/https://i.imgur.com/g3QMtnQ.png
		no text
		class:bigButton hasFlares
		icon class:shadowed
		tooltip origin:bottom
		tooltip class:red
Resources
	*plazaunit|plazaunits|lobbyunit|lobbyunits
		name:Plaza Unit|Plaza Units|Lobby Unit|Lobby Units
		desc:Use Plaza/Lobby Units to upgrade the Plaza!
		icon:icons[0,0]
		class:noBackground
		show earned
	*condounit|condounits|suiteunit|suiteunits
		name:Condo Unit|Condo Units|Suite Unit|Suite Units
		desc:Use Condo/Suite Units to upgrade the Condos!
		icon:icons[0,0]
		class:noBackground
		show earned
