JĘZYK C (PRINTF ORAZ SCANF) 

1. <b>printf</b>
-printf("Twój ciąg znaków"); 

Następuje wywołanie funkcji printf() z argumentem zawartym w nawiasach
(ciag znaków musi znajdować się w cudzysłowiu).

 
Wypisanie ciągu znaków jest tylko jedną z możliwości – możemy również wypisać wartość zmiennej. 

Jednak w tym przypadku, programista musi znać typ zmiennej, wówczas dla zmiennej o nazwie MojaZmienna typu integer
 możesz zrobić to nastepująco:


-printf("%d", MojaZmienna); 
W takim wypadku, wywołana zostanie funkcja printf() a argumentem będzie ciąg znaków „%d” 
(znak % informuje program, że w tym miejscu zostanie użyta zmienna, natomiast literka po % - w naszym wypadku d – informuje program o typie tej zmiennej, tutaj jest to int)
nastepnie po przecinku, wypisujemy nazwe zmiennej. 

2. <b>scanf</b>
-scanf("%d", &zmienna);
Na początku używamy słowa kluczowego scanf,  a następnie otwieramy nawias.
 
W cudzysłowiu ustalamy typ zmiennej (w naszym przypadku będzie to %d, czyli integer), a następnie po przecinku wprowadzamy nazwę zmiennej, do której chcemy przypisać wartość, poprzedzoną znakiem "&".

3. <b>WAŻNE INFORMACJE</b>:

• Instrukcja printf sluzy do wypisywania tekstu na ekran.

• Za pomocą instrukcji printf możemy wypisywać także wartości zmiennych.

• Instrukcja scanf sluzy z czytania tekstu wpisanego przez uzytkownika i wykonywania na nim konkretnych operacji jak np. przypisanie do zmiennej.

• Chcąc wypisać kilka zmiennych w funkcji printf pamiętaj aby wypisywać je w odpowiedniej kolejności! 
