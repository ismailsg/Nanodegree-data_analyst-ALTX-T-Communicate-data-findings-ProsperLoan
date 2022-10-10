# (Prosper Loan)
## by (Ismail Essagar)


## Dataset

> Cet ensemble de données contient des informations sur les prêts entre pairs facilités par la société de crédit Prosper. Il y a 113 937 prêts avec 81 variables. Aux fins de cette enquête, j'ai pris les 14 variables suivantes :'ListingNumber', 'Term', 'LoanStatus', 'BorrowerAPR', 'ProsperScore', 'ListingCategory (numeric)', 'EmploymentStatus', 'EmploymentStatusDuration', 'IsBorrowerHomeowner', 'DebtToIncomeRatio', 'StatedMonthlyIncome', 'LoanOriginalAmount', 'LoanOriginationDate', 'MonthlyLoanPayment'


## Summary of Findings

>      Le montant le plus présent est 4000. Généralement les montants les plus cités sont souvant inférieurs ou égals à 15000. Rarement que la durée des prêts est inférieur à un an , elle va jusqu'à 3 ans dans la plupart du temps et même 5 ans dans d'autre cas mais ce cas moins présents. Amélioration de l'habitat est la catégory qu'on trouve le plus pour les prêts. La plupart des emprunteurs sont des employés au moment de publier les prêts. On peut déduire que plus d'emprunteurs sont des propriètaires mais pas trop par rapport aux autres. La distribution des revenus mensuels est asymétrique à droite. Le revenu mensuel le plus fréquent des emprunteurs .semble être d'environ 5 000, le revenu mensuel de la plupart des États étant inférieur à 20 000. Le taux de l'emprunteur est négativement corrélé au montant initial du prêt, au ProsperScore et au paiement mensuel du prêt. Les emprunteurs dont le revenu mensuel est plus élevé ont des montants de prêt plus élevés. Les emprunteurs dont le revenu mensuel est plus élevé sont en mesure de rembourser des mensualités de prêt plus élevées. Plus le montant du prêt est élevé, plus le montant du remboursement mensuel est élevé . Il est évident que les emprunteurs non-propriétaires ont principalement prêté des montants compris entre 0 et 5 000 avec un maximum de 30 000. Alors que la plupart des propriétaires étaient répartis sur différents montants un peu élevés Les prêts à terme de 36 mois ont un taux de pourcentage annuel des emprunteurs compris entre 0 et 0,4 avec quelques valeurs aberrantes allant à 0,5, les prêts à terme de 60 mois sont davantage concentrés sur les montants de prêt les plus élevés et les BorrowerAPR entre 0,1 et 0,35, tandis que la durée du prêt de 12 mois est principalement pour les montants de prêt inférieurs avec un BorrowerAPR entre 0 et 0,35. Bien que le terme n'ait pas de relation significative avec la force des effets sur le taux annuel en pourcentage des emprunteurs. L'effet des conditions du prêt sur le paiement mensuel du prêt à rembourser en fonction du montant du prêt a été une découverte intéressante. Pour les prêts qui ne couvrent que 12 mois, les frais mensuels ont tendance à être plus élevés que les autres termes puisqu'il s'agit d'un terme plus court. Alors que les prêts sont plus étalés pour des durées de prêt de 60 mois.


## Key Insights for Presentation

> Pour ce projet, je me suis concentré sur l'exploration de la découverte des facteurs qui ont des effets sur le pourcentage du taux annuel des emprunteurs.

>  Tout d'abord, j'ai sélectionné 14 variables sur les 81 variables d'origine, puis j'ai commencé à explorer la distribution des variables une par une à l'aide de tracés d'histogrammes pour les variables continues et de counplots pour les variables discrètes et normales.

>  Pour l'analyse bivariée, j'ai d'abord utilisé une carte de corrélation pour donner un aperçu des variables qui ont toute forme de corrélation entre elles. Après cela, j'ai exploré ceux qui avaient une corrélation supérieure à 0,2 pour explorer leurs relations.

>   Ensuite, j'ai utilisé un graphique de régression par rapport au montant du prêt et au pourcentage du taux annuel de l'emprunteur car c'est le facteur le plus évident. Puis divers tracés comme des boxplots, des violin plots, des barplots pour trouver la relation entre deux variables.

>   Enfin, d'après mes conclusions dans l'analyse bivariée, il est déterminé que les caractéristiques les plus fortes qui affectent le pourcentage de taux annuel des emprunteurs sont le LoanOriginalAmount, le prosperScore et le MonthlyLoanPayment.
    Tout cela sera montré dans la présentation."# ismailsg-Nanodegree-data_analyst-ALTX-T-Project-3" 
