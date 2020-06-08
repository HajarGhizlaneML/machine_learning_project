# DL_Chatbot_Project:

  Nous avons essayer de créer un Chatbot en utlisant Sequence to Sequence model et 2 RNNs :
  
  1-Le premier RNN agit comme un codeur, qui code une séquence d'entrée de longueur variable en un vecteur de contexte de longueur fixe. 
    En fait, ce vecteur de contexte (le dernier hidden layer du RNN) contient des informations sémantiques sur la phrase de requête qui 
    représente l'input du bot.
  
  2-Le deuxième RNN est un décodeur, qui prend l'input et le vecteur de contexte, et renvoie un "Guess" pour le mot suivant dans la 
    séquence et un hidden state à utiliser dans la prochaine itération.
	
# Dataset:
 Nous avons combiner deux bases de données:
 
 1-The Cornell Movie-Dialogs Corpus : dataset contient une grande collection de métadonnées de conversations extarites de script 
   des films.
   
   Source:https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html
	
 2-Quelques fichiers contenant des conversations sur d'autres sites comme Kaggle qui semble utile pour ce projet.
 
   Source:https://www.kaggle.com/kausr25/chatterbotenglish
   
   Le fichier DL_Chatbot_Project.pynb: regroupe toutes les parties (Prepare data, Seq2Seq_model, training...) utilsées pour la création du Chatbot.
