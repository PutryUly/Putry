<?php
$biodata = [
    "nama" => "rudi",
    "pekerjaan" => "progamer",
    "pendidikan" => "S1",
    "umur"  => "18",
    "nilai" => "a",
    "hobi" => [
        "tidur", "rebahan", "duduk"
    ]
];

foreach ($biodata as $key => $value) {
    if ($key == "hobi") {
        echo "hobi:" . PHP_EOL;
        $a = 1;
        foreach ($value as $hobi) {
            echo $a . ". " . $hobi . PHP_EOL;
            $a++;
        }
    } else {
        echo $key . ':' . $value . PHP_EOL;
    }
}

hasil
on line 3
PS C:\Users\adeli\OneDrive\Documents\tugas mira> php index.php
nama:rudi
pekerjaan:progamer
pendidikan:S1
umur:18
nilai:a
hobi:
1. tidur
2. rebahan
3. duduk
PS C:\Users\adeli\OneDrive\Documents\tugas mira>
