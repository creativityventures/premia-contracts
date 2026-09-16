# Prime, échéance et règlement

Les bibliothèques de mathématiques d’option encadrent la conversion entre strike, échéance, volatilité et prime. Les contrats distinguent les unités monétaires et les paramètres de marché afin de limiter les erreurs de précision.

Au règlement, la valeur intrinsèque dépend du sens de la position et du prix de référence. Le code doit aussi traiter l’expiration, les exercices et les cas sans valeur. Ces points constituent les invariants à vérifier lors d’une revue.

Suite : [pools et liquidité](./03-pools-liquidite.md).
