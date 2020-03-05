argentdispo =  lire decimal

prixunitaire =  lire decimal

nombrebonbon = 0

while argentdispo > 0 and prixunitaire > 0 :
    
       
    argentdispo = argentdispo - prixunitaire
        
    if argentdispo > 0 :
    
        nombrebonbon = nombrebonbon + 1
    
print(nombrebonbon)
