
<?php
$array = [1, 1, 2, 3, 4, -51, 12, 12, 12, -51];
$count = 0;

for ($i = 1; $i < count($array); $i++) {
    if ($array[$i] == $array[$i - 1]) {
        $count++;
    }
}

echo $count;
?>
