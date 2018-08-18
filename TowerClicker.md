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
		name:Make a unit
		desc:Click this to get a unit.
		on click:anim icon wobble
		on click:yield 1 unit
		icon:stuff/https://i.imgur.com/R28Exb3.png
		no text
		class:bigButton hasFlares
		icon class:shadowed
		tooltip origin:bottom
    tooltip class:red
