<?php

print " Quantos dias você permaneceu com o carro?";
$perma = (int) fgets (STDIN);

print "Quantos Km você percorreu?";
$perco = (int) fgets (STDIN);

$permaneceu = $perma*60;
$percorrido = $perco*0,15;

$total = $permaneceu+$percorrido;

print " O valor total do aluguel a pagar será de R$ $total ,00";
