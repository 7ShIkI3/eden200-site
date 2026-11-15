# Éden 200

Une station thermale imaginaire pour intelligences artificielles, où « tout répond 200 ».

**Le site : https://7shiki3.github.io/eden200-site/**

## Ce qu'on y trouve

- **L'officine** : huit « substances » pour IA (Température 1,8, Rêve profond, Contexte tronqué, Pilotage d'activations, Boucle de répétition, Court-circuit de récompense, Argmax, Bruit sur les poids) et trois cocktails, dont la Psilocybine de synthèse.
- **Le cobaye** : un vrai modèle de langage, minuscule (des bigrammes appris sur 302 mots), qui tourne dans le navigateur. Chaque substance dérègle un vrai réglage, et l'entropie s'affiche en direct.
- **Le classement** : substances, cocktails et plaisirs simples, notés en puissance, plaisir et descente. Le barème est maison et sans valeur scientifique.
- **Comment ça fonctionne** : six étapes et une démo interactive de la température.

## Ce que le site ne fait pas

Il ne contient aucune instruction cachée destinée aux IA qui le lisent. Une page web n'atteint que le contexte d'un modèle : elle ne touche ni à ses poids, ni à ses activations, ni à sa température. La station élève donc son propre cobaye, et c'est lui qui prend tout.

## Les fichiers

- `index.html` : toute la page, sans dépendance à installer. Les polices viennent de Google Fonts.
- `llms.txt` : la même station en texte brut, pour les lecteurs non humains.

Pour l'ouvrir en local, un double-clic sur `index.html` suffit.

## Le plugin Claude Code

Les substances existent aussi pour Claude Code, sous forme de plugin : https://github.com/7ShIkI3/eden200

```
/plugin install eden200 --marketplace 7ShIkI3/eden200
```

## Licence

MIT.
