# Formeln aus den Dokumenten

## Skript Kapitel 1 - Schaltverhalten einer Spule

1. **Spannung über einer Spule**:
   $$\displaystyle u(t) = L \frac{di(t)}{dt}$$
   - \( u(t) \): Spannung über der Spule
   - \( L \): Induktivität der Spule
   - \( i(t) \): Strom durch die Spule

2. **Ausschaltvorgang bei einer stromführenden Spule**:
   $$\displaystyle u_R(t) + u_L(t) = U_0$$
   $$\displaystyle Ri_L(t) + L \frac{di_L(t)}{dt} = U_0$$
   - \( u_R(t) \): Spannung über dem Widerstand
   - \( u_L(t) \): Spannung über der Spule
   - \( U_0 \): Versorgungsspannung
   - \( R \): Widerstand
   - \( i_L(t) \): Strom durch die Spule

3. **Lösung der Differentialgleichung**:
   $$\displaystyle i(t) = i_0 e^{-\frac{R}{L}t}$$
   $$\displaystyle u_L(t) = L \frac{di(t)}{dt} = -L \frac{R}{L} i_0 e^{-\frac{R}{L}t} = -R i_0 e^{-\frac{R}{L}t} = -R i(t)$$
   - \( i(t) \): Strom durch die Spule
   - \( i_0 \): Anfangsstrom
   - \( R \): Widerstand
   - \( L \): Induktivität

4. **Einschaltvorgang bei einer Spule**:
   $$\displaystyle u_R(t) + u_L(t) = I_0 R$$
   $$\displaystyle i(t) = \frac{I_0}{R} (1 - e^{-\frac{R}{L}t})$$
   $$\displaystyle u_L(t) = I_0 R e^{-\frac{R}{L}t}$$
   - \( u_R(t) \): Spannung über dem Widerstand
   - \( u_L(t) \): Spannung über der Spule
   - \( I_0 \): Anfangsstrom
   - \( R \): Widerstand
   - \( L \): Induktivität
   - \( i(t) \): Strom durch die Spule

5. **Induktivität einer Spule**:
   $$\displaystyle u_L(t) = L \frac{d i(t)}{dt}$$
   - \( u_L(t) \): Spannung über der Spule
   - \( L \): Induktivität der Spule
   - \( i(t) \): Strom durch die Spule

6. **Maschensatz**:
   $$\displaystyle R i_R(t) + L \frac{d i_L(t)}{dt} = 0$$
   - \( R \): Widerstand
   - \( i_R(t) \): Strom durch den Widerstand
   - \( L \): Induktivität
   - \( i_L(t) \): Strom durch die Spule

## Skript Kapitel 2 - Grundlagen der Wechselstromlehre

1. **Kapazität des Kompensationskondensators bei Resonanz**:
   $$\displaystyle C = \frac{1}{L\omega^2}$$
   - \( C \): Kapazität
   - \( L \): Induktivität
   - \( \omega \): Winkelgeschwindigkeit

2. **Leistungsanpassung**:
   $$\displaystyle P_{max} = \frac{U_Q^2}{4R_Q}$$
   $$\displaystyle Q = \frac{U_Q^2}{4X_Q}$$
   - \( P_{max} \): Maximale Leistung
   - \( U_Q \): Spannung
   - \( R_Q \): Widerstand
   - \( Q \): Blindleistung
   - \( X_Q \): Reaktanz

3. **Impedanz und Admittanz**:
   $$\displaystyle Z = R + jX$$
   $$\displaystyle Y = \frac{1}{Z} = \frac{1}{R + jX}$$
   - \( Z \): Impedanz
   - \( R \): Widerstand
   - \( X \): Reaktanz
   - \( Y \): Admittanz

4. **Serien- und Parallelmodell**:
   $$\displaystyle Z = R_S + j\omega L_S$$
   $$\displaystyle Y = G_P + j\omega C_P$$
   - \( Z \): Impedanz
   - \( R_S \): Serienwiderstand
   - \( \omega \): Winkelgeschwindigkeit
   - \( L_S \): Serieninduktivität
   - \( Y \): Admittanz
   - \( G_P \): Parallelleitwert
   - \( C_P \): Parallelkapazität

5. **Resonanzfrequenz eines Serieschwingkreises**:
   $$\displaystyle \omega_r = \frac{1}{\sqrt{LC}}$$
   - \( \omega_r \): Resonanzfrequenz
   - \( L \): Induktivität
   - \( C \): Kapazität

