[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[22,27,16,2,18,6]
------------------   *16, 27'den ve 22'den küçük. sola en başa kaydırırız.
[16,22,27,2,18,6]
------------------   *2,sol tarafındaki tüm sayılardan küçük. en başa alınır.
[2,16,22,27,18,6]
------------------   *18, 22'den ve 27'den küçük. bu iki sayının önüne alınır.
[2,16,18,22,27,6]   
------------------   *6, 2 haricinde solundaki sayılardan küçük
[2,6,16,18,22,27]


Big-O gösterimini yazınız.

Big-O Gösterimi

Bu dizi average case örneğidir.Toplam n(n-1)/2 karşılaştırma olur. Bu da O(n^2) olarak gösterilir. 


Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

18 sayısını bulmak average case'dir çünkü dizinin başında olmadığı gibi sonunda da değildir. Dolayısıyla time complexity için O(n^2) diyebiliriz.


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6]
-----------------------   *Bu 9 sayılı dizide tüm değerlere baktığımızda en küçük sayı değeri 2'dir. 2 en başa gelir ve 7 ile yer değiştirir.
[2,3,5,8,7,9,4,15,6]
-----------------------   *Geri kalan 8 sayı arasından en küçüğü 3'tür ve doğru yerdedir. Diğer 7 sayı arasından en küçüğü 4'tür ve 5 ile yer değiştirir.
[2,3,4,8,7,9,5,15,6]
-----------------------   *6 sayı arasından en küçüğü 5'tir ve 8 ile yer değiştirir. 
[2,3,4,5,7,9,8,15,6]
-----------------------   *5 sayı arasından en küçüğü 6'dır ve 7 ile yer değiştirir. 
[2,3,4,5,6,9,8,15,7]