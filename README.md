 SYSCOHADA-CAMEROUN (V8)

        Le module sycohada_cameroun est un module devéloppé par Y-NOTE permettant pour de nouvelles instances de base de l'ERP Odoo,
    d'integrer directement les taxes et positions fiscales aux normes camerounaises pour la comptabilité OHADA.
    
    
    COMMENT DEPLOYER LE MODULE ?
    
        Le syscohada_cameroun ne génère pas directement des taxes lors de son installation.
    Il utilise le systeme mis en place par Odoo qui consiste à créer des templates de taxes et de codes qui seront ensuite utilisés pour générer des taxes et codes correspondants lors de l'installation du module de comptabilité.
    
        Placez le module dans votre repertoire addons. Vous pouvez commencer par installer le module account(Comptabilité), ensuite, l10n_syscohada(Plan comptable OHADA).
    L'installation du module l10n_syscohada installera par dépendance le module syscohada_cameroun. Lors de cette installation,
    Odoo vous propose de configurer la devise, les taxes d'achat et de vente par defaut. Vous trouverez les éléments suivants dans
    les listes proposées:
    -   Taxe de vente par defaut:
        -   TVA-VENTE
        -   TVAIS-RETENUE
        -   TVAIS-VENTE
        -   IS-RETENUE
        -   NONE
    
    -   Taxes d'achat par défaut:
        -   TVA-ACHAT
        -   TSR(Taxe Sur le Revenu)
        -   PRECOMPTE-IS
        -   NONE
    Une fois les changements appliqués, Odoo lancera l'opération de création des taxes et codes correspondants.
    
    NB: Si pendant l'installation du module du module l10n_syscohada, l'étape de configuration des taxes par defaut n'est pas affichée(ou est affichée mais les nouvelles taxes enoncées plus haut n'y figurent pas), vous pouvez annuler ce formulaire de configuration et vous rendre dans 'Configuration - Comptabilité' pour y effectuer les parametrages par défaut.
    
##############################################################################

    SYSCOHADA-CAMEROUN
    Copyright (c) Y-Note, All rights reserved.
    
    This library is free software; you can redistribute it and/or
    modify it under the terms of the GNU Lesser General Public
    License as published by the Free Software Foundation; either
    version 3.0 of the License, or (at your option) any later version.
    
    This library is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
    Lesser General Public License for more details.
    
    You should have received a copy of the GNU Lesser General Public
    License along with this library.

##############################################################################
