Topic  Modelling  is a very  important  part  of  understanding   important  features  present  in  your  document. 

It  will  group  or  cluster   important  words   into  various  topics  .

In this  code   i  used  LDA   to  find  topics  which  are similar  in nature  .  


This  code will  take  any  document (docx file)  ,   parse it   remove  stopwords  ,   remove punctuations  etc  and  create  10  most important topics .

I  used   LDA  from  gensim  library  .

You  can pull  this  repo  and do  modifications  as  per your  requirements  .  

I  hope  it will  be useful  for someone  who need  help to  find  topics .  


I  took  help  from  "Susan Li " articles  in   medium.  

The  most important  topics  from the   docx i used are   :  


    (0, '0.033*"University" + 0.029*"Press" + 0.021*"Cambridge" + 0.017*"Oxford"')
    (1, '0.025*"scramble" + 0.020*"binding" + 0.015*"A-movement" + 0.012*"structure"')
    (2, '0.021*"marker" + 0.017*"argument" + 0.016*"clause" + 0.016*"subject"')
    (3, '0.035*"pronoun" + 0.021*"Korean" + 0.019*"discourse" + 0.015*"antecedent"')
    (4, '0.010*"function" + 0.007*"argument" + 0.007*"sentence" + 0.007*"Korean"')
    (5, '0.053*"Linguistics" + 0.043*"Korean" + 0.030*"Journal" + 0.018*"Asian"')
    (6, '0.035*"Korean" + 0.023*"language" + 0.015*"order" + 0.012*"subject"')
    (7, '0.030*"feature" + 0.018*"position" + 0.017*"movement" + 0.016*"sentence"')
    (8, '0.042*"Korean" + 0.025*"Linguistic" + 0.017*"Language" + 0.015*"Natural"')
    (9, '0.026*"clause" + 0.016*"Korean" + 0.015*"quantifier" + 0.011*"embed"')
    
    From the above topics   we can  know  this   docx  file is  related  to  some university  , and korean  related , more precisly  it  is telling 
    
    about korean  linguistics . 
    
    
    
