Informacion de la maquina: 
    Meow - Linux - Easy - 10.120.40.111

Puertos abiertos encontrados: 
    23 corriendo un servicio telnet 

Explotacion mediante enumaracion basica de usuarios probando credenciales comunes:
    (admin, admin), (root,root), (admin,password)
    con (root,root) obtuve una shell con privilegios de root.

Conclusion: 
    Para prevenir este tipo de ataques se debe usar crendenciales mas robustas o cifradas. O añadir una regla de firewall al puerto en cuestion.