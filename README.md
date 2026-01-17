# Exercici XML 03 - Definició de DTD

Exercici de validació de documents XML mitjançant DTD (Document Type Definition).

## Estructura del repositori

### Primera part - DTD interns
- **`client1.xml`**: Document XML amb DTD intern per esdeveniments musicals (concerts)
  - Conté l'element `<grup>` per identificar els grups musicals
  - Atribut `gratuita` obligatori a l'element `<entrada>`

- **`client2.xml`**: Document XML amb DTD intern per esdeveniments teatrals
  - Conté l'element `<companyia>` per identificar les companyies de teatre
  - Element `<entrada>` sense atributs

### Segona part - DTD extern amb namespaces
- **`esdeveniments.xml`**: Document XML que combina concerts i teatre amb namespaces
  - Namespace `c:` per a concerts
  - Namespace `t:` per a teatre
  
- **`esdeveniments.dtd`**: Fitxer DTD extern que defineix l'estructura amb namespaces

## Validació

Tots els documents han estat validats amb l'extensió **XML Language Support by Red Hat** de Visual Studio Code.
A la carpeta captures es troben les proves fetes amb error i el amb el docuemnt corregit. 
