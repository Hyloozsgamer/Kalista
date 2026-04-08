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

### 🧬 INFOGRAFÍA DE MICRO-FRAGMENTOS (SHARDS)
Kalista escala drásticamente distinto dependiendo de qué Micro-Runas le equipes, cruzando su punto de quiebre algorítmico exactamente a **Nivel 6**.

<table width="100%">
  <tr>
    <td width="33%" align="center">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/item/1042.png" width="50" style="border-radius: 5px;"><br>
      <b><kbd>10% ATTACK SPEED</kbd></b><br><hr>
      <p><i>Obligatorio. Define de forma directa la constante de velocidad de tu Salto a Nivel 1.</i></p>
    </td>
    <td width="33%" align="center">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/item/1036.png" width="50" style="border-radius: 5px;"><br>
      <b><kbd>+9 DAÑO AD / +MOVE SPEED</kbd></b><br><hr>
      <p><i>AD asegura presión bruta temprana.<br> Move Speed te aisla contra skillshots rápidos en Mid-Game.</i></p>
    </td>
    <td width="33%" align="center">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/item/1028.png" width="50" style="border-radius: 5px;"><br>
      <b><kbd>+65 HP vs HP PROGRESIVA</kbd></b><br><hr>
      <p><b>Punto de Quiebre (Lvl 6):</b><br>
      <img src="https://img.shields.io/badge/Matchup-Seguro-green.svg"> Usa HP Progresiva contra Matchups pasivos.<br>
      <img src="https://img.shields.io/badge/Matchup-Letal-red.svg"> Usa los 65 HP planos contra Lucian/Draven o morirás al 'Ignite' inicial.</p>
    </td>
  </tr>
</table>

---

### 📈 Curvas de Rendimiento (Trading Power Spikes)
Análisis de volatilidad y capitalización de combate de Kalista según la franja temporal. Las "Velas" representan la eficacia porcentual esperada de su kit contra hiper-carries de Late Game (eg. Jinx/Vayne).

| Plazo Temporal (Macro) | Tendencia Base del Mercado | Volatilidad (Requisito E) | Curva de Impacto (Candlestick Spike) |
| :---: | :---: | :---: | :--- |
| **Early Game (0 - 15m)** | 🐂 BULL (Alza Fuerte) | 🔴 Extrema (Requiere Dominio) | `  ▄▆███▇▅▃ ` *(Snowball obligatorio. BotRK Rush)* |
| **Mid Game (15 - 25m)** | ⚖️ STABLE (Meseta) | 🟡 Media (Objectivos) | ` ▃▅▆▇██▆▄ ` *(Pico de eficiencia con Barones a 40 stacks E)* |
| **Late Game (25m+)** | 🐻 BEAR (Caída Constante) | 🟢 Baja (Caída de AS y Armor) | `       ▂▄ ` *(Dependes 100% de iniciación con tu Support y R)* |

---

## 🤝 4. DATABASE DE OATHSWORN (SUPPORT INFOGRAPHIC)
<p><i>Interfaz de Sinergia (Elige con cuidado a quién le lanzas la Spear)</i></p>

