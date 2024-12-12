# devoirlibre
pour input j'ai utilisé la structure suivant :
 { "idOrder": 101, "dateOrder": "2024-12-12", "amount": 250.75, "customerId": 1 }
  { "idOrder": 102, "dateOrder": "2024-12-13", "amount": 180.50, "customerId": 2 }
  { "idOrder": 103, "dateOrder": "2024-12-14", "amount": -320.00, "customerId": 3 }
chaque ordre dans un ligne, pas de probleme si il y'a un ligne vide(code pense que ligne vide et un ordre ms le probleme est fixe)
aussi si il y'a deja une ordre dans database il va ingorer l'objet et il ne peut pas etre inserer dans output.txt
database utiliser dans folder thread
si input et vide et l'utilisateur entre nouveau ordre il faut le sauvgarder avec ctrl+s et merci
