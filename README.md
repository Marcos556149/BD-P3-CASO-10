# BD-P3-CASO-10
1*) A= π Codt σ prov ='SJ' Teatro
    π DNI, Tel (Persona ⨝ π DNI (Compra ⨝ A))
2*) SJ= π Codt σ prov='SJ' Teatro
    MDZ= π Codt σ prov='MDZ' Teatro
    SL= π Codt σ prov='SL' Teatro
    LR= π Codt σ prov='LR' Teatro
    CON= π Cod σ tipo='concierto' Esp
    AA= Tiene ⨝ CON
    (π Cod (AA ⨝ SJ)) ∩ (π Cod (AA ⨝ MDZ)) ∩ (π Cod (AA ⨝ LR)) ∩ (π Cod (AA ⨝ SL))
3*) A= π Codt σ Nom='Quintinilla' Teatro
    π Cod (Tiene ⨝ A)
4*) NO SE PUEDE HACER PORQUE NO ESTA EL PRECIO
5*) A= π Codt σ Capac ≤ 300 Teatro
    Esp ⨝ (π Cod,Codt Tiene ÷ A)
