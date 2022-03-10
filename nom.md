# nom 

## @showdialog
 
Faire défiler ton nom avec les lumières DEL sur le Micro:Bit!
 
![RECIT](https://drive.google.com/uc?id=1AYOnOTuePsS1n7_WV3uRIGQeXu8lIP1F)
 
## Step 1 @fullscreen
 
Bienvenue! Place le bloc ``||basic:afficher texte ""||`` dans l'emplacement ``||basic:toujours||`` pour faire défiler ton nom.
 
```blocks
basic.forever(function () {
    basic.showString("Mon prénom")
})
```
 
## Step 2 @fullscreen
 
Tu peux utiliser le bloc ``||basic:montrer l'icône||`` à la suite de ton nom dans l'emplacement  ``||basic:toujours||`` pour afficher une icône. Il y a plusieurs choix d'icône!
 
```blocks
basic.forever(function () {
    basic.showString("Mon prénom")
    basic.showIcon(IconNames.Heart)
})
```
 
## Step 3 @fullscreen
👍 Super! Tu devrais voir ton nom et ton icône défiler dans le simulateur du Micro:Bit. Clique sur «Terminer» pour voir ton nouveau projet dans l'interface MakeCode.
