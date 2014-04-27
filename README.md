axihaum
=======

Ce dépôt contient les fichiers concernant la fraiseuse numérique du HAUM, basée sur une LPKS ProtoMat 91s.

Des photos de la LPKS ProtoMat 91S telle que nous l'avons reçu sont disponibles ici:
https://secure.flickr.com/photos/111893015@N07/sets/72157638807824124/

Quelques régles de nommage:
Les fichiers DXF ainsi que les couches (DXF et FreeCAD) sont nommé de la façon suivante:

Y_P_L.dxf

 - où Y est l'initiale la partie concernée (X, Y, Z et C pour le chassis)
 - où P est l'initiale de la sous-partie concernée (Part, Guide, Screw)
 - où L est l'initiale du coté concerné (Left, Right, Up, Down)

Les axes X, Y et Z sont nommé du plus grand (X) au plus petit (Z).
Note: dans la version originale, Z n'est pas motorisé.

Pour le nommage et les vues, on considère la fraiseuse vue de face dans le prolongement de l'axe X (axe le plus long), l'axe Y étendu de gauche à droite, Z de haut en bas.

Fichiers:

 * DXF (2D)
   - X_SY_RT: X, Support for Y, Right Top (also used as Left in 3D)
   - X_SY_LM: X, Support for Y, Left Middle
   - X_SY_RM: X, Support for Y, Right Middle
   - X_SY_B: X, Support for Y, Bottom
   - Y_P_L: Y, Part, Left
   - Y_P_R: Y, Part, Right
   - C_T: Case, Table

 * FreeCAD (3D)
   - axihaum: modèlisation de la LPKS ProtoMat 91s
   - C_T: Chassic, Table
   - A_LB: Accessories, Linear Bearing
   - A_M: Accessories, NEMA23 Motor
   - A_C_NEMA23: Accessories, NEMA23 coupler (D6.35 -> D8)
   - A_T: Accessories, Transmission (with Top, Left/Right, Bottom as separate files)
   - Z_P: Z, Panel
   - Z_S: Z, Support

Notes:
 * les premières parties de la modèlisation 3D ont été réalisées à partir d'imports de DXF, extrudés et soustraits.
 * les pièces suivantes (à partir de C_T) utilisent les esquisses 2D intégré dans FreeCAD. Les fichiers DXF correspondant peuvent être crées au besoin.
