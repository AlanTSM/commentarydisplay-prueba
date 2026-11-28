# Prueba de la vista de campo (Narrador dinámico de TSM)

Página de prueba de la rama `vista-campo` de [commentarydisplay](https://github.com/AlanTSM/commentarydisplay) (sesiones 21-23: pestañas «Eventos», «Pts. Exp.» y «Vista 2D» con etiqueta «Fase Beta», narración sincronizada con el campo, pausas entre partes, balón parado y relleno narrado).
No es la versión oficial, que sigue en https://alantsm.github.io/commentarydisplay/.

Para probar un partido, pega su informe en el cuadro de texto y abre la pestaña «Vista 2D».

### S24–S25
- Minuto bajo el marcador, «Ampliar» antes de «Reanudar», repetición solo de la jugada del gol, banner de tarjetas.
- Mayor fidelidad narración–coreografía: palo/larguero, paradas, cabezazos, tiros lejanos, penaltis y tandas con desenlace visible.

### S26
- Descansos: retirada al túnel (descanso y final de los 90' con prórroga) o hacia el entrenador (descanso de la prórroga).
- Minutos sin ocasiones con dominio del centro del campo y robos creíbles.
- Paradas sobre la línea, remates al palo en jugadas y contras, penalti al palo con rebote.

### S27
- Cabezazos y desvíos representados en su jugada, córners con remate, barrera sin jugadores pegados, saque de puerta con el área despejada, balón siempre tocado antes de salir, cambios con el balón parado.

### S28–S29
- Córners con el área llena (solo uno se queda atrás vigilando la contra).
- Informes t514: árbitro «Árbitro: Nombre (país)», «Jugadas de ataque» (antes «Ocasiones de gol»), «Estadio» y pie con «.HB»; siguen valiendo los informes antiguos.
- Hora por defecto 20:30; desde las 20:00 el tiempo «Soleado» se muestra como «🌙 Despejado».
- Minutos sin ocasiones (con «Omitir minutos sin ocasiones» desmarcado): recuadro neutro con «Balón en disputa» / «Sin ocasiones».
- Gol: primero solo «¡¡¡GOOOOOOL!!!» parpadeando (estilo CM 01/02) con el color del equipo que marca (también en propia puerta); el resto de la frase en el siguiente comentario.
- Color por acción: cada frase lleva el color del equipo del jugador que hace la acción (despejes, cortes, paradas, robos y faltas del rival con su color); «La defensa despeja», «el portero corta de puños»… también con el color del rival.

### S30
- Sesión de ajustes internos (saques de banda y barrera) sin cambios publicados: los intentos no mejoraban el auditor y se revirtieron.

### S31
- Partidos sin Home Bonus (pie «timestamp.0»): estadio «TSM Stadium».
- Imagen del estadio bajo el banquillo local e información bajo el visitante; árbitro como «Árbitro: [bandera] Nombre» con el país al pasar el cursor.
- Barra «Dominio en los últimos minutos»: solo durante el partido (aparece y desaparece suave), mínimo 10 % por equipo y sin contar cambios, táctica ni instrucciones del mánager.
- Recuadro de narración: nombres en negrita; marcador, clima, añadido y separadores en color neutro; el gol dura al menos 3 s; la animación y el glow del marcador solo con goles; color por acción también en penaltis y tanda (el portero con su color) y el ganador de la tanda con el suyo.
- Engranaje con tooltip «Configuración»; «Omitir minutos sin ocasiones» desmarcado por defecto.
- Configuración: temas «Copa TSM» (vino) y «Simple» (blanco), botón «Aplicar» fijo abajo y quinta fuente «Roboto» (con alternativas para todos los sistemas).
- Marcador: un icono de tarjeta roja por cada roja, en la esquina superior del equipo, en cuanto la narración la muestra.
- Con el partido empezado, «Colores suplentes» se oculta y en su hueco aparecen los goleadores con el minuto, en letra pequeña, en cuanto se enciende el glow del gol (los anulados se quitan; los autogoles van con el equipo beneficiado).

### S32
- Nombres en negrita del recuadro de narración: espacio delante y detrás, sin pegarse al texto ni añadir espacio antes de comas o puntos.
- Escudos y nombres del marcador siempre a la misma altura; la lista de goleadores queda debajo y no los desplaza.
- Entre varias jugadas del mismo minuto el recuadro desaparece 1 segundo (el minuto no avanza; la Vista 2D no se altera).
- En los minutos sin ocasiones el recuadro no aparece (el minuto sí avanza). «Omitir minutos sin ocasiones» sigue saltándolos del todo.
- «MEDIA PARTE», «PRÓRROGA», «FINAL», «TANDA DE PENALTIS» y las líneas de resultado van en color neutro en todos los temas.
- En cada descanso aparece encima del minuto un botón «Iniciar segunda parte», «Iniciar prórroga» o «Iniciar tanda de penaltis», también fuera de la Vista 2D; desaparece al pulsarlo.

### S33
- Botón «Vista 2D BETA» encima de «Comenzar partido»: abre la vista 2D a pantalla completa (como «Ampliar»). La pestaña pasa a llamarse «Momentum» y muestra el ritmo del partido en tiempo real, sin spoilers y sin contar cambios, tácticas ni instrucciones del mánager.
- La tanda de penaltis en la Vista 2D va al ritmo de los comentarios (ya no se adelanta).
- El comentario «X se impone desde los 11 metros» (y «X gana la tanda») va con el color del ganador. En la tanda, las intervenciones del portero llevan su color.

### S34
- «Reiniciar» deja la pantalla como al acabar de pegar el partido (sin goleadores, eventos, momentum ni recuadros).
- El título de la competición conserva «TSM», «UEFA» y el resto de siglas («Copa TSM T38 (Jue 26 nov)»).
- El botón «Vista 2D BETA» es más pequeño y está más cerca del marcador.
- En la Vista 2D, un desplegable entre «Cerrar» y «Pausar» permite elegir «Vista clásica 2D» o «Vista 3D (Estadio)» (perspectiva, jugadores con cuerpo al estilo Championship Manager 2007).
