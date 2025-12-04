1. Create a new state (folder) to hold parks in Ohio
2. Add 2 new files named Adams-Lake-State-Park.txt and Caesar
   Creek-State-Park.txt to Ohio
3. Add a new state (folder) to hold parks in New York
4. Add three new parks in New York. Remember, they are just files with the
   park name and a .txt file extension
5. Add an Iguana as a new type of pet
6. Add a new Mexican meal with the name Enchilada.txt
7. Add a new state to hold parks in Iowa
8. Add three new parks from Iowa
9. Remove goldfish as a pet
   10.Remove all parks in Ohio
   11.List the parks in Iowa
   12.Remove all parks in Iowa
   Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight
   $ cd command-line

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line
$ ls
Animals/  Foods/  Parks/

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line
$ cd parks

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ cd ohio
bash: cd: ohio: No such file or directory

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ ls
Califiornia/  Florida/  Texas/

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ mkdir Ohio

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ ls
Califiornia/  Florida/  Ohio/  Texas/

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ cd Ohio

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks/Ohio
$ touch Adams-Lake-State-Park.txt

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks/Ohio
$ ls
Adams-Lake-State-Park.txt

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks/Ohio
$ touch Caesar-Creek-State-Park.txt

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks/Ohio
$ ls
Adams-Lake-State-Park.txt  Caesar-Creek-State-Park.txt

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks/Ohio
$ cd ..

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ mkdir New York

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ ls
Califiornia/  Florida/  New/  Ohio/  Texas/  York/

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ rm new
rm: cannot remove 'new': Is a directory

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ rmdir new

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ rmdir york

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ ls
Califiornia/  Florida/  Ohio/  Texas/

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ mkdir "New York"

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ ls
Califiornia/   Florida/  'New York'/   Ohio/   Texas/

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ cd "New York"

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks/New York
$ rmdir "New York"
rmdir: failed to remove 'New York': No such file or directory

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks/New York
$ cd ..

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ rmdir "New York"

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ ls
Califiornia/  Florida/  Ohio/  Texas/

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ mkdir New-York

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ ls
Califiornia/  Florida/  New-York/  Ohio/  Texas/

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ cd New-York

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks/New-York
$ touch Central-Park.txt North-Park.txt South-Park.txt

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks/New-York
$ ls
Central-Park.txt  North-Park.txt  South-Park.txt

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks/New-York
$ cd ../..

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line
$ ls
Animals/  Foods/  Parks/

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line
$ cd animals

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/animals
$ ls
Farm/  Pets/

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/animals
$ cd pets

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/animals/pets
$ ls
Cat.txt  Dog.txt  Goldfish.txt  Parrot.txt

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/animals/pets
$ touch Iguana.txt

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/animals/pets
$ ls
Cat.txt  Dog.txt  Goldfish.txt  Iguana.txt  Parrot.txt

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/animals/pets
$ cd ../..

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line
$ cd foods

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/foods
$ ls
BBQ/  Mexican/

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/foods
$ cd Mexican

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/foods/Mexican
$ touch Enchilada.txt

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/foods/Mexican
$ ls
Burrito.txt          Enchilada.txt              Taco.txt
'Chile Rellano.txt'  'Guacamole and Chips.txt'

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/foods/Mexican
$ cd ../..

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line
$ cd parks

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ ls
Califiornia/  Florida/  New-York/  Ohio/  Texas/

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ mkdir Iowa

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ ls
Califiornia/  Florida/  Iowa/  New-York/  Ohio/  Texas/

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ cd Iowa

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks/Iowa
$ touch East-Park.txt West-Park.txt Iowa-Park.txt

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks/Iowa
$ ls
East-Park.txt  Iowa-Park.txt  West-Park.txt

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks/Iowa
$ cd ../..

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line
$ cd pets
bash: cd: pets: No such file or directory

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line
$ cd animals

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/animals
$ cd pets

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/animals/pets
$ ls
Cat.txt  Dog.txt  Goldfish.txt  Iguana.txt  Parrot.txt

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/animals/pets
$ rm Goldfish.txt

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/animals/pets
$ ls
Cat.txt  Dog.txt  Iguana.txt  Parrot.txt

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/animals/pets
$ cd ../..

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line
$ cd parks

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ ls
Califiornia/  Florida/  Iowa/  New-York/  Ohio/  Texas/

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ cd ohio

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks/ohio
$ ls
Adams-Lake-State-Park.txt  Caesar-Creek-State-Park.txt

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks/ohio
$ rm Adams-Lake-State-Park.txt Caesar-Creek-State-Park.txt

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks/ohio
$ ls

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks/ohio
$ cd ..

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ ls
Califiornia/  Florida/  Iowa/  New-York/  Ohio/  Texas/

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks
$ cd Iowa

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks/Iowa
$ ls
East-Park.txt  Iowa-Park.txt  West-Park.txt

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks/Iowa
$ rm East-Park.txt Iowa-Park.txt West-Park.txt

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks/Iowa
$ ls

Student@YUUSTD15551283 MINGW64 /c/User/Student/pluralsight/command-line/parks/Iowa
$
