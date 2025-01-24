<h1 align="left">Détection et classification automatisées des tumeurs cérébrales à l’aide de techniques d’apprentissage profond</h1>

###

<br clear="both">

<h3 align="left">🎯 Contexte du Projet</h3>

###

<p align="left">La détection et la classification des tumeurs cérébrales à partir d'images IRM sont des étapes cruciales dans le diagnostic et le traitement des patients atteints de maladies neurologiques. Ces tâches, souvent complexes et chronophages, nécessitent une expertise spécialisée et une attention méticuleuse.<br><br>Avec l'émergence des techniques d'apprentissage profond, il est désormais possible d'automatiser ces processus, offrant ainsi une analyse rapide, précise et reproductible. Cela permet de réduire le fardeau des radiologues et d'améliorer les prises de décision cliniques.<br><br>Ce projet vise à développer un système robuste capable :<br><br>-1- De détecter et classifier automatiquement les tumeurs cérébrales à partir d'images IRM.<br>-2- D'intégrer la segmentation des tumeurs, permettant une localisation et une délimitation précises des zones tumorales.<br><br>Ces fonctionnalités sont essentielles pour assister les professionnels de santé dans la prise de décisions éclairées et la planification des traitements.</p>

###

<br clear="both">

<h3 align="left">📝 Objectifs du Projet</h3>

###

<br clear="both">

<p align="left">✅  Classification : Utiliser des réseaux de neurones convolutifs (CNN) et des modèles de transfert d’apprentissage pré-entraînés (ResNet50, ResNet101, Xception, EfficientNet, DenseNet, MobileNet, Inception, InceptionResNet) pour classifier les images IRM en fonction de la présence ou non d'une tumeur cérébrale.<br><br>✅  Segmentation : Développer un modèle basé sur UNet pour segmenter et localiser précisément les tumeurs sur les images IRM.<br><br>✅  Comparaison des modèles : Identifier le modèle le plus performant en termes de précision, fiabilité et efficacité dans un contexte clinique.</p>

###

<br clear="both">

<h3 align="left">⚙️ Fonctionnalités</h3>

###

<h4 align="left">👉 Notebooks :</h4>

###

<p align="center">Les notebooks pour la classification des images IRM à l’aide de CNN et de modèles de transfert d’apprentissage :<br><a href="https://www.kaggle.com/code/dhaouadiibtihel98/brain-tumor-classification-cnn-model"> Notebook CNN </a><br><a href="https://www.kaggle.com/code/dhaouadiibtihel98/brain-tumor-classification-resnet50-model"> Notebook ResNet50 </a><br><a href="https://www.kaggle.com/code/dhaouadiibtihel98/brain-tumor-classification-resnet101-m"> Notebook ResNet101 </a><br><a href="https://www.kaggle.com/code/dhaouadiibtihel98/brain-tumor-classification-xception"> Notebook Xception </a> <br><a href="https://www.kaggle.com/code/dhaouadiibtihel98/brain-tumor-classification-efficientnet"> Notebook EfficientNet </a><br><a href="https://www.kaggle.com/code/dhaouadiibtihel98/brain-tumor-classification-densenet"> Notebook DenseNet </a><br><a href="https://www.kaggle.com/code/dhaouadiibtihel98/brain-tumor-classification-mobilenetv1"> Notebook MobileNet </a><br><a href="https://www.kaggle.com/code/dhaouadiibtihel98/brain-tumor-classification-using-inceptionv3"> Notebook Inception </a><br><a href="https://www.kaggle.com/code/dhaouadiibtihel98/brain-tumor-classification-inceptionresnetv2"> Notebook InceptionResNetV2 </a><br><br>Après une comparaison approfondie des performances des modèles, le modèle InceptionResNetV2 a été retenu pour sa précision exceptionnelle, essentielle dans un contexte clinique.</p>

###

