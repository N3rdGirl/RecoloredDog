# Dog Substitution
Substitutes two dogs in stardew valley
I have configured the mod to change the look of dog1.xnb and dog2.xnb to what is basically my dogs. To actually get the changed animal you need to select either the 2nd dog option or 3rd when creating a new farm, or if you feel adventureous, you can change the content.json to pick whichever pet you want.

To change it you would need to look at this specific section of the content.json
   "Changes": [
      {
         "Action": "Load",
         "Target": "Animals/dog1",
         "FromFile": "assets/Java.png"
      },
      {
      "Action": "Load",
      "Target": "Animals/dog2",
      "FromFile": "assets/Boo.png"
      }
    ]

From there you would change "dog2" to which ever animal you want it to be(dog, dog1, dog2, cat, cat1, cat2 etc etc)
