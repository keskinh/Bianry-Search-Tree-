# Bianry-Search-Tree-
[Patika.dev](https://www.patika.dev/tr)

Bianry Search Tree 

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

Burada Binary Search Tree ile aradığımız eleman 7 olsun ve 6yı referans alarak ağacımızı oluşturup 9u arayalım. Bu ağacı oluşturuken her rakamının sol arafında kendinden küçükler sağ tarafında kendinden  büyükler yer alacak şekilde sıralayacağız.

6 ile başlıyoruz 4< 6 bu sebeple 4 6'nın soluna 
5>4 o zaman 5 4'ün sağına 
3, 2, 1 < 42ten olduğu için hepsi 4'ün soluna dizilir.
8>6 dan olduğu için ağacın sağ tarafına 
7< 8 olduğu için 8'in solunda yer alır  
9> 8 olduğundan dolayı da 8'in sağında yer alır ve ağaç tamamlanır.
                                6
                            4           8 
                                             9
                        3     5     7
                    2
                1
                                      
