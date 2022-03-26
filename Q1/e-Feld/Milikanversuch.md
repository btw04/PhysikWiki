## Milikanversuch
#OneNote: [Millikanversuch](https://onedrive.live.com/view.aspx?resid=63471C1A420E058F%2135717&id=documents&wd=target%28Physik%2FQ1-2%2Fe-Feld.one%7CFD2FF94F-AEFD-47C3-9B01-19B7DF694908%2FMillikanversuch%7C05054B05-9F07-4ACB-9C33-8CBB8BD6D1B0%2F%29)

Bestimmung der [[Ladung Q]] von Öltröpfchen

### Aufbau des Schwebeversuchs
![[Millikanversuch Aufbau.png]]_Aufbau des Millikanversuches_

Zwischen zwei Platten eines [[Plattenkondensator]] entsteht ein [[Homogenes Feld|homogenes]] Feld. Durch eine Zersträubung entstehen kleine Öltröpfchen, die eine gewisse, uns unbekannte, negative Ladung haben. Das elektrische Feld wirkt auf diese mit einer nach oben gerichteten [[Kraft]]. Nun kann die Feldstärke genau so eingestellt werden, dass die [[Elektrische Kraft#Formel|elektrische Kraft]] und die immer wirkende [[Auftriebskraft]] die auf das Tröpfchen wirkende Gewichtskraft ausgleicht.

#### Herleitung des Schwebeversuchs

![[Kräftegleichgewicht Millikan.png]]_Kräftegleichgewicht beim Millikanversuch_

Es gilt das Kräftegleichgewicht $F_{Gegen} = F_{G}$, gesucht ist $F_{el}$, diese ist Bestandteil der Gegenkraft, $F_{el} + F_A = F_{Gegen}$ dies entspricht $$F_{el} = F_A - F_{Gegen}$$

Für die Auftriebskraft $F_A$ wird folgendes eingesetzt:
        
$$F_A = m * g \quad \text{ || } m = \rho * V$$
$$F_A = \rho * V * g \quad \text{ || } V = \frac{4}{3}\pi * r^3$$
        
$$F_A = \rho * \frac{4}{3}\pi * r^3 * g$$
        
Und für die Gewichtskraft $F_G$ wird folgendes eingesetzt:
        
$$
        F_G = m * g = \rho_{Öl} * \frac{4}{3}\pi * r^3 * g
        $$
        
Beide Formeln werden eingesetzt und der Term vereinfacht:
        
$$
        F_{G'} = \rho_{Öl} * \frac{4}{3}\pi * r^3 * g - \rho_L * \frac{4}{3}\pi * r^3 * g
        $$
        
$$
        F_{G'} = (\rho_{Öl} - \rho_L) * \frac{4}{3}\pi * r^3 * g
        $$
        
$$
        F_{G'} = \rho{'}_ * \frac{4}{3}\pi * r^3 * g
        $$

Diese Kraft kann nun der elektrischen Kraft gleichgesetz werden
$$
        F_{el} = F_{G'}
        $$

Für das vom [[Plattenkondensator]] erzeugte elektrische Feld gilt $E = \frac{U}{d}$, wobei $U$ die Spannung und $d$ der Plattenabstand ist
$$
        q * E = \rho_{'} * \frac{4}{3}\pi * r^3 * g \quad \text{ || } E = \frac{U}{d}
        $$
$$
        q * \frac{U}{d} = \rho_{'} * \frac{4}{3}\pi * r^3 * g \quad \text{ || } * \frac{d}{U}
        $$
        
$$
        q = \frac{\rho_{'} * 4 * \pi * r^3 * g * d}{3 * U}
        $$

### Schwebe-Fall-Methode
Der einzige fehlende Bestandteil unserer Formel ist nun der Radius $r$, welcher sich nicht aus der Schwebemethode berechnen lässt. Hierfür kommt nun die sogenannte _Schwebe-Fall-Methode_ zum Einsatz, bei welcher das Öltröpfchen im freien Fall beobachtet wird.

#### Herleitung der Schwebe-Fall-Methode
![[Schwebe-Fall-Methode.png]]_Beobachtung des Tröpfchens beim Fallen_

Die Stokes’sche Reibungskraft $F_{stokes}$ wird mit der Gegenkraft $F_{G'}$ gleichgesetzt und nach dem Radius r umgestellt:
        
$$
        6 * \pi * \eta * r * v = \rho_{'} * \frac{4}{3}\pi * r^3 *g \quad \text{ || } : r
        $$
        
$$
        6 * \pi * \eta * v = \rho_{'} * \frac{4}{3}\pi * r^2 *g \quad \text{ || } * \frac{3}{4 * \rho_{'} * \pi * g}
        $$
        
$$
        \frac{18\pi * \eta * v}{4 * \rho_{'} * \pi * g} = r^2 \quad \text{ || } \sqrt{r^2}
        $$
        
$$
        \sqrt\frac{9 * \eta * v}{2 * \rho_{'} * g} = r \quad \text{ || } [\eta] = (\frac{N * s}{m^2})
        $$
        
Die hergeleitete Formel für den Radius r wird in die Formel für die Ladungsmenge q eingesetzt:

  
$$
        q = \frac{\rho_{'} * 4 * \pi * r^3 * g * d}{3 * U} \quad \text{ || } r = \sqrt\frac{9 * \eta * v}{2 * \rho_{'} * g}
        $$
Hier wird jetzt sehr viel Umstellung gemacht, die wir uns auch manchmal sparen können, aber damit es einfach nur schön aussieht, machen wir es trotzdem
$$
        q = \frac{\rho_{'} * 4 * \pi * g * d}{3 * U} * (\sqrt\frac{9 * \eta * v}{2 * \rho_{'} * g})^3 \quad \text{ || } (^n\sqrt a)^m = n\sqrt a^m
        $$
        
$$
        q = \frac{\rho_{'} * 4 * \pi * g * d}{3 * U} * \sqrt\frac{9^3 * \eta^3 * v^3}{2^3 * \rho_{'}^3 * g^3}
        $$
        
$$
        q = \frac{\rho_{'} * 4 * \pi * g * d}{3 * U} * \sqrt\frac{9^3 * \eta^3 * v^3}{2^3 * \rho_{'}^3 * g^3}
        $$
        
Anhand dieses Potenzgesetzes...
        
$$
        (^n\sqrt a)^m = n\sqrt a^m
        $$
        
$$
        \sqrt{x^3} = \sqrt{x^2 * x} = \sqrt{x^2} * \sqrt{x} = x * \sqrt{x}
        $$
        
können wir sagen, dass:
        
$$
        q = \frac{\rho_{'} * 4 * \pi * g * d}{3 * U} * \frac{9}{2 * \rho_{'} * g} * \sqrt\frac{9 * \eta^3 * v^3}{2 * \rho_{'} * g} \quad \text{ || } \sqrt{9} = 3
        $$
        
$$
        q = \frac{4 * 9 * \pi * d}{3 * 2 * U} * 3 * \sqrt\frac{\eta^3 * v^3}{2 * \rho_{'} * g}
        $$
        
$$
        q = \frac{4 * 9 * \pi * d}{2 * U} * \sqrt\frac{\eta^3 * v^3}{2 * \rho_{'} * g} \quad \text{ || } \frac{1}{\sqrt{2}} * 1 = \frac{1}{\sqrt{2}} * \frac{\sqrt{2}}{\sqrt{2}} = \frac{\sqrt{2}}{2}
        $$
        
$$
        q = \frac{4 * 9 * \pi * d}{2 * U} * \frac{\sqrt{2}}{2} * \sqrt\frac{\eta^3 * v^3}{2 * \rho_{'} * g}
        $$
        
$$
        q = \frac{4 * 9 * \pi * d * \sqrt{2}}{4 * U}  * \sqrt\frac{\eta^3 * v^3}{2 * \rho_{'} * g} 
        $$
        
$$
        q = \frac{9 * \pi * d * \sqrt{2}}{U}  * \sqrt\frac{\eta^3 * v^3}{2 * \rho_{'} * g} 
        $$
        
    