# Binary-Search-Tree

### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

**Örneğimizi [2] araması icin yapalım.**

 *Öncelikle rootu seçiyoruz.* 
* [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]
* root = 5

*Yapıyı kokler haline getiriyoruz*

                      [5]
            [1,3,0,4,2]  [7,8,6,9]

*Aradığımız degere gore dallanmış köklerden birisini seçiyoruz.*
           
                  [1,3,0,4,2]

*Yeni bir root seciyoruz.*
* root = 3

*Dallarına ayırıyoruz.*

                      [3]
                 [0,1,2]   [4]

*Boylece arama yapacagımız listeyi kucultmus olduk ve aramamızı daha verimli bir hala getirdik.*



