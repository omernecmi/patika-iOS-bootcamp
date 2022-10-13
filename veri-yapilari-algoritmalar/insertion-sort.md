# Insertion Sort Projesi
#### Soru A -  [22,27,16,2,18,6] ifadesini aşağıdaki sorulara göre çözümleyiniz. <br /> 
1- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız. <br /> 
[2,27,16,22,18,6] (n-1) <br />
[2,6,16,22,18,27] (n-2) <br />
[2,6,16,18,22,27] (n-3) <br />

2- Big-O gösterimini yazınız. <br />
n+(n-1)+(n-2)+(n-3)+....1 işlem gerçekleşir = (n.(n+1))/2 = (n^2+n)/2 bu fonksiyonun dominant kısmı dikkate alındığında Big-O (n^2) <br />

3- Time Complexity: <br />
Best Case: Aradağımız elemanın ilk sırada bulunması durumunu ifade eder.(22) <br />
Average Case: Aradığımız elemanın ortada bulunması durumunu ifade eder. (16,12) <br />
Worst Case: Aradığımız elemanın sonda bulunması durumunu ifade eder. (6) <br />

4- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız. <br />
[2,6,16,18,22,27] ifadesinde 18 konumu itibariyle "average case" kapsamına girer. <br />

#### Soru B - [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre adımlarını yazınız. 
[2,3,5,8,7,9,4,15,6] <br />
[2,3,4,8,7,9,5,25,6] <br />
[2,3,4,5,7,9,8,15,6] <br />
[2,3,4,5,6,9,8,15,7] <br />
[2,3,4,5,6,7,8,15,9] <br />
[2,3,4,5,6,7,8,9,15] <br />

