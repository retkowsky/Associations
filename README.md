# Associations

Associations rules using Azure ML.

•	L’indice de support : mesure la fréquence d’apparition de A et B sur un même ticket (nombre de tickets avec A et B/nombre total de tickets)<br>
•	L’indice de confiance : probabilité d’apparition de B sur les tickets comprenant A (nombre de tickets avec A et B/nombre de tickets avec A)<br>
•	Le levier ou le lift : le poids relatif de cette association compte tenu de la fréquence d’apparition naturelle de B<br>
<br>
Le lift quantifie l’effet levier entre deux produits.<br>
•	Lift>1 l’achat du produit A induit une plus forte probabilité d’achat du produit B<br>
•	Lift<1 l’achat du produit A induit une plus faible probabilité d’achat du produit B<br>
<br>
Dans la pratique, seules les valeurs éloignées de 1 sont intéressantes.
Le lift est souvent utilisé, mais il n’informe pas sur la valeur exacte de l’association entre deux produits. Il doit être complété par les autres indicateurs.
<br>
Le support révèle la fréquence d’apparition d’une association :<br>
•	L’association se réalise souvent lorsque la valeur du support est élevée (et inversement) Si le lift est élevé mais que l’indice de support est faible, alors l’association est forte mais se réalise peu souvent.<br>
•	La confiance quantifie en terme probabiliste l’association. C’est l’indicateur le plus souvent retenu pour illustrer finement l’association de produits.<br>
•	Lorsque le lift et le support sont élevés (>1%), l’indice de confiance prend alors toute sa signification. C’est le révélateur du pouvoir de prédiction de l’achat de B sachant A.<br>

Association forte et pertinente = support élevé, lift supérieur à 1, et confiance la plus élevée possible.<br>


Azure ML Service: https://azure.microsoft.com/en-us/services/machine-learning-service/

Serge Retkowsky | serge.retkowsky@microsoft.com | https://www.linkedin.com/in/serger/
