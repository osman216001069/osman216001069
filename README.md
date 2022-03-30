- 👋 Hi, I’m @osman216001069
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
osman216001069/osman216001069 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ders-4</title>
</head>
<body>
    <?php

        /* UYGULAMA ODEVI
          kuyruk ve yiGin veri yapilarininin php uzerinde dzileri kullanarak 
        orneklendirimesini gerceklestiriniz */
        /* uygulama : rasgele uretilen sayi 50 'den buyuk ise 
        gectiniz : notunuz : xx
        50'den kucuk ise 
        kaldiniz : notunuz : xx */


    $rasgele_sayi= rand (10,100);
    if ($rasgele_sayi >= 50)
    {
        echo "gectiniz - notunuz : $rasgele_sayi";
    
    
    }
    
        else 
        {
            echo "kaldiniz - notunuz : $rasgele_sayi";
        }
    
    echo "<h3> sik kullanilan string fonksiyonlari </h3>";
        
    $yazi = "aydin meslek yuksek okulu";
    echo $yazi."<br>"."okulunuz...";
    /* icerigin buyuk harfe cevirilmesi */
    echo" <br> \$yazi degiskeninin buyuk harfle yazilmasi:".$buyukyazi=strtoupper($yazi);
    echo "  <br> buyuk yazi = $yazi";
  
    echo "  <br> buyuk yazi = $buyukyazi";
    echo" <br> \$yazi degiskeninin kucuk harfle yazilmasi:  ".$kucukyazi=strtolower($buyukyazi);
    echo "<br> $buyukyazi";
    echo "<br> $yazi";
    /* icerigin harf sayisi :  */
    echo "<br> \$yazi'nin harf sayisi :  ". strlen($yazi);
    echo "<br>";
/* ascii char donusumu */
    echo "karekter karsiligi : 65  " . chr (65);
    echo "<br>";
    echo "karekter karsiligi : 100  " . chr (100);
    echo "<br>";
     /* 0-255 arasindeki degerleri chr fonsiyonuna sokarak satir satir yazdiriniz . */
     
     for ($i= 33 ; $i <=126 ; $i++)
     {
         echo "  :  "." <br> $i " .chr ($i) . "_";
     }

     
  
   
    ?>
</body>
</html>
