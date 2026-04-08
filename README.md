<div align="center">
  <img src="https://ddragon.leagueoflegends.com/cdn/img/champion/splash/Kalista_0.jpg" alt="Kalista Splash" width="900" style="border-radius: 10px;">
  <br><br>
  <h1>🗡️ KALISTA MASTER WIKI & SYSTEM OS 🗡️</h1>
  <p><b>The Ultimate Data-Driven Execution Engine for High Elo [Parche 26.7]</b></p>
  <i>"El fin de tu trayecto... comienza ahora."</i>
</div>

---

## 📖 Índice del Sistema (Wiki)
1. **[Arquitectura de Habilidades & Matemáticas del Frame-Data](#1-arquitectura-de-habilidades--matemáticas-del-frame-data)**
   - 1.1 Pasiva: Martial Poise (Salto) y Curva de Attack Speed
   - 1.2 Q (Pierce): Transferencia de Rend
   - 1.3 W (Sentinel): Control de Visión y Daño de Pacto
   - 1.4 E (Rend): Thresholds de Ejecución y Matemáticas
   - 1.5 R (Fate's Call): Geometría de Engage
2. **[Itemización y Matemáticas (El "Por Qué")](#2-itemización-y-matemáticas-el-por-qué)**
3. **[Runas Optimizadas (Parche 26.7)](#3-runas-optimizadas-parche-267)**
4. **[Matriz de Oathsworn (Supports) Expandida](#4-matriz-de-oathsworn-supports-expandida)**
5. **[Matriz de Matchups & Fase de Líneas](#5-matriz-de-matchups--fase-de-líneas)**

---

## ⚙️ 1. Arquitectura de Habilidades & Matemáticas del Frame-Data

### 1.1 Pasiva: Martial Poise (Elegancia Marcial)
*La habilidad que define a Kalista. Si no entiendes el Frame-Data de la pasiva, no puedes jugarla.*

*   **Mecánica Base:** Tras emitir una orden de ataque básico, Kalista saltará hacia la dirección indicada en lugar de cancelar la animación. 
*   **Parche 26.7 Importante:** Históricamente sus auto-ataques infligían un 90% de su AD. En parches modernos, **inflige 100% de su Daño de Ataque Total**, permitiéndole construir AD puro sin penalización y maximizar *Lifesteal*.
*   **Por qué el "Attack Speed" es una trampa mortal a Late Game:**
    La distancia de salto de Kalista **NO** escala con velocidad de movimiento regular fuera de las botas.
    *   <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/item/1001.png" width="20"> Botas Tier 1 (25% extra distance)
    *   <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/item/3006.png" width="20"> Botas Tier 2 (Berserker / Steelcaps) = Máximo Salto Posible.
    *   **"El Cap de AS" (Attack Speed):** Al sobrepasar **1.80 a 2.0 de AS**, la animación de su salto *empieza a ser más lenta que su capacidad de atacar parada*. **Regla de Master+**: Si tienes mucho AS (por ejemplo con Lethal Tempo activo o Guinsoo cargado) y necesitas maximizar DPS puro al Barón o Tumbando Torre, **DEJA DE SALTAR** (A-Click estático en el sitio sin moverse). Saltar literalmente reducirá tu DPS un 20%.

### 1.2 Q (Pierce / Atravesar)
*   **El "Por Qué":** Escala con un absurdo **105% de tu AD Total**. 
*   **Táctica Oculta (Transferencia de Lanzas):** Si matas un objetivo con (Q), el proyectil atraviesa el cuerpo y traslada **TODAS las lanzas previas que tuviera ese objetivo al siguiente objetivo al que golpee**.
*   *Setup de High Elo:* Llenas al minion tanque de lanzas (4-5 stacks). Cuando tenga poca vida -> Lanzas Q al enemigo atravesando al minion -> El enemigo recibe el golpe de la Q (105% AD) + Todas las lanzas del minion (daño altísimo con E instantáneo).

### 1.3 W (Sentinel / Centinela)
*   **Visión:** Mandas un espectro que hace un recorrido y vuelve. Grita si ve al jungla enemigo. Revela campeones ocultos en arbustos (True Sight).
*   **Pacto de Daño (El por qué subes 1 punto a nivel 2 o 3):** Si el Support marcado ataca a un objetivo, Kalista aplica daño Mágico adicional equivalente al **14% - 18% de la Vida Máxima del enemigo** en su siguiente ataque. En fase de líneas esto es una bomba atómica encubierta. Tradea si el support pega.

### 1.4 E (Rend / Desgarrar) - Curvas de DPS & Gráficos de Ejecución
*   **Mecánica de Farmeo (Mana Refund):** Si (E) mata *al menos 1 unidad*, te devuelve su coste de maná completo y reduce su enfriamiento a 0. Esto permite "farmear gratis" eternamente. Rinde a 2 minions bajos de vida con la misma E.
*   **Auto-Reset:** El casteo de (E) no detiene tus auto-ataques. Puedes lanzar (E) literalmente a mitad de vuelo de un auto-ataque o tu `(Q)` en el aire y reseteará sin frenarte (Double trigger).

#### 📊 Gráfico 1: Escalado de Daño Rend (E) vs Armadura del Rival (Lvl 9)
En la fase media del juego, el número de lanzas necesarias para ejecutar varía drásticamente según la clase de armadura del objetivo. *(Base Matemática: AD Promedio = 150)*.

<div align="center">
  <code>Leyenda de Ejecución (Puntos de HP Restante vs Stacks para Lethal)</code>
  <pre>
[🛡️ SQUISHY - 40 Armor]    (ADC/Mages):  ▀ ▀ ▀ ▀ █ (4 Lanzas = Ejecución a ~450 HP)
[🛡️ BRUISER - 100 Armor]   (Fighters):   ▀ ▀ ▀ ▀ ▀ ▀ ▀ █ (7 Lanzas = Ejecución a ~550 HP)
[🛡️ TANK - 200+ Armor]     (Ornn/Sion):  ▀ ▀ ▀ ▀ ▀ ▀ ▀ ▀ ▀ ▀ ▀ ▀ █ (12+ Lanzas = Ejecución a ~700 HP)
  </pre>
</div>

#### 📉 Gráfico 2: Cruz de Escalado DPS (BotRK vs Rend E)
El daño óptimo de Kalista es una **"Estructura en X"**. Al inicio del combate, la Hoja del Rey (BotRK) hace daño masivo porque el rival tiene la vida llena (Damage % Current HP). A medida que la vida del rival baja, el DPS del BotRK cae brutalmente, pero el daño apilado de tus Lanzas de Rend sube exponencialmente.

<div align="center">
  <table border="1">
    <tr>
      <th>Fase del Combate (Vida del Rival)</th>
      <th>Daño Auto-ataque (BotRK % Actual)</th>
      <th>Poder Apilado de (Rend E)</th>
    </tr>
    <tr>
      <td><code>[ 100% HP ] 🟩🟩🟩🟩🟩</code></td>
      <td>█████████ (Máximo)</td>
      <td>▏ (Cero)</td>
    </tr>
    <tr>
      <td><code>[  75% HP ] 🟨🟨🟨🟨</code></td>
      <td>██████ (Alto)</td>
      <td>███ (Despertando)</td>
    </tr>
    <tr>
      <td><code>[  50% HP ] 🟧🟧🟧</code></td>
      <td>████ (Medio)</td>
      <td>██████ (Zona Peligro)</td>
    </tr>
    <tr>
      <td><code>[  25% HP ] 🟥</code></td>
      <td>█ (Irrelevante)</td>
      <td>█████████ (<b>LETHAL EXECUTION</b>)</td>
    </tr>
  </table>
  <p><i>Conclusión Táctica: Nunca detones la E antes de llegar a la zona naranja/roja. Si lo haces antes, destruirás el cruce de escalado matemático.</i></p>
</div>

*   **Límites de Daño Épicos (Barón / Dragón):** El daño es acumulable en escala hasta matar a un dragón o al mismísimo barón. Al tener un scaling garantizado de tu AD por cada lanza extra, con 40 lanzas (y la penetración de armor pasiva), puedes prever entre **2400-3000 Puntos de Daño**, lo cual sobreescribe instantáneamente al *Smite / Aplastar* del jungla (que hace un máximo de 1200 a nivel 18). Eres la dueña absoluta del control de objetivos.

### 1.5 R (Fate's Call / Llamada del Destino)
*   Atrae al Support a Stasis absoluto (inmune). Ellos teclean click-derecho para lanzarse con un Knock-up AoE.
*   **Rango Máximo de Tiro:** Pueden lanzarse hasta el límite de la red visible o a través de paredes medias (ej. Pits de Dragón).
*   **El Rescate Extremo:** Puedes castearlo incluso si estás stuneado, pero puedes salvar al support si van a morir aplastados por la torre o por el Ignite (la Stasis limpia todo mal temporal).

---

## 🛠️ 2. Itemización y Matemáticas (El "Por Qué")

Kalista rompe los estándares de las builds comunes debido a su necesidad absoluta de supervivencia y aplicación constante de On-Hit para stackear espadas de (E).

### Build "Shredder" Táctico (Core Meta 26.7)
1. <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/item/3006.png" width="16"> **Grebas de Berserker (Boots T2)**: `Compralas en Recall 1`. Siempre. ¿Por qué? Kalista no puede esquivar hooks (Nautilus, Thresh, Blitzcrank) si no salta largo. Las grebas completan tu rango de salto defensivo. El AD aquí es irrelevante sin las botas grandes.
2. <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/item/3153.png" width="16"> **Hoja del Rey Arruinado (BotRK)**: Daño por `% Health Mínima`. Sinergia brutal, porque además roba velocidad de movimiento. Si combinas la pasiva del BotRK robando Movement Speed + la ralentización de tu (E) desgarrar, es matemáticamente imposible que un peleador sin Dash te alcance.
3. <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/item/3124.png" width="16"> **Guinsoo's Rageblade**:
    *   **¿Por qué?** Porque su Pasiva de "Ataque Fantasma" duplica los efectos On-Hit cada 3 auto-ataques. Esto incluye **agregar lanzas de Rend (E) EL DOBLE DE RÁPIDO**. En peleas donde necesitas stackear lanzas en el tanque rápidamente, esto acorta a la mitad el tiempo requerido para matarlo.
4. <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/item/3302.png" width="16"> **Terminus**:
    *   Daño Mágico, Daño Físico y te da progresiones masivas de Armadura (Armor) y Resistencia Mágica. Kalista vive en el filo de la navaja (corto rango), por lo que ganar Resistencias gratuitas al golpear te mantiene vivo contra Asesinos que logran hacerte gap-close.

### Situacionales Importantes
*   **Runaan's Hurricane (3085)**: La aplicación de los tornados es tratada como un ataque básico puro. **SI** que stackean lanzas de (E) en todos los targets golpeados. En combates encajonados en el río o la jungla profunda, te permite explotar a los 3 campeones a la redonda de un solo flash + E.

---

## 🔮 3. Análisis de Runas & Micro-Shards (Parche 26.7)

### Árbol Principal (Keystones)
*   **Lethal Tempo**: Mandatorio el 90% de partidas. Te permite cruzar el límite de 2.0 AS, pero **recuerda la regla de oro**: Si superas 2.0 AS, deja de saltar o perderás DPS.
*   **Press the Attack (PTA)**: Usar solo si el draft rival tiene 4+ Squishies (Asesinos/Magos). PTA + Q + E es una ejecución semi-instantánea.
*   **Secundarias (Obligatorias):**
    *   *Triunfo*: Crucial en Kalista porque al tener rango bajo (525), vivirás en la zona de fuego cruzado.
    *   *Coup de Grace* vs *Cut Down*: Activa `Cut Down` siempre si hay más de 1 tanque (>3000 HP). Se multiplica exponencialmente con el Rendeo (E) en tanques.
*   **Árbol Secundario (Valor):**
    *   *Condicionamiento + Sobrecrecimiento*: Transforma a Kalista en rango de "Bruiser" (Off-Tank) llegada la marca de los 12 minutos.

### 🧬 Interfaces de Micro-Fragmentos (Stats Shards)
Kalista escala drásticamente distinto dependiendo de qué Micro-Runas le equipes, calculando el umbral de utilidad a Nivel 6.

<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/perk-images/StatMods/StatModsAttackSpeedIcon.png" width="18"> <b>Slot 1 (Ofensiva)</b> | <kbd>10% Attack Speed</kbd></summary>
<blockquote><b>Operativa Táctica:</b> Ni lo pienses. El AS = Velocidad de Salto Pasivo Nivel 1. Es el único requerimiento obligatorio de este árbol.</blockquote></details>

<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/perk-images/StatMods/StatModsAdaptiveForceIcon.png" width="18"> <b>Slot 2 (Flexible)</b> | <kbd>+9 Daño Plano</kbd> vs <kbd>+2% Move Speed</kbd></summary>
<blockquote><b>Operativa Táctica:</b> AD asegura presión bruta a Nivel 1 para dominar. Velocidad de Movimiento incrementa tu supervivencia pasiva porque mejora las distancias inter-salto vs Skillshots rápidos.</blockquote></details>

<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/perk-images/StatMods/StatModsHealthPlusIcon.png" width="18"> <b>Slot 3 (Defensa)</b> | <kbd>+65 HP Plano</kbd> vs <kbd>HP Progresiva</kbd></summary>
<blockquote><b>Punto de Quiebre Matemático:</b> A Nivel 1, los 65 HP absorbén un Ignite temprano entero. A <b>Nivel 6</b>, la Vida Progresiva cruza su umbral (>65 HP) y asciende hasta 180 HP.<br>
<img src="https://img.shields.io/badge/Matchup-Seguro-green.svg"> Usa <b>Vida Progresiva</b> contra rivales pasivos para tanquear escudos de arco.<br>
<img src="https://img.shields.io/badge/Matchup-Riesgoso-red.svg"> Usa <b>Vida Plana</b> contra Lucian/Draven o morirás pre-6.</blockquote></details>

---

### 📈 Curvas de Rendimiento (Trading Power Spikes)
Análisis de volatilidad y capitalización de combate de Kalista según la franja temporal. Las "Velas" representan la eficacia porcentual esperada de su kit contra hiper-carries de Late Game (eg. Jinx/Vayne).

| Plazo Temporal (Macro) | Tendencia Base del Mercado | Volatilidad (Requisito E) | Curva de Impacto (Candlestick Spike) |
| :---: | :---: | :---: | :--- |
| **Early Game (0 - 15m)** | 🐂 BULL (Alza Fuerte) | 🔴 Extrema (Requiere Dominio) | `  ▄▆███▇▅▃ ` *(Snowball obligatorio. BotRK Rush)* |
| **Mid Game (15 - 25m)** | ⚖️ STABLE (Meseta) | 🟡 Media (Objectivos) | ` ▃▅▆▇██▆▄ ` *(Pico de eficiencia con Barones a 40 stacks E)* |
| **Late Game (25m+)** | 🐻 BEAR (Caída Constante) | 🟢 Baja (Caída de AS y Armor) | `       ▂▄ ` *(Dependes 100% de iniciación con tu Support y R)* |

---

## 🤝 4. Database de Oathsworn: Top 10 Sinergias
<p><i>Interfaz de Sistema (Despliega para cargar Protocolo de Sinergia)</i></p>

<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Renata.png" width="22"> <b>Renata Glasc</b> | <kbd>⭐ S+ (DIOS)</kbd> | <i>Resurrection Engine</i></summary>
<blockquote><b>Protocolo (R):</b> Renata W te mantiene con vida. Si ella muere, casteas R y la lanzas hacia el enemigo. Ella aplica el Knockup, asegurando la baja y su resurrección automática.</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Taric.png" width="22"> <b>Taric</b> | <kbd>⭐ S+</kbd> | <i>Dive Bomb Invencible</i></summary>
<blockquote><b>Protocolo (R):</b> Taric canaliza R (Inmunidad) en el aire mientras tú le usas la R de escudo de lanzamiento. Un cometa invulnerable aplasta la backline. Rompe el juego 100%.</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Nautilus.png" width="22"> <b>Nautilus</b> | <kbd>🟢 S</kbd> | <i>Engage Absolute</i></summary>
<blockquote><b>Protocolo (R):</b> Perfecto front-laner. Absorbe burst, luego le usas R encima de la cara del enemigo como un CC en cadena infinito e inesquivable.</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Leona.png" width="22"> <b>Leona</b> | <kbd>🟢 S</kbd> | <i>Lockdown Sostenido</i></summary>
<blockquote><b>Protocolo (R):</b> Leona permite un engage seguro que detona el Daño Pactado de tu (W) instantáneamente y de manera repetida en un radio ineludible.</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Thresh.png" width="22"> <b>Thresh</b> | <kbd>🟢 S</kbd> | <i>El Rescate Eterno</i></summary>
<blockquote><b>Protocolo (R):</b> Rescate universal. Tú lo tiras para iniciar, él te tira la Linterna para salir. Movilidad estrambótica de 1000 rango creando un bucle intocable.</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Rell.png" width="22"> <b>Rell</b> | <kbd>🟢 S</kbd> | <i>Bomba Magnética</i></summary>
<blockquote><b>Protocolo (R):</b> La lanzas como un misil, activa su propia R en el centro de tu impacto y desinstala a los 5 personajes rivales juntos. La mejor teamfight del juego.</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Blitzcrank.png" width="22"> <b>Blitzcrank</b> | <kbd>🟡 A</kbd> | <i>Kidnapper Loop</i></summary>
<blockquote><b>Protocolo (R):</b> Tira el Hook (Agarrón), tu le echas R e instantáneamente secuestráis al rival arrastrándolo bajo vuestra propia torre. Riesgoso pero ejecución letal segura.</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Alistar.png" width="22"> <b>Alistar</b> | <kbd>🟡 A</kbd> | <i>Peel Inmatable</i></summary>
<blockquote><b>Protocolo (R):</b> Si él falla su combo, tú arreglas el error recogiéndolo con la (R). Si engancha bien, saltáis juntos. Mezclar ambas ultimates lo hace inmatable a cualquier burst.</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Braum.png" width="22"> <b>Braum</b> | <kbd>🟡 A</kbd> | <i>Escudo Deflector</i></summary>
<blockquote><b>Protocolo (R):</b> Con tu altísima velocidad de salto, multiplicas las cargas de stun pasivas de Braum rápidamente saltando alrededor del equipo rival bloqueando proyectiles.</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Karma.png" width="22"> <b>Karma</b> | <kbd>🟠 B</kbd> | <i>Speed Dominance</i></summary>
<blockquote><b>Protocolo (R):</b> El escudo+velocidad de Karma a Nivel 1 compite con tu Rend maravillosamente. Pero a Late Game no aguanta estar de proyectil y se diluye en utilidad ofensiva.</blockquote></details>

<br>

---

## ⚔️ 5. Mercado de Matchups: Análisis Volátil (15 ADCs)
<p><i>Terminal Activa: Haz clic para desplegar Trading Specs y Algoritmo de Build.</i></p>

<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Ashe.png" width="22"> <b>Ashe</b> | <img src="https://img.shields.io/badge/Riesgo-EXTREMO-black.svg"> | Spike: <code>`█▇▆▅▄▃▂ `</code></summary>
<blockquote><b>Operativa:</b> El slow arruina los <i>frames</i> de tu salto pasivo disminuyendo tu cap DPS un 65%. Debes purificar el <i>Slow</i> siempre o evita la pelea.<br>
<b>Algoritmo Build:</b> <kbd>Cleanse Obligatorio</kbd> + <kbd>Lethality Burst</kbd> (No prolongues las peleas).</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Draven.png" width="22"> <b>Draven</b> | <img src="https://img.shields.io/badge/Riesgo-ALTO-red.svg"> | Spike: <code>`  ▄▆███▇▅▃ `</code></summary>
<blockquote><b>Operativa:</b> DPS plano base superior al tuyo si no detonas la E. Predice el aterrizaje de su hacha en el suelo y golpéalo impunemente con la (Q) Pierce. Pide presión.<br>
<b>Algoritmo Build:</b> <kbd>Botas Tabis (Placas de Acero)</kbd> + <kbd>Terminus</kbd>.</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Vayne.png" width="22"> <b>Vayne</b> | <img src="https://img.shields.io/badge/Riesgo-ALTO-red.svg"> | Spike: <code>` ▃▅▆▇████ `</code></summary>
<blockquote><b>Operativa:</b> Interacción de Late Limit. La destrozas en Early, pero si llega al min 25 te matará en 3 básicos invisibles de daño True. Debes terminar el Macro juego antes.<br>
<b>Algoritmo Build:</b> <kbd>Terminus (Hyper Resistencias Mágicas/Armor)</kbd>.</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Xayah.png" width="22"> <b>Xayah</b> | <img src="https://img.shields.io/badge/Riesgo-ALTO-red.svg"> | Spike: <code>`  ▃▅██▅▃ `</code></summary>
<blockquote><b>Operativa:</b> Su pasiva llena el campo de plumas. <b>NUNCA</b> des un salto hacia atrás en línea recta. Siempre salta formando un círculo perfecto alrededor suyo (Zoning Dodge).<br>
<b>Algoritmo Build:</b> <kbd>Shieldbow</kbd> (Absorción de <i>Bladecaller E</i>).</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Caitlyn.png" width="22"> <b>Caitlyn</b> | <img src="https://img.shields.io/badge/Riesgo-MODERADO-orange.svg"> | Spike: <code>`  ██▆▅▄▃▂ `</code></summary>
<blockquote><b>Operativa:</b> Rango 650 asfixiante que te bloquea maniobras de salto. Abusa del passthrough transfiriendo lanzas E a través de los minions. Ejecuta full All-In nivel 6 con Flash.<br>
<b>Algoritmo Build:</b> <kbd>Runaan's Hurricane</kbd> (Clear wave instántaneo).</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Lucian.png" width="22"> <b>Lucian</b> | <img src="https://img.shields.io/badge/Riesgo-MODERADO-orange.svg"> | Spike: <code>` ▃▅██▅▃ `</code></summary>
<blockquote><b>Operativa:</b> Si usa Dashes pasivos defensivos, abusa sus 13s de cooldown iniciales. Modifica tu trayectoria de salto a 45 grados de su Dash para que falle su Luz Lacerante.<br>
<b>Algoritmo Build:</b> <kbd>Placas de Acero</kbd> (Reducción pasiva a sus dobles auto-ataques).</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Samira.png" width="22"> <b>Samira</b> | <img src="https://img.shields.io/badge/Riesgo-MODERADO-orange.svg"> | Spike: <code>`   ▃▅████ `</code></summary>
<blockquote><b>Operativa:</b> Un mal click te destruye. Su (W) <i>Blade Whirl</i> borra toda detonación de Rend E que intentes volar en ella. Debes baitarlo. Utiliza (R) como counter a su Ultimate.<br>
<b>Algoritmo Build:</b> <kbd>Guinsoo</kbd> (Duplicador de acumulaciones masivas rápidas).</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Aphelios.png" width="22"> <b>Aphelios</b> | <img src="https://img.shields.io/badge/Riesgo-MODERADO-orange.svg"> | Spike: <code>`  ▃▅████ `</code></summary>
<blockquote><b>Operativa:</b> Checkea sus cartuchos pasivos siempre. Tienes unos 30s de ventana donde el arma Severum/Crescendum están agotadas; ese es tu margen analítico de All-In seguro.<br>
<b>Algoritmo Build:</b> <kbd>Burst Lethality System</kbd>.</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Varus.png" width="22"> <b>Varus</b> | <img src="https://img.shields.io/badge/Riesgo-MODERADO-orange.svg"> | Spike: <code>` ▃▄▇██▅▃ `</code></summary>
<blockquote><b>Operativa:</b> Ambas de sus versiones (AP %HP / Lethalidad) te obligan a esquivar perfect-frame. Evita su flecha R pasiva; si te frena sin pasiva te elimina el 100% HP de una carga C.<br>
<b>Algoritmo Build:</b> <kbd>Terminus</kbd> + <kbd>Shieldbow</kbd> (Capa mágica).</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Jinx.png" width="22"> <b>Jinx</b> | <img src="https://img.shields.io/badge/Riesgo-BAJO-green.svg"> | Spike: <code>` ▂▃▅▆▇██ `</code></summary>
<blockquote><b>Operativa:</b> Dominancia absoluta Nvl 1 al 9. Congela las líneas forzándola a arriesgarse al farm. Píllala con doble avance salteado y detona un passthrough a los meeles.<br>
<b>Algoritmo Build:</b> <kbd>Assassin Lethality</kbd> (Ignórala en tank, ciérrala y hazla split-push).</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Kaisa.png" width="22"> <b>Kai'Sa</b> | <img src="https://img.shields.io/badge/Riesgo-BAJO-green.svg"> | Spike: <code>` ▂▃▅██▇▄ `</code></summary>
<blockquote><b>Operativa:</b> Mecísima macro. Pelea siempre **dentro de tu propia oleada** para anular la "Isolation" de su Q de misiles. Sin su Q max damage, tu Rend siempre gana en DPS cruzado.<br>
<b>Algoritmo Build:</b> <kbd>Guinsoo</kbd> puro core.</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Twitch.png" width="22"> <b>Twitch</b> | <img src="https://img.shields.io/badge/Riesgo-BAJO-green.svg"> | Spike: <code>` ▂▄▆███ `</code></summary>
<blockquote><b>Operativa:</b> Precaución de la letalidad invisible de flanqueo. Lleva Exhaust; cuando quite invisibilidad aplicas CC de exhaust y saltándole en la cara mitigas el 50% de daño de su ballesta.<br>
<b>Algoritmo Build:</b> <kbd>Shieldbow</kbd>.</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Jhin.png" width="22"> <b>Jhin</b> | <img src="https://img.shields.io/badge/Riesgo-BAJO-green.svg"> | Spike: <code>` ▃▄▆▇▅▃ `</code></summary>
<blockquote><b>Operativa:</b> Sistema predecible. Su 4to tiro requiere animaciones largas que puedes evadir dadas las velocidades de tus hops. Te sales del rango y entras post-ataque. Facilísimo.<br>
<b>Algoritmo Build:</b> <kbd>BotRK</kbd> (Robar pasiva MoveSpeed imposibilita su kiting).</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Zeri.png" width="22"> <b>Zeri</b> | <img src="https://img.shields.io/badge/Riesgo-BAJO-green.svg"> | Spike: <code>` ▂▃▄▅▇█ `</code></summary>
<blockquote><b>Operativa:</b> Zeri dispara Skillshots. Tus hops constantes vuelven prácticamente imposible a una Zeri landear impactos limpios ininterrumpidos. Error de Macro al seleccionar a Zeri aquí.<br>
<b>Algoritmo Build:</b> <kbd>On-Hit Placas Armor</kbd>.</blockquote></details>
<details><summary><img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Ezreal.png" width="22"> <b>Ezreal</b> | <img src="https://img.shields.io/badge/Riesgo-BAJO-green.svg"> | Spike: <code>` ▃▅▆██▅ `</code></summary>
<blockquote><b>Operativa:</b> Escudado de Minions bloquea casi todo daño real. Sus hops laterales le hacen fallar (Q) todo el combate. Su E defensiva apenas evita que tus lanzas adheridas sigan restando su vida.<br>
<b>Algoritmo Build:</b> <kbd>BotRK + Berserker Rush</kbd>.</blockquote></details>

<div align="center">
  <br>
  <p><i>"Nuestra fe... nos ata." — Kalista.</i></p>
</div>