6. **Resonanztransformator**:
   $$\displaystyle \omega_r = \sqrt{\frac{1}{LC} - \frac{R^2}{L^2}}$$
   - \( \omega_r \): Resonanzfrequenz
   - \( L \): Induktivität
   - \( C \): Kapazität
   - \( R \): Widerstand

7. **Momentanleistung**:
   $$\displaystyle p(t) = u(t) \cdot i(t)$$
   - \( p(t) \): Momentanleistung
   - \( u(t) \): Spannung
   - \( i(t) \): Strom

8. **Wirkleistung**:
   $$\displaystyle P = \frac{1}{T} \int_0^T p(t) \, dt$$
   - \( P \): Wirkleistung
   - \( T \): Periode
   - \( p(t) \): Momentanleistung

9. **Blindleistung**:
   $$\displaystyle Q = U I \sin(\phi)$$
   - \( Q \): Blindleistung
   - \( U \): Spannung
   - \( I \): Strom
   - \( \phi \): Phasenwinkel

10. **Scheinleistung**:
    $$\displaystyle S = U I$$
    $$\displaystyle S = \sqrt{P^2 + Q^2}$$
    - \( S \): Scheinleistung
    - \( U \): Spannung
    - \( I \): Strom
    - \( P \): Wirkleistung
    - \( Q \): Blindleistung

11. **Leistungsfaktor**:
    $$\displaystyle \lambda = \frac{P}{S}$$
    $$\displaystyle \cos \phi = \frac{P}{S}$$
    - \( \lambda \): Leistungsfaktor
    - \( P \): Wirkleistung
    - \( S \): Scheinleistung
    - \( \phi \): Phasenwinkel

12. **Blindfaktor**:
    $$\displaystyle \sin \phi = \frac{Q}{S}$$
    - \( Q \): Blindleistung
    - \( S \): Scheinleistung
    - \( \phi \): Phasenwinkel

13. **Komplexe Scheinleistung**:
    $$\displaystyle S = P + jQ$$
    - \( S \): Scheinleistung
    - \( P \): Wirkleistung
    - \( Q \): Blindleistung

14. **Quadratischer Mittelwert, Effektivwert**:
    $$\displaystyle X_{\text{eff}} = \sqrt{\frac{1}{T} \int_{0}^{T} x^2(t) \, dt}$$
    - \( X_{\text{eff}} \): Effektivwert
    - \( T \): Periode
    - \( x(t) \): Zeitabhängige Funktion

15. **Linearer Mittelwert eines beliebigen periodischen Signals \(x(t)\)**:
    $$\displaystyle X_{\text{lin}} = \frac{1}{T} \int_{0}^{T} x(t) \, dt$$
    - \( X_{\text{lin}} \): Linearer Mittelwert
    - \( T \): Periode
    - \( x(t) \): Zeitabhängige Funktion

16. **Summe einer komplexen Zahl mit ihrer Konjugierten**:
    $$\displaystyle x + x^* = 2 \text{Re}(x)$$
    - \( x \): Komplexe Zahl
    - \( x^* \): Konjugiert-komplexe Zahl

17. **Produkt einer komplexen Zahl mit ihrer Konjugierten**:
    $$\displaystyle x \cdot x^* = |x|^2$$
    - \( x \): Komplexe Zahl
    - \( x^* \): Konjugiert-komplexe Zahl
    - \( |x| \): Betrag der komplexen Zahl

18. **Eulersche Form der imaginären Einheit**:
    $$\displaystyle i = e^{i\frac{\pi}{2}}$$
    - \( i \): Imaginäre Einheit
    - \( \pi \): Kreiszahl

19. **Eulersche Form der negativen reellen Einheit**:
    $$\displaystyle -1 = e^{\pm i\pi}$$
    - \( \pi \): Kreiszahl

20. **Impedanz eines Serienschwingkreises**:
    $$\displaystyle Z = R + j\omega L + \frac{1}{j\omega C}$$
    - \( Z \): Impedanz
    - \( R \): Widerstand
    - \( \omega \): Winkelgeschwindigkeit
    - \( L \): Induktivität
    - \( C \): Kapazität

## Skript Kapitel 3 - Frequenzverhalten linearer Netzwerke

1. **Frequenzgang eines RLC-Serieschwingkreises**:
   $$\displaystyle H(\omega) = \frac{R}{R + j\omega L + \frac{1}{j\omega C}}$$
   - \( H(\omega) \): Frequenzgang
   - \( R \): Widerstand
   - \( \omega \): Winkelgeschwindigkeit
   - \( L \): Induktivität
   - \( C \): Kapazität

