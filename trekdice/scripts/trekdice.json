Hooks.on('diceSoNiceReady', (dice3d) => {

	dice3d.addTexture("colourdifference", {
	    name: "⁂ Colour Dodge",
	    composite: "difference",
	    source: "modules/trekdice/textures/bark.webp",
        bump: "modules/trekdice/textures/barkb.webp"
	});

  dice3d.addSystem({id:"TrekDice",name:"⁂ Star Trek Adventures (d20, 1 best)"},false);

  dice3d.addDicePreset({
    type:"d20",
    labels:[
      'No','2','3','4','5','6','7','8','9','10','11','12','13','14','15','16','17','18','19',
      'modules/trekdice/faces/sta20.webp'
    ],
    system:"Dragon20"
  });


  dice3d.addSystem({id:"TrekDice",name:"⁂ Star Trek Adventures (d6, special)"},false);

  dice3d.addDicePreset({
    type:"d6",
    labels:[
      'modules/trekdice/faces/sta/d6-1.webp',
      'modules/trekdice/faces/sta/d6-2.webp',
      'modules/trekdice/faces/sta/d6-3.webp',
      'modules/trekdice/faces/sta/d6-4.webp',
      'modules/trekdice/faces/sta/d6-5.webp',
      'modules/trekdice/faces/sta/d6-6.webp'
    ],
	system:"TrekDice"
  });

  dice3d.addSystem({id:"GMDice",name:"⁂ GM Dice (d20)"},false);

  dice3d.addDicePreset({
    type:"d20",
    labels:[
      'modules/trekdice/faces/gmdice/d20/d20-ehhmaybe.webp',
      'modules/trekdice/faces/gmdice/d20/d20-skull1.webp',
      'modules/trekdice/faces/gmdice/d20/d20-skull2.webp',
      'modules/trekdice/faces/gmdice/d20/d20-skull3.webp',
      'modules/trekdice/faces/gmdice/d20/d20-skull1.webp',
      'modules/trekdice/faces/gmdice/d20/d20-skull2.webp',
      'modules/trekdice/faces/gmdice/d20/d20-death.webp',
      'modules/trekdice/faces/gmdice/d20/d20-nottoday.webp',
      'modules/trekdice/faces/gmdice/d20/d20-playerdeath.webp',
      'modules/trekdice/faces/gmdice/d20/d20-skull3.webp',
      'modules/trekdice/faces/gmdice/d20/d20-skull1.webp',
      'modules/trekdice/faces/gmdice/d20/d20-skull2.webp',
      'modules/trekdice/faces/gmdice/d20/d20-skull3.webp',
      'modules/trekdice/faces/gmdice/d20/d20-skull1.webp',
      'modules/trekdice/faces/gmdice/d20/d20-20.webp',
      'modules/trekdice/faces/gmdice/d20/d20-25.webp',
      'modules/trekdice/faces/gmdice/d20/d20-77.webp',
      'modules/trekdice/faces/gmdice/d20/d20-66.webp',
      'modules/trekdice/faces/gmdice/d20/d20-tpk.webp',
      'modules/trekdice/faces/gmdice/d20/d20-youdie.webp'
    ],
    system:"GMDice"
  });
});
