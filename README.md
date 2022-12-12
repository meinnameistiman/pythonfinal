# 1- Bir listeyi düzleştiren (flatten) fonksiyon yazın. 

liste = [[1,'a',['cat'],2],[[[3]],'dog'],4,5]
yeni_liste = []

def flatten(n):
    for i in n :
        if isinstance(i, list):
            flatten(i)
        else:
            yeni_liste.append(i)

flatten(liste)
print(yeni_liste)


# 2- Verilen listenin içindeki elemanları tersine döndüren bir fonksiyon yazın. Eğer listenin 
# içindeki elemanlar da liste içeriyorsa onların elemanlarını da tersine döndürün. 

input = [[1, 2], [3, 4], [5, 6, 7]]

input.reverse()

for i in range(len(input)):
    (input[i]) = (input[i])[::-1]

print(input)
