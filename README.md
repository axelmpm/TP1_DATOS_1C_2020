# TPs_DATOS_1C_2020

    TP2 workflow:
        1) se hace el notebook con el algoritmo
        2) se lo prueba para ver como da
        3) se lo submitea
        4) se lo agrega al informe
        5) paso 1) con un nuevo algoritmo

    Informe TP2:
        https://es.overleaf.com/9929313537cstmyvrsmmhd

    DRIVE con ideas TP2: 
        https://docs.google.com/document/d/1BgSbnm7DZa6TtsCEaXxTdbGqxC34fqUtRB6p-PHuQac/edit

    Informe TP1: 
        https://es.overleaf.com/project/5ec4a3bba31c280001e9223b

    DRIVE con ideas TP1: 
        https://docs.google.com/document/d/1B8ROm6J33qeZduitpz7esbcvn0uf4x_pSifhdH9x5JU/edit?usp=sharing

    PARA MERGEAR NOTEBOOKS: pip install nbmerge

        (Si quiero mergear a1.ipynb y a2.ipynb y a3.ipynb y guardarlo en un archivo llamado a4.ipynb, hago:
        nbmerge a1.ipynb a2.ipynb a3.ipynb > a4.ipynb).
        (Al mergear, buscar los import y ponerlos todos en la 1ra celda).

    Nombre de variables: PrimeraLetraDelNombre_NombreVariable. Ej: N_TweetsFalsos, es la variable TweetsFalsos de Nacho.

    PARA HACER "import datuslib" SE HACE EN UNA CELDA: %run datuslib.ipynb

        (datuslib.ipynb es donde guardamos nuestras funciones compartidas).
    
    CADA PLOT DEBE PERTENECER A UN TEMA Y CADA TEMA DEBE CORRESPONDERSE CON UNO Y SOLO UN NOTEBOOK CON NOMBRE (SIGLA)_(TEMA)

        (por ejemplo: si yo (Axel) hago los plots de tema negatividad los meto en A_negatividad.ipynb).
        
    PARA PODER RESOLVER CONFLICTOS ENTRE NOTEBOOKS: 

        pip install nbdime                     (INSTALACION)
        nbdime config-git --enable --global    (INSTALACION)
        nbdime mergetool                       (USAR CUANDO APAREZCA UN CONFLICTO)

    Convencion de nombres: 

        - Funciones en ingles.
        - Variables y plots en español.