<table width="100%">
  <tr>
    <td width="20%" align="center">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Renata.png" width="50" style="border-radius: 50%;"><br>
      <b>Renata</b><br><kbd>⭐ S+</kbd><hr>
      <p style="font-size: 11px;"><i>Invencibilidad (R)</i></p>
    </td>
    <td width="20%" align="center">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Taric.png" width="50" style="border-radius: 50%;"><br>
      <b>Taric</b><br><kbd>⭐ S+</kbd><hr>
      <p style="font-size: 11px;"><i>Bombardeo Dive (R)</i></p>
    </td>
    <td width="20%" align="center">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Nautilus.png" width="50" style="border-radius: 50%;"><br>
      <b>Nautilus</b><br><kbd>🟢 S</kbd><hr>
      <p style="font-size: 11px;"><i>Cadena CC Infinita</i></p>
    </td>
    <td width="20%" align="center">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Leona.png" width="50" style="border-radius: 50%;"><br>
      <b>Leona</b><br><kbd>🟢 S</kbd><hr>
      <p style="font-size: 11px;"><i>Detonador Mágico Pacto W</i></p>
    </td>
    <td width="20%" align="center">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Thresh.png" width="50" style="border-radius: 50%;"><br>
      <b>Thresh</b><br><kbd>🟢 S</kbd><hr>
      <p style="font-size: 11px;"><i>Doble Escape (Lantern R)</i></p>
    </td>
  </tr>
  <tr>
    <td width="20%" align="center">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Rell.png" width="50" style="border-radius: 50%;"><br>
      <b>Rell</b><br><kbd>🟢 S</kbd><hr>
      <p style="font-size: 11px;"><i>Imán (Ultimate Combo)</i></p>
    </td>
    <td width="20%" align="center">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Blitzcrank.png" width="50" style="border-radius: 50%;"><br>
      <b>Blitzcrank</b><br><kbd>🟡 A</kbd><hr>
      <p style="font-size: 11px;"><i>Secuestro a Rango</i></p>
    </td>
    <td width="20%" align="center">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Alistar.png" width="50" style="border-radius: 50%;"><br>
      <b>Alistar</b><br><kbd>🟡 A</kbd><hr>
      <p style="font-size: 11px;"><i>Peel Absoluto Inmatable</i></p>
    </td>
    <td width="20%" align="center">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Braum.png" width="50" style="border-radius: 50%;"><br>
      <b>Braum</b><br><kbd>🟡 A</kbd><hr>
      <p style="font-size: 11px;"><i>Pared Deflectora Rápida</i></p>
    </td>
    <td width="20%" align="center">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Karma.png" width="50" style="border-radius: 50%;"><br>
      <b>Karma</b><br><kbd>🟠 B</kbd><hr>
      <p style="font-size: 11px;"><i>Speed Temprano. Decae Late.</i></p>
    </td>
  </tr>
</table>

<br>

---

## ⚔️ 5. Mercado de Matchups: Análisis Volátil (15 ADCs)
<p><i>Terminal Activa: Haz clic para desplegar Trading Specs y Algoritmo de Build.</i></p>

