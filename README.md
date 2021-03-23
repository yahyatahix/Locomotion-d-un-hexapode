# Locomotion d'un-hexapode
Conception d'un réseau de neurones à décharges nonautonome  permettant  de  générer  les  commandes  dedéplacement pour un hexapode. Puis, généraliser pourun nombre supérieur de pattes (100 pattes dans notreétude).  Enfin,  mettre  en  place  un  système  semi-autonome. 

# CONTEXTE DE TRAVAIL
L'étude  de  la  locomotion  des  insectes  démontre  laprésence  d'un  système  centralisé  et  d'un  systèmedécentralisé.  Le  système  centralisé  permettantd'imprimer  un  mouvement  général  tandis  que  lesystème décentralisé permet à chaque patte de réagirindépendamment. Ces deux approches ont fait l'objetd'étude  dans  la  littérature  [1]  [2]  et  permettentd'obtenir  des  résultats  différents.  Dans  le  cadre  denotre  étude  nous  avons  opté  pour  un  systèmecentralisé  qui  permet  d'avoir  un  réseau  plus  simplemême  si  la  l'adaptabilité  est  plus  faible  [2].  De  plus,cette architecture offre de meilleures performances caron utilise un seul générateur central contrairement ausystème décentralisé qui en nécessite un pour chaquepatte.  Pour la réalisation de ce projet, nous avons utiliséla  bibliothèque  brian2  de  python  ainsi  quel'environnement Jupyter notebook.

# RÉFÉRENCES

[1]: R. D. Beer, H. J. Chiel, R. D. Quinn, K. S. Espenschied,andP.  Larsson,  “A  distributed  neural  networkarchitecture  for  hexapod  robotlocomotion,”NeuralComputation,   vol.   4,   pp.   356–365,   1992.[Online].Available :https://doi.org/10.1162/neco.1992.4.3.356 

[2]:  M.  OTIS,  “Développement  d’un  s  système  depropulsion pour un biomi-crorobot hexapode avec unionomère erfluorosulfonique,” Master’sthesis,Université de Sherbrooke, 2004 

[3]:https://brian2.readthedocs.io/en/stable/examples/CUBA.html

[4]:  N.  Porcino,  “Hexapod  gait  control  by  a  neuralnetwork,” in1990 IJCNNInternational Joint Conferenceon Neural Networks, June 1990, pp. 189–194 vol.1.
