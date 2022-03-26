### Aufbau und Ablauf
Beim elektromagentischen Schwingkreis haben wir einen ähnlichen Aufbau zum [[Entladen eines Plattenkondensators]]. Über einen Schalter $S_1$ kann umgeschaltet werden zwischen dem Zustand $A$ (Aufladen) und $E$ (Entladen). 
- Beim Aufladen lädt sich der Kondensator $C$. 
- Beim Entladen entlädt er sich über den [[Widerstand]] $R$ und die Spule $L$. 
- Da aber nun durch die Spule ein Strom fließt entsteht ein Magnet- oder b-Feld. 
- Dieses induziert dann aber im weiteren eine Spannung $U_2(t)$, die wiederrum den Kondensatur $C$ in die umgedrehte Richtung wie vorher wieder auflädt. 

=> Dieser Prozess gleicht also einer Schwingung, und kann deshalb auch wie eine Betrachtet und hergeleitet werden. 

![[Aufbau des elektromagnetischen Schwingkreises.png]]_Aufbau des elektromag. Schwingkreises_ 

### Herleitung der Schwingungsdauer
Wir betrachten zunächst einen Maschenumlauf im rechten Teil der Schaltung. Aus der [[Maschenregel]] wissen wir: $$U_C(t) + U_R(t) + U_L(t) = 0$$$U_R(t)$ betrachten wir aber nur bei über einen Widerstand gedämpften Schwingprozess, hier lassen wir es einfach weg.

Für $U_C(t)$ kennen wir $Q = C \cdot  U$, also $$U_C(t) = \frac{Q(t)}{C}$$Für $U_L(t)$ gilt die Formel $U_L = L \cdot  \frac{\Delta I}{\Delta t}$. Wir wissen: $I(t) = \dot{Q}(t)$, also gilt $$\frac{\Delta I}{\Delta t} = \dot{I}(t) = \ddot{Q}(t)$$ 

Mit beidem eingesetzt kommen wir auf $$\frac{Q(t)}{C}+L\cdot \ddot{Q} = 0$$Oder umgestellt auf $$\ddot{Q}(t) + \frac{1}{L\cdot C}\cdot Q(t) = 0$$ 
Wie auch schon bei anderen Differentialgleichungen für Schwingungen (siehe [[Schwingunsdauer eines Federpendels]] oder [[Schwingungsdauer eines Fadenpendels]]) setzen wir in diese Formel eine allgemeine Schwingunsfunktion $y(t) = \hat{y} \cdot  sin(\omega \cdot  t)$ ein. Diese müssen wir für unsere DGL erst Ableiten.$$Q(t) = Q_0 \cdot  sin(\omega \cdot  t)$$
$$\dot{Q}(t) = Q_0 \cdot  \omega \cdot  cos(\omega \cdot  t)$$
$$\ddot{Q}(t) = -Q_0 \cdot  {\omega}^² \cdot  sin(\omega \cdot  t)$$
Eingesetzt in die DGL haben wir folglich also $$-\omega^2\cdot Q_0\cdot sin(\omega\cdot t)+ \frac{1}{L\cdot C}\cdot Q_0\cdot sin(\omega\cdot t) = 0$$Im nächsten Schritt klammern wir aus:$$Q_0\cdot sin(\omega\cdot t)\cdot [~\frac{1}{L\cdot C}-\omega^2~] = 0$$Da wir für den linken Teil davon ausgehen, dass dieser nur zu wenigen Zeitpunkten 0 ist, betrachten wir stattdessen den rechten Teil des Terms. $$\frac{1}{L \cdot  C}-\omega^2 = 0$$Hiermit kommen wir auf$$\sqrt{\frac{1}{L\cdot C}} = \omega$$Für [[Omega ω]] wissen wir $\omega = \frac{2\cdot \pi}{T}$, eingesetzt kommen wir also auf $$\sqrt{\frac{1}{L\cdot C}} = \frac{2\cdot \pi}{T}$$und dann schließlich für T auf $$2\cdot \pi \cdot  \sqrt{L\cdot C} = T$$