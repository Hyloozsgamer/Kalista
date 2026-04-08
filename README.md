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

## 🔮 3. Runas Optimizadas (Parche 26.7)

*   **Principal:** Precisión 
    *   **Lethal Tempo**: Vital para la agresividad de nivel 1 y la escalada On-Hit a Mid Game. (Alternativa: Press the Attack si quieres hiper-explotar objetivos en línea con el combo Q+E).
    *   **Triunfo**: Indispensable dada tu naturaleza cortadistancias; a veces te curará esa vida que te salva del Ignite.
    *   **Leyenda: Alacrity/Velocidad**: Sinergia base de DPS puro. (Sustituir por Bloodline solo si vas The Collector, pero AS% puro es mejor por su pasiva).
    *   **Coup de Grace (Golpe de Gracia)** // **Cut Down**: `Cut Down` siempre si el support rival o jungla tienen +3000 de HP. Modifica las matemáticas del (E).
*   **Secundaria:** Valor (Resolve)
    *   **Bone Plating (Revestimiento de Huesos)** o **Conditioning (Condicionamiento)**: Bone Plating en fase de líneas duras asegurará ganar el 2v2 o 1v1. Condicionamiento te vuelve un TANK hibridado en Lete Game.
    *   **Overgrowth (Sobrecrecimiento)**: Más vida máxima hace que el Shieldbow no pete rápido.

---

### 📈 Curvas de Rendimiento (Trading Power Spikes)
Análisis de volatilidad y capitalización de combate de Kalista según la franja temporal. Las "Velas" representan la eficacia porcentual esperada de su kit contra hiper-carries de Late Game (eg. Jinx/Vayne).

| Plazo Temporal (Macro) | Tendencia Base del Mercado | Volatilidad (Requisito E) | Curva de Impacto (Candlestick Spike) |
| :---: | :---: | :---: | :--- |
| **Early Game (0 - 15m)** | 🐂 BULL (Alza Fuerte) | 🔴 Extrema (Requiere Dominio) | `  ▄▆███▇▅▃ ` *(Snowball obligatorio. BotRK Rush)* |
| **Mid Game (15 - 25m)** | ⚖️ STABLE (Meseta) | 🟡 Media (Objectivos) | ` ▃▅▆▇██▆▄ ` *(Pico de eficiencia con Barones a 40 stacks E)* |
| **Late Game (25m+)** | 🐻 BEAR (Caída Constante) | 🟢 Baja (Caída de AS y Armor) | `       ▂▄ ` *(Dependes 100% de iniciación con tu Support y R)* |

---

## 🤝 4. Matriz de Oathsworn (Supports) Expandida (Top 10)

La conexión del *Black Spear* dictamina tu destino de línea de draft. Cero heurísticas pasivas.

| Support Oathsworn | Categoría | Macro Game Synergy | Detalle de Interacciones de Marco R |
| :--- | :---: | :--- | :--- |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Renata.png" width="25"> **Renata Glasc** | ⭐ **S+** | *Resurrection Engine* | Renata W te mantiene con vida. Si ella muere, casteas R y aplicas Knockup para asegurar la baja y resucitar. |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Taric.png" width="25"> **Taric** | ⭐ **S+** | *Dive Bomb Invencible* | Taric canaliza R en estasis de salto. Un cometa invulnerable aplasta la backline. Rompe el juego 100%. |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Nautilus.png" width="25"> **Nautilus** | 🟢 **S** | *Engage Total (Puntual)* | El mejor front-line absoluto. Absorbe burst, luego le usas R encima de sus caras como un CC en cadena infinito. |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Leona.png" width="25"> **Leona** | 🟢 **S** | *Lockdown Sostenido* | Leona permite un engage seguro que detona el Daño Pactado de tu W instántaneamente de manera repetida. |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Thresh.png" width="25"> **Thresh** | 🟢 **S** | *Seguridad Doble* | Rescate universal. Tú lo tiras para iniciar, él te tira la Linterna. Movilidad estrambótica de 1000 rango. |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Rell.png" width="25"> **Rell** | 🟢 **S** | *Bomba Magnética* | La lanzas como un misil, activa su propia R en el centro y desinstala a los 5 personajes rivales juntos. |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Blitzcrank.png" width="25"> **Blitzcrank** | 🟡 **A** | *Kidnapper Loop* | Tira el Hook (Agarrón), tu le echas R e instantáneamente secuestráis al rival bajo vuestra propia torre. Riesgoso pero Letal. |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Alistar.png" width="25"> **Alistar** | 🟡 **A** | *Peel de Bloques* | Su combo requiere timing, pero si fallan su engage tú arreglas el error recogiéndolo. Inmatable al mezclar las RS. |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Braum.png" width="25"> **Braum** | 🟡 **A** | *Protección Pasiva* | Con tu pasiva de saltos multiplicas las cargas de stun del escudo de Braum rápidamente saltando alrededor. |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Karma.png" width="25"> **Karma** | 🟠 **B** | *Poke Dominance* | Escudo/Speed Lv1 compite con tu Rend, pero a Late Game no aguanta estar de proyectil y morirá. |

---

