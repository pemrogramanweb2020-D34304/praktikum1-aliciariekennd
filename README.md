<?php 
$star=5;
	for($a=1; $a<=$star; $a++){
	for($b=1; $b<=$a; $b++){
		echo "&nbsp";
	}
	for($c=$star; $c>=$a; $c-=1){
		echo "*";
	}
	echo "<br>";
	}

	$star=5;
	for($a=1; $a<=$star; $a++){
	for($i=1; $i<=$a; $i++){
		echo " &nbsp";
	}
	for($c=$star; $c>=$a; $c-=1){
		echo "*";
	}
	echo "<br>";
	}

	$i = 10;
for ($i = 5; $i >= 1; $i--) {
  for ($j = 1; $j <= 1 - $i; $j++) {
    echo " ";
  }
  for ($k = 1; $k < $i; $k++) {
    echo "$k";
  }
  for ($l = $i; $l >= 1; $l--) {
    echo "$l";
  }
  echo "<br>";
}
 ?>
       
       