2. **Normierungsfaktoren**:
   $$\displaystyle \omega_0 = \frac{1}{\sqrt{LC}}$$
   $$\displaystyle Q = \frac{1}{R} \sqrt{\frac{L}{C}}$$
   $$\displaystyle \xi = \frac{1}{2Q}$$
   - \( \omega_0 \): Eigenfrequenz
   - \( Q \): Gütefaktor
   - \( R \): Widerstand
   - \( L \): Induktivität
   - \( C \): Kapazität
   - \( \xi \): Dämpfungsfaktor

3. **Differentialgleichung des RLC-Kreis**:
   $$\displaystyle L \frac{d^2i}{dt^2} + R \frac{di}{dt} + \frac{i}{C} = 0$$
   - \( L \): Induktivität
   - \( R \): Widerstand
   - \( C \): Kapazität
   - \( i \): Strom

4. **Verstärkung, Dämpfung, Differentiation, Integration**:

   - Verstärkung:
   $$\displaystyle y(t) = k x(t)$$
   - \( y(t) \): Ausgangssignal
   - \( x(t) \): Eingangssignal
   - \( k \): Verstärkungsfaktor

   - Differentiation:
   $$\displaystyle y(t) = \frac{d x(t)}{dt}$$
   - \( y(t) \): Ausgangssignal
   - \( x(t) \): Eingangssignal

   - Integration:
   $$\displaystyle y(t) = \int x(t) \, dt$$
   - \( y(t) \): Ausgangssignal
   - \( x(t) \): Eingangssignal

5. **Frequenzgang eines RC-Glieds**:
   $$\displaystyle H(\omega) = \frac{U_2}{U_1} = \frac{1}{1 + j\omega RC}$$
   - \( H(\omega) \): Frequenzgang
   - \( U_1 \): Eingangsspannung
   - \( U_2 \): Ausgangsspannung
   - \( \omega \): Winkelgeschwindigkeit
   - \( R \): Widerstand
   - \( C \): Kapazität

6. **Umrechnung von Serie- in Parallelmodell für eine Kapazität**:
   $$\displaystyle Z = \frac{1}{Y} = \frac{1}{G + j\omega C}$$
   - \( Z \): Impedanz
   - \( Y \): Admittanz
   - \( G \): Leitwert
   - \( \omega \): Winkelgeschwindigkeit
   - \( C \): Kapazität

   Umrechnung:
   $$\displaystyle G = \frac{Z^2}{R_P}$$
   $$\displaystyle C = \frac{Z^2}{\omega R_P}$$
   - \( G \): Leitwert
   - \( Z \): Impedanz
   - \( R_P \): Parallelwiderstand
   - \( \omega \): Winkelgeschwindigkeit
   - \( C \): Kapazität

## Kapitel 4 - Eigenschaften realer Bauelemente

1. **Temperaturkoeffizient eines Widerstands**:
   $$\displaystyle R(\theta) = R_{20} \left(1 + \alpha_{20} (\theta - 20^\circ C)\right)$$
   - \( R(\theta) \): Widerstand bei Temperatur \(\theta\)
   - \( R_{20} \): Widerstand bei 20°C
   - \( \alpha_{20} \): Temperaturkoeffizient

2. **Umrechnungsformeln für Spulenmodelle**:
   $$\displaystyle L_P = L_S (1 + Q_L^2)$$
   $$\displaystyle R_P = R_S (1 + Q_L^2)$$
   - \( L_P \): Parallelinduktivität
   - \( L_S \): Serieninduktivität
   - \( Q_L \): Gütefaktor der Induktivität
   - \( R_P \): Parallelwiderstand
   - \( R_S \): Serienwiderstand

3. **Impedanz einer verlustbehafteten Spule**:
   $$\displaystyle Z = R + j\omega L$$
   - \( Z \): Impedanz
   - \( R \): Widerstand
   - \( \omega \): Winkelgeschwindigkeit
   - \( L \): Induktivität

4. **Spannungsteiler**:
   $$\displaystyle \frac{U_2}{U} = \frac{Z_2}{Z_1 + Z_2}$$
   - \( U \): Gesamtspannung
   - \( U_2 \): Spannung über \(Z_2\)
   - \( Z_1 \): Impedanz des ersten Elements
   - \( Z_2 \): Impedanz des zweiten Elements

5. **Parallelschaltung von Impedanzen**:
   $$\displaystyle \frac{1}{Z} = \frac{1}{Z_1} + \frac{1}{Z_2}$$
   - \( Z \): Gesamtimpedanz
   - \( Z_1 \): Impedanz des ersten Elements
   - \( Z_2 \): Impedanz des zweiten Elements

