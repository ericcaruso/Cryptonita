#################################################################

Cryptonita é uma hash alternativa em php, utilizando
a substituição de string caractere à caractere, juntamente
com uma hash md5 e um reverse, dificultando assim asimetricamente
sua descriptografia e resumindo a possibilidade de colisão de hash.

####################################################################


exemplo de utilização:

<?php

// Incluindo arquivo 
include("cryptonita");

$senha = "123";

// Chamando através da função php
$senha_cryptonita = Cryptonita($senha);

// Imprimindo a hash
echo $senha_cryptonita;

?>


