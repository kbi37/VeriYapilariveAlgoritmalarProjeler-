[16,21,11,8,12,22] -> Merge Sort

1)Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

[16,21,11,8,12,22]  

[16,21,11]          [8,12,22]    --Tabloyu ikiye bölünür

[16]  [21,11]  [8] [12,22]  --Her bir grupta 1 veya 2 eleman kalıncaya kadar bu işlem uygulanır.

[16] [11,21]   [8] [12,22]  --Gruplara ayrılan diziler kendi içinde sıralanır

[11,16,21]     [8,12,22]  --Diziler sıralamayı uygun şekilde birleştirilir.

[8,11,12,16,21,22] --Diziler sıraya uygun olacak şekilde bir kez daha birleştirilir.
 

2)Big-O gösterimini yazınız.

Best Case : O(n*logn)

Average Case : O(n*logn)

Worst Case : O(n*logn)
