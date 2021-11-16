  <!-- #Linea 87 codigo fuente antes del testeo  -->
  guessSubmit.addeventListener('click', checkGuess);
  <!-- #Linea correcta -->
  guessSubmit.addEventListener('click', checkGuess);

  El incoveniente era que la funcion addEventListener tenia un error de sintaxis

  
  <!-- #Linea 95 del codigo fuente antes del testeo  -->
  resetButton.addeventListener('click', resetGame);

  <!-- #Linea correcta  -->
  resetButton.addEventListener('click', resetGame);

  El incoveniente era que la funcion addEventListener tenia un error de sintaxis


En las variables iniciales del script se eliminaron algunas que no tenian funcionalidad