## ⚔️ 5. Matriz de Matchups Ampliada (15 ADCs)

*El mercado de bot lane es puro trading de golpes. Elige tu stock sabiamente basándote en los power spikes (Early Bull / Late Bear).*

| ADC Rivales | Riesgo | Volatilidad / Curva de Matchup | Estratégia de Líneas & Teamfight | Modifications Build |
| :--- | :---: | :--- | :--- | :--- |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Ashe.png" width="25"> **Ashe** | 💀💀 EXTREMO | 🔴 `█▇▆▅▄▃▂ ` (Caes en Picado) | El slow arruina los *frames* de salto pasivo. Debes purificar el *Slow*. Solo inicia a melee con R. | **Cleanse / Lethality Burst**. |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Draven.png" width="25"> **Draven** | 🔴 ALTO | 🔴 `  ▄▆███▇▅▃ ` | DPS plano superior al tuyo sin E. Predice el aterrizaje de su hacha y pégale (Q). Pide Ganks. | **Botas Tabis / Armor**. |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Vayne.png" width="25"> **Vayne** | 🔴 ALTO | 🟡 ` ▃▅▆▇████ ` (Te supera Late) | La destrozas en Early, pero si llega al min 25 te matará en 3 básicos invisibles. Trata de ganar antes. | **Terminus (Stats híbridos)** |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Xayah.png" width="25"> **Xayah** | 🔴 ALTO | 🟡 `  ▃▅██▅▃ ` | Su pasiva llena el piso de plumas. NUNCA saltes hacia atrás en línea recta. Siempre salta lateral (Side-hopping). | **Shieldbow (Protección Burst)** |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Caitlyn.png" width="25"> **Caitlyn** | 🟡 MEDIO | 🔴 `  ██▆▅▄▃▂ ` | Su rango (650) bloquea libertad de salto. Abusa del passthrough a minions con Q. Full All-in al Nivel 6. | **Runaan's Hurricane** para oleadas. |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Lucian.png" width="25"> **Lucian** | 🟡 MEDIO | 🟡 ` ▃▅██▅▃ ` | Observa su E (Dash agresivo). Mueve tu salto en ángulo de 45° a su (Q). Aprovéchate de sus CDs largos en early. | **Placas Acero**. |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Samira.png" width="25"> **Samira** | 🟡 MEDIO | 🟡 `   ▃▅████ ` | Su W *Blade Whirl* borra tu E. Literalmente guárdala o perderás. Cuando usa *Inferno Trigger*, Tírale soporte. | **Guinsoo (Stack rápido de Lanzas)** |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Aphelios.png" width="25"> **Aphelios** | 🟡 MEDIO | 🟡 `  ▃▅████ ` | Tienes 30s de ventana cuando no tiene Severum/Crescendum (Armas rojas/blancas) para asediarle. | **Burst Lethality**. |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Varus.png" width="25"> **Varus** | 🟡 MEDIO | 🟡 ` ▃▄▇██▅▃ ` | Versión AP o Letalidad te hacen checkmate. Evita su flecha R o estás muerta en 0.5s sin pasiva de salto. | **Terminus (Resistencia Mágica)** |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Jinx.png" width="25"> **Jinx** | 🟢 BAJO | 🟢 ` ▂▃▅▆▇██ `(Escala fuerte) | Eres superior niveles 1 al 9. Congela oleada, la matas al mínimo avance mal posicionado que dé. | **Assassin Burst** (Elimínala rápido). |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Kaisa.png" width="25"> **Kai'Sa** | 🟢 BAJO | 🟡 ` ▂▃▅██▇▄ ` | Métete dentro de las olas de minions para que su lluvia de misiles Q no aplique isolación. Rindeas a la mínima. | **Guinsoo** |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Twitch.png" width="25"> **Twitch** | 🟢 BAJO | 🟡 ` ▂▄▆███ ` | Flanquea desde invisible. Si apretas 'Exhaust' rápido cuando aparezca, le robas todo su DPS, salta en su cara. | **Shieldbow / Escudos** |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Jhin.png" width="25"> **Jhin** | 🟢 BAJO | 🟢 ` ▃▄▆▇▅▃ ` | Su cuarto tiro es previsible y sus animaciones lentas. Saltas fuera del rango del cuarto tiro y vuelves a entrar. Checkmate. | **BotRk (Movement Steal)** |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Zeri.png" width="25"> **Zeri** | 🟢 BAJO | 🟢 ` ▂▃▄▅▇█ ` | Es una skillshot pura. Tu pasiva de estar saltando ininterrumpidamente hace que Zeri falle 50% de sus balas. | **On-Hit Armor** |
| <img src="https://ddragon.leagueoflegends.com/cdn/14.5.1/img/champion/Ezreal.png" width="25"> **Ezreal** | 🟢 BAJO | 🟢 ` ▃▅▆██▅ ` | Mismo caso. Bloquea sus (Q) con minions. Tu salto anula su precisión en fase de teamfights extendidas. | **BotRK + Berserker Rush** |

<div align="center">
  <br>
  <p><i>"Nuestra fe... nos ata." — Kalista.</i></p>
</div>