<div align="center">
  <img height="300" src="https://github.com/ibtihel-dhaouadi/D-tection-et-classification-des-tumeurs-c-r-brales-l-aide-de-techniques-d-apprentissage-profond/blob/main/InceptionResnet_accurancy_loss_curve.png"  />
</div>

###

<p align="left">Et un notebook pour la segmentation des tumeurs à l’aide du modèle UNet :  <a href="https://www.kaggle.com/code/dhaouadiibtihel98/brain-tumor-segmentation-u-net"> Notebook Segmentation UNet </a></p>

###

<h4 align="left">👉 Application Tkinter :</h4>

###

<p align="left">Un fichier system.py dans "systeme de detection de tumeurs cerebrales.rar" contenant une interface utilisateur interactive développée avec Tkinter. Cette application permet de :<br><br>- Charger une image IRM.<br>- Classifier automatiquement si une tumeur est présente ou non.<br>- Visualiser les résultats de la segmentation.<br><br>⬇️ Un aperçu de l’interface :</p>

###

<div align="center">
  <img height="350" src="https://github.com/ibtihel-dhaouadi/D-tection-et-classification-des-tumeurs-c-r-brales-l-aide-de-techniques-d-apprentissage-profond/blob/main/result3.png"  />
</div>

###

<br clear="both">

<h3 align="left">👨🏻‍💻 Technologies utilisées :</h3>

###

<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" height="40" alt="vscode logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kaggle/kaggle-original.svg" height="40" alt="kaggle logo"  />
</div>

###

<p align="left">✔️  Langage principal: Langage principal pour la manipulation et l'analyse des données.<br><br>✔️ Bibliothèques principales :<br>- TensorFlow/Keras : Développement des modèles CNN et transfert d'apprentissage.<br>- OpenCV :  Prétraitement des images et visualisation des résultats.<br>- Tkinter : Création d'une interface utilisateur pour tester le modèle.<br>- Matplotlib et Seaborn : Visualisation des résultats et des performances des modèles.<br><br>✔️ Outils et environnements :<br>➜ kaggle Notebook : Utilisé pour l’entraînement des modèles sur GPU, accélérant considérablement les calculs.<br>➜ Visual Studio Code : Environnement de développement intégré (IDE) pour le développement et les tests.</p>

###

<br clear="both">

<h3 align="left">📌 Résultats:</h3>

###

<p align="left">Après avoir testé plusieurs modèles de transfert d’apprentissage, le modèle InceptionResNetV2 a été sélectionné pour sa précision remarquable et sa fiabilité. Il est particulièrement adapté à une utilisation clinique où des résultats précis sont essentiels. De plus, l’intégration de la segmentation avec UNet permet d’améliorer la compréhension des zones tumorales, aidant les professionnels à mieux planifier les traitements.</p>

###

<br clear="both">

<h3 align="left">🔚 Conclusion :</h3>

###

<p align="left">Ce projet montre comment l'apprentissage profond peut être utilisé pour résoudre des problèmes complexes dans le domaine médical. Grâce à une méthodologie rigoureuse, le modèle InceptionResNetV2 a été identifié comme le meilleur pour la classification, tandis que le modèle U-Net a permis une segmentation précise des tumeurs.<br><br>Ce système est conçu pour fournir un soutien précieux aux professionnels de la santé, contribuant à un diagnostic et à une planification des traitements plus rapides et plus précis.</p>

###

<h5 align="center">N’oubliez pas de télécharger les fichiers des meilleurs modèles (best_InceptionResNetV2Model.keras et best_unetmodel.keras) depuis les résultats des notebooks, puis de les placer dans le dossier assets du fichier compressé "système de détection de tumeurs cérébrales.rar" si vous souhaitez tester le système.</h5>

###

<h6 align="center">🔗 N’hésitez pas à consulter les fichiers attaché à ce dépôt pour plus de détails. Vos commentaires et suggestions sont les bienvenus !</h6>

###
