# PD-GARAGE-QBCore
Just Drag and drop script

You can config the ped location in the config file

Just drag it to your qb folder

Configed for MRPD

PD Bennys Modification included 

Not made by me ;)

Preiview - https://www.youtube.com/watch?v=lhTjFGfqzeE

Dependency- https://github.com/qbcore-framework/qb-target and 

Installation - 
Add this in your QBTarget Init or Config

Config.TargetModels = {
    ["PDGarage"] = {
		models = {
			`ig_trafficwarden`
		},
		options = {
			{
				event = "garage:menu",
				icon = "fas fa-shopping-cart",
				label = "Take out PD vehicle",
				job = "police",
				
			},
		},
		distance = 4.5,
