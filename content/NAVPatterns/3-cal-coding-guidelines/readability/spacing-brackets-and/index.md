+++
title = "Spacing Brackets and ::"
weight = 1130
+++
There must be no spaces characters before and after \[\] dimension brackets symbols or :: option symbols.
Bad code

    A\[i\] \[j\] := Amt;  
      
    

Good code

    A\[i\]\[j\] := Amt;  
      
    

Bad code

    "Currency Exchange Rate"."Fix Exchange Rate Amount" :: Currency:  
      
    

Good code

    "Currency Exchange Rate"."Fix Exchange Rate Amount"::Currency:  
      
    

Bad code

    IF FIND (Which) THEN  
      
    

Good code

    IF FIND(Which) THEN
