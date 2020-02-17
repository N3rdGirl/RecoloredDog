# RecoloredDog
Recolors the dog in stardew valley
I have configured the mod to change the look of dog2.xnb to a black dog with brownish paws. The look of the recolored dog matches very much my own dog. To actually get the changed animal you need to select the 3rd dog option when creating a new farm, or if you feel adventureous, you can change the content.json to pick whichever pet you want.

To change it you would need to look at this specific section of the content.json
"Changes": [
      {
      "Action": "Load",
      "Target": "Animals/dog2",
      "FromFile": "assets/MyDog.png"
      }
]
From there you would change "dog2" to which ever animal you want it to be(dog, dog1, dog2, cat, cat1, cat2 etc etc)
