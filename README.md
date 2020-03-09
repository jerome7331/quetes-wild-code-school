DEBUT ALGORYTHME

argentdispo =  lire decimal

prixunitaire =  lire decimal

nombrebonbon = 0

while argentdispo > 0 and prixunitaire > 0 :
    
    
    argentdispo = argentdispo - prixunitaire
        
    si argentdispo > 0 :
    
        nombrebonbon = nombrebonbon + 1
        
    sinon :
        
        nombrebonbon = nombrebonbon + 0
        
        
    
afficher(nombrebonbon)

FIN ALGORYTHME
