Dtd
===

Listes des DTD et schémas officiels utilisés par Zephyr pour : 

 - ses sites propres
 - les sites de ses clients dont les schémas sont publics et intégrés dans les projets en cours de fonctionnement.

Utilisation
-----------

Cette centralisation permet la vérification et completion du code xml. La déclaration doit être faite suivant la nomenclature suivante :

	xmlns="https://raw.github.com/ZephyrHQ/Dtd"
    xmlns:xsd="http://www.w3.org/2001/XMLSchema"
    targetNamespace="https://raw.github.com/ZephyrHQ/Dtd"
	
Une DTD particulière peut être appelée avec l'adresse suivante : 

	https://raw.github.com/ZephyrHQ/Dtd/[chemin vers la DTD ou le fichier xsd]
	
Notes
-----

L'utilisation d'un dépot github public permet de conserver un accès ouvert au plus grand nombre.
