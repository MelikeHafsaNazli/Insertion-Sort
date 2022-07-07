# Insertion Sort

## Proje 1 - Indertion Sort
[22,27,16,2,18,6] dizininin Insertion Sort'a göre aşamaları aşağıda belirtildiği gibidir.

İlk aşamada dizindeki en küçük elemanı bulur ve ilk elemanla yer değiştirir -> [2,27,16,22,18,6]. Sonrasında bu işleme diğer elemanla devam eder -> [2,6,16,22,18,27].
Üçüncü eleman, sıradaki en küçük eleman olduğu için onu atlar ve diğer elemana geçer -> [2,6,16,18,22,27]. Kalan elemanların kontrolünü yapar ve olması gereken yerlerinde olduğuna karar verdiği için değiştirme işlemi yapmaz. Dizin tamamen sıralandığında algoritma sona erer.

## Big-O Notation
    Time Complexity; Worst case, aradığımız sayının sonda olması; average case, aradığımız sayının ortada olması; 
    best case, aradığımız sayının dizinin en başında olmasıdır.

Buna göre;

    Worst Case: O(n)
    Average Case: O(n^2)
    Best Case: O(n^2) 

## Case Determination

[22,27,16,2,18,6] dizininin sıralanmış hali [2,6,16,18,22,27]'dir. Bu dizine göre 18 sayısının time complexity'si average case ile uyumludur.

## Example

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı aşağıda verilmiştir.

1. [2,3,5,8,7,9,4,15,6]
2. [2,3,5,8,7,9,4,15,6]
3. [2,3,4,8,7,9,5,15,6]
4. [2,3,4,5,7,9,8,15,6]

Patika.dev profile: https://app.patika.dev/melikehafsa