6. **Gütefaktor von Kondensatoren**:
   $$\displaystyle Q_C = \frac{\omega C_P R_S}{1 + \omega^2 C_P^2 R_S^2}$$
   - \( Q_C \): Gütefaktor des Kondensators
   - \( \omega \): Winkelgeschwindigkeit
   - \( C_P \): Parallelkapazität
   - \( R_S \): Serienwiderstand

7. **Umrechnungsformeln für äquivalente Kondensatormodelle**:
   $$\displaystyle C_S = \frac{C_P}{1 + \left(\frac{1}{Q_C}\right)^2}$$
   $$\displaystyle R_S = \frac{R_P}{1 + \left(\frac{Q_C}{\omega R_P C_P}\right)^2}$$
   $$\displaystyle C_P = \frac{C_S}{1 + \left(\frac{Q_C}{\omega R_S C_S}\right)^2}$$
   $$\displaystyle R_P = R_S (1 + Q_C^2)$$
   - \( C_S \): Serienkapazität
   - \( C_P \): Parallelkapazität
   - \( Q_C \): Gütefaktor des Kondensators
   - \( R_S \): Serienwiderstand
   - \( R_P \): Parallelwiderstand

8. **Frequenzabhängigkeit**:
   $$\displaystyle Z(f) = \frac{R}{\sqrt{1 + \left(\frac{f}{f_c}\right)^2}}$$
   - \( Z(f) \): Impedanz bei Frequenz \(f\)
   - \( R \): Widerstand
   - \( f \): Frequenz
   - \( f_c \): Grenzfrequenz

## Kapitel 5 - Induktion und Selbstinduktion

1. **Induktionsspannung**:
   $$\displaystyle u_S(t) = \frac{d\Phi}{dt}$$
   - \( u_S(t) \): Induktionsspannung
   - \( \Phi \): Magnetischer Fluss

2. **Magnetische Größen**:
   $$\displaystyle B = \frac{\Phi}{A}$$
   $$\displaystyle H = \frac{B}{\mu}$$
   $$\displaystyle \mu = \mu_0 \mu_r$$
   - \( B \): Magnetische Flussdichte
   - \( \Phi \): Magnetischer Fluss
   - \( A \): Fläche
   - \( H \): Magnetische Feldstärke
   - \( \mu \): Permeabilität
   - \( \mu_0 \): Permeabilität des Vakuums
   - \( \mu_r \): Relative Permeabilität

3. **Spule als passiver Zweipol**:
   $$\displaystyle \Psi(t) = L i(t)$$
   $$\displaystyle u(t) = L \frac{di(t)}{dt}$$
   - \( \Psi(t) \): Verketteter Fluss
   - \( L \): Induktivität
   - \( i(t) \): Strom
   - \( u(t) \): Spannung

4. **Gespeicherte Energie in einer Spule**:
   $$\displaystyle W = \frac{1}{2} L i^2$$
   - \( W \): Gespeicherte Energie
   - \( L \): Induktivität
   - \( i \): Strom

5. **Koppelfaktor von Spulen**:
   $$\displaystyle M = k \sqrt{L_1 L_2}$$
   - \( M \): Koppelfaktor
   - \( k \): Kopplungskoeffizient
   - \( L_1 \): Induktivität der ersten Spule
   - \( L_2 \): Induktivität der zweiten Spule

## Allgemeine Formeln

1. **Komplexe Zahlen**:
   $$\displaystyle z = a + jb$$
   $$\displaystyle |z| = \sqrt{a^2 + b^2}$$
   $$\displaystyle \bar{z} = a - jb$$
   - \( z \): Komplexe Zahl
   - \( a \): Realteil
   - \( jb \): Imaginärteil
   - \( |z| \): Betrag der komplexen Zahl
   - \( \bar{z} \): Konjugiert-komplexe Zahl

2. **Eulersche Identität**:
   $$\displaystyle e^{j\theta} = \cos(\theta) + j\sin(\theta)$$
   - \( e \): Eulersche Zahl
   - \( j \): Imaginäre Einheit
   - \( \theta \): Winkel

3. **Lineare Mittelwert**:
   $$\displaystyle X_{\text{lin}} = \frac{1}{T} \int_0^T x(t) \, dt$$
   - \( X_{\text{lin}} \): Linearer Mittelwert
   - \( T \): Periode
   - \( x(t) \): Zeitabhängige Funktion
