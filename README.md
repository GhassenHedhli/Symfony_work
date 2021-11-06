# Symfony_work
#Les actions faites: 
#manipuler security.yaml 
#créer un entity = User 
#créer un controller = SecurityController 
#créer un Form = RegistrationType Sur templates = login.html.twig / registration.html.twig

#Les conditions du Sign Up: Email doit etre unique c-à-d non exite dans la base de données 
#le Password doit contenir au minimum 8 caractères et le meme que ConfirmPassword le ConfirmPassword doit etre le meme que Password

#Sur la base de données: security.yaml=Le Password est crypté par l'algorithme 'bcrypt'

#Sur l'interface: bouton de la déconnexion ne s'affiche pas si la connexion ne sera pas affecté

#Sur SecurityController: 
#J'ai des functions: 
#function registration = pour Ajouter les utilisateurs 
#function login = pour faire la connexion à login.html.twig après la validation de la connexion et vers le product avec le route  
#function logout = (Voir security.yaml 'target:ListProd') pour faire la deconnexion 
#Read: security.yaml Form =RegistrationType Controller =SecurityController Entity =User templates = templates = login.html.twig / registration.html.twig
