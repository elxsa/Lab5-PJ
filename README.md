RO: Programare Java - laborator 5, scurtă descriere: 



1. Se consideră fișierul persoane.json cu conținutul aferent. Următorul program va prelua datele din fișier, le va încărca într-o colecție List şi le va afișa. Colecția va fi completată cu încă o persoană şi apoi va fi salvată în fișier. Clasele obiectelor care vor fi salvate în format JSON respectă modelul POJO (Plain Old Java Object). Potrivit modelului POJO, clasele trebuie să aibă variabile membre private, gettere şi settere şi un constructor fără parametri. 

Clasa "ObjectMapper" furnizează prin metodele sale funcționalitatea de bază pentru scrierea şi citirea fișierelor JSON, precum şi suport pentru conversii. Astfel, se utilizează metoda writeValue() pentru a scrie o listă de persoane într-un fişier JSON şi metoda readValue() pentru a citi datele din JSON într-o listă de persoane. 

2. Deasupra metodelor care realizează teste se pune adnotația @Test. Clasa exemplul2.Calculator a fost importată, pentru a putea scrie unități de testare pentru metodele sale.

Metoda assertEquals() are doi parametri, valoarea așteptată şi al doilea valoarea returnată de funcția apelată (în exemplul considerat de funcţia suma()). La utilizarea acestei metode testul trece dacă metoda returnează valoarea așteptată. La utilizarea metodelor assertTrue() testul trece dacă condiția specificată este adevărată, iar la utilizarea metodele assertFalse() testul trece dacă condiția specificată este falsă.

EN: Java Programming - Lab 5, brief description:

1. Consider the file persoane.json with its corresponding content. The following program will retrieve data from the file, load it into a List collection, and display it. The collection will be augmented with one more person and then saved to a file. The classes of objects that will be saved in JSON format adhere to the POJO (Plain Old Java Object) model. According to the POJO model, classes must have private member variables, getters and setters, and a no-argument constructor.
The "ObjectMapper" class provides basic functionality for writing and reading JSON files through its methods, as well as support for conversions. Thus, the writeValue() method is used to write a list of people to a JSON file, and the readValue() method is used to read data from JSON into a list of people.

2. Above the methods that perform tests, the @Test annotation is placed. The class exemplul2.Calculator has been imported, to enable writing test units for its methods.
The assertEquals() method has two parameters, the expected value and the second is the value returned by the function called (in the considered example by the function suma()). When using this method, the test passes if the method returns the expected value. When using the assertTrue() methods, the test passes if the specified condition is true, and when using the assertFalse() methods, the test passes if the specified condition is false.
