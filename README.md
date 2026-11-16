# ❌⭕ 3 en raya

Juego de **3 en raya** para el navegador, pensado para que los peques entrenen antes de un torneo del cole.
Tiene un **modo entrenador** que da consejos antes de cada jugada y explica qué ha estado bien o mal después.

👉 **Jugar ahora:** https://maroke.github.io/3-en-raya/

![Modo entrenador contra la máquina](capturas/entrenador.png)

## Características

- 🤖 **Contra la máquina**, con 4 niveles:
  - 😊 **Fácil**: juega casi al azar.
  - 🙂 **Medio**: gana si puede y tapa tus dos en raya, pero cae en las dobles amenazas.
  - 😎 **Difícil**: juega muy bien, aunque a veces se despista.
  - 🧠 **Imposible**: juega perfecto. Como mucho, ¡se le puede empatar!
- 👫 **2 jugadores** en el mismo ordenador, con nombres. El que empieza se va turnando.
- 🎯 **¿Quién empieza?**: tú, la máquina o por turnos.
- 🎓 **Modo entrenador**:
  - Consejo **antes** de cada jugada («¡El rival tiene dos en raya, tápale!»).
  - Análisis **después** de cada jugada: buena, mejorable o error, explicando por qué.
  - 💡 **Pista**: marca en verde las mejores casillas.
  - ↩️ **Deshacer**: para repetir una jugada y aprender del error.
  - 📋 **Resumen** al final de cada partida.
- 🏆 **Trucos para ganar el torneo**: las estrategias clave explicadas para niños.
- 📱 Funciona en ordenador (Windows, Mac, Linux), tablet y móvil.

![Partida a 2 jugadores](capturas/dos-jugadores.png)

## Cómo se juega

1. Los jugadores ponen por turnos su ficha (❌ o ⭕) en una casilla vacía.
2. Gana quien consiga **3 fichas en línea**: en horizontal, en vertical o en diagonal.
3. Si se llena el tablero sin que nadie lo consiga, es **empate**.

## 🏆 Trucos de campeón

1. **Primero, ¿puedo ganar?** Si tienes dos en raya y la tercera casilla está libre, ¡pon ahí!
2. **Segundo, ¿va a ganar el rival?** Si tiene dos en raya, tápale.
3. **Empieza en el centro o en una esquina.** El centro está en 4 líneas, las esquinas en 3 y los lados solo en 2.
4. **Si el rival empieza en el centro**, responde en una esquina (¡nunca en un lado!).
5. **Si el rival empieza en una esquina**, responde en el centro.
6. **Doble amenaza:** busca una casilla que te dé dos formas de ganar a la vez.
7. **Si tienes el centro y el rival tiene dos esquinas opuestas**, juega en un lado.
8. Si los dos juegan perfecto, la partida termina en **empate**.

## Jugar sin internet

Descarga el repositorio (botón verde **Code → Download ZIP**), descomprímelo y abre `index.html` con doble clic.

## Tecnología

Un único archivo `index.html` con HTML, CSS y JavaScript, sin dependencias ni instalación.
La máquina de los niveles altos usa el algoritmo **minimax**, que revisa todas las partidas posibles.

## Licencia

Código bajo licencia [MIT](LICENSE).
"3 en raya" es el nombre tradicional y genérico de este juego en español. Este proyecto no está relacionado con ninguna marca comercial.
