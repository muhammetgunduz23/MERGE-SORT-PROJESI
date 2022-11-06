# MERGE-SORT-PROJESI
Patika.dev

Patika.dev ve Kodluyoruz marmara üniversitesi yazılıma başlangıç eğitiminin ikinci projesi

[16,21,11,8,12,22] -> Merge Sort

1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
                                              [16,21,11,8,12,22]
                                    
                                 [16,21,11]                       [8,12,22]
                               
                               [16,21]     [11]                 [8,12]    [22]
                               
                            [16]  [21]     [11]              [8]  [12]     [22]
                            
                              [16,21]     [11]                [8,12]      [22]
                               
                                 [11,16,21]                       [8,12,22]
                                 
                                             [8,11,12,16,21,22]
Diziyi her adımda parçalara ayırıp tek eleman kalıncaya kadar bölüyoruz. Tek eleman olana kadar bölmeye devam ediyoruz. Böldükten sonra sıralı şekilde bize sunuyor.

2.Big-O gösterimini yazınız.

Cevap= O(nlogn)
