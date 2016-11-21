<?php
$fantasy = array ('Автор: Почепцов' => 'Золотой шар 125грн');
$detektiv = array('Автор: Артур' => 'Шерлок Холмс 20грн');
$skazka = array('Автор: Носов' => 'Незнайка 15грн');
$books = array($fantasy, $detektiv, $skazka);

// output
echo '<pre>';
print_r($books);
echo '</pre>';