<table width="100%">
  <tr>
    <td width="20%" align="center" style="background:#1a0f0f;">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Ashe.png" width="50" style="border-radius: 50%;"><br>
      <b>Ashe</b><br><img src="https://img.shields.io/badge/Riesgo-EXTREMO-black.svg"><hr>
      <p style="font-size: 11px;"><i>Slow arruina Salto</i><br><kbd>Cleanse</kbd></p>
    </td>
    <td width="20%" align="center" style="background:#2d1313;">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Draven.png" width="50" style="border-radius: 50%;"><br>
      <b>Draven</b><br><img src="https://img.shields.io/badge/Riesgo-ALTO-red.svg"><hr>
      <p style="font-size: 11px;"><i>Supera tu DPS base</i><br><kbd>Tabis</kbd></p>
    </td>
    <td width="20%" align="center" style="background:#2d1313;">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Vayne.png" width="50" style="border-radius: 50%;"><br>
      <b>Vayne</b><br><img src="https://img.shields.io/badge/Riesgo-ALTO-red.svg"><hr>
      <p style="font-size: 11px;"><i>Limit-Test en Late</i><br><kbd>Terminus</kbd></p>
    </td>
    <td width="20%" align="center" style="background:#2d1313;">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Xayah.png" width="50" style="border-radius: 50%;"><br>
      <b>Xayah</b><br><img src="https://img.shields.io/badge/Riesgo-ALTO-red.svg"><hr>
      <p style="font-size: 11px;"><i>Peligro de Plumas</i><br><kbd>Shieldbow</kbd></p>
    </td>
    <td width="20%" align="center" style="background:#26180b;">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Caitlyn.png" width="50" style="border-radius: 50%;"><br>
      <b>Caitlyn</b><br><img src="https://img.shields.io/badge/Riesgo-MEDIO-orange.svg"><hr>
      <p style="font-size: 11px;"><i>Abusa del Rango 650</i><br><kbd>Runaan's</kbd></p>
    </td>
  </tr>
  <tr>
    <td width="20%" align="center" style="background:#26180b;">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Lucian.png" width="50" style="border-radius: 50%;"><br>
      <b>Lucian</b><br><img src="https://img.shields.io/badge/Riesgo-MEDIO-orange.svg"><hr>
      <p style="font-size: 11px;"><i>Dash Ofensivo Cds</i><br><kbd>Tabis</kbd></p>
    </td>
    <td width="20%" align="center" style="background:#26180b;">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Samira.png" width="50" style="border-radius: 50%;"><br>
      <b>Samira</b><br><img src="https://img.shields.io/badge/Riesgo-MEDIO-orange.svg"><hr>
      <p style="font-size: 11px;"><i>Su W borra tu E</i><br><kbd>Guinsoo</kbd></p>
    </td>
    <td width="20%" align="center" style="background:#26180b;">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Aphelios.png" width="50" style="border-radius: 50%;"><br>
      <b>Aphelios</b><br><img src="https://img.shields.io/badge/Riesgo-MEDIO-orange.svg"><hr>
      <p style="font-size: 11px;"><i>Vigilar armas rojas/blancas</i><br><kbd>Lethality</kbd></p>
    </td>
    <td width="20%" align="center" style="background:#26180b;">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Varus.png" width="50" style="border-radius: 50%;"><br>
      <b>Varus</b><br><img src="https://img.shields.io/badge/Riesgo-MEDIO-orange.svg"><hr>
      <p style="font-size: 11px;"><i>Blockear R obligatorio</i><br><kbd>Shieldbow</kbd></p>
    </td>
    <td width="20%" align="center" style="background:#132616;">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Jinx.png" width="50" style="border-radius: 50%;"><br>
      <b>Jinx</b><br><img src="https://img.shields.io/badge/Riesgo-BAJO-green.svg"><hr>
      <p style="font-size: 11px;"><i>Early dominado facil</i><br><kbd>Assassin</kbd></p>
    </td>
  </tr>
  <tr>
    <td width="20%" align="center" style="background:#132616;">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Kaisa.png" width="50" style="border-radius: 50%;"><br>
      <b>Kai'Sa</b><br><img src="https://img.shields.io/badge/Riesgo-BAJO-green.svg"><hr>
      <p style="font-size: 11px;"><i>Pelear entre minions</i><br><kbd>Guinsoo</kbd></p>
    </td>
    <td width="20%" align="center" style="background:#132616;">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Twitch.png" width="50" style="border-radius: 50%;"><br>
      <b>Twitch</b><br><img src="https://img.shields.io/badge/Riesgo-BAJO-green.svg"><hr>
      <p style="font-size: 11px;"><i>Exhaust en aparición</i><br><kbd>Shieldbow</kbd></p>
    </td>
    <td width="20%" align="center" style="background:#132616;">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Jhin.png" width="50" style="border-radius: 50%;"><br>
      <b>Jhin</b><br><img src="https://img.shields.io/badge/Riesgo-BAJO-green.svg"><hr>
      <p style="font-size: 11px;"><i>4to tiro evadible pasivamente</i><br><kbd>BotRK</kbd></p>
    </td>
    <td width="20%" align="center" style="background:#132616;">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Zeri.png" width="50" style="border-radius: 50%;"><br>
      <b>Zeri</b><br><img src="https://img.shields.io/badge/Riesgo-BAJO-green.svg"><hr>
      <p style="font-size: 11px;"><i>Esquivas Q solas saltando</i><br><kbd>Tabis</kbd></p>
    </td>
    <td width="20%" align="center" style="background:#132616;">
      <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Ezreal.png" width="50" style="border-radius: 50%;"><br>
      <b>Ezreal</b><br><img src="https://img.shields.io/badge/Riesgo-BAJO-green.svg"><hr>
      <p style="font-size: 11px;"><i>Bloquea Q con creeps</i><br><kbd>BotRK+Berserk</kbd></p>
    </td>
  </tr>
</table>

<div align="center">
  <br>
  <p><i>"Nuestra fe... nos ata." — Kalista.</i></p>
</div>