# Formeln aus den Dokumenten

## Skript Kapitel 1 - Schaltverhalten einer Spule

1. **Spannung über einer Spule**:
   $$\displaystyle u(t) = L \frac{di(t)}{dt}$$

2. **Ausschaltvorgang bei einer stromführenden Spule**:
   $$\displaystyle u_R(t) + u_L(t) = U_0$$
   $$\displaystyle Ri_L(t) + L \frac{di_L(t)}{dt} = U_0$$

3. **Lösung der Differentialgleichung**:
   $$\displaystyle i(t) = i_0 e^{-\frac{R}{L}t}$$
   $$\displaystyle u_L(t) = L \frac{di(t)}{dt} = -L \frac{R}{L} i_0 e^{-\frac{R}{L}t} = -R i_0 e^{-\frac{R}{L}t} = -R i(t)$$

4. **Einschaltvorgang bei einer Spule**:
   $$\displaystyle u_R(t) + u_L(t) = I_0 R$$
   $$\displaystyle i(t) = \frac{I_0}{R} (1 - e^{-\frac{R}{L}t})$$
   $$\displaystyle u_L(t) = I_0 R e^{-\frac{R}{L}t}$$

## Skript Kapitel 2 - Grundlagen der Wechselstromlehre

1. **Kapazität des Kompensationskondensators bei Resonanz**:
   $$\displaystyle C = \frac{1}{L\omega^2}$$

2. **Leistungsanpassung**:
   $$\displaystyle P_{max} = \frac{U_Q^2}{4R_Q}$$
   $$\displaystyle Q = \frac{U_Q^2}{4X_Q}$$

3. **Impedanz und Admittanz**:
   $$\displaystyle Z = R + jX$$
   $$\displaystyle Y = \frac{1}{Z} = \frac{1}{R + jX}$$

4. **Serien- und Parallelmodell**:
   $$\displaystyle Z = R_S + j\omega L_S$$
   $$\displaystyle Y = G_P + j\omega C_P$$

5. **Resonanzfrequenz eines Serieschwingkreises**:
   $$\displaystyle \omega_r = \frac{1}{\sqrt{LC}}$$

6. **Resonanztransformator**:
   $$\displaystyle \omega_r = \sqrt{\frac{1}{LC} - \frac{R^2}{L^2}}$$

7. **Momentanleistung**:
   $$\displaystyle p(t) = u(t) \cdot i(t)$$

8. **Wirkleistung**:
   $$\displaystyle P = \frac{1}{T} \int_0^T p(t) \, dt$$

9. **Blindleistung**:
   $$\displaystyle Q = U I \sin(\phi)$$

10. **Scheinleistung**:
    $$\displaystyle S = U I$$
    $$\displaystyle S = \sqrt{P^2 + Q^2}$$

11. **Leistungsfaktor**:
    $$\displaystyle \lambda = \frac{P}{S}$$
    $$\displaystyle \cos \phi = \frac{P}{S}$$

12. **Blindfaktor**:
    $$\displaystyle \sin \phi = \frac{Q}{S}$$

13. **Komplexe Scheinleistung**:
    $$\displaystyle S = P + jQ$$

## Skript Kapitel 3 - Frequenzverhalten linearer Netzwerke

1. **Frequenzgang eines RLC-Serieschwingkreises**:
   $$\displaystyle H(\omega) = \frac{R}{R + j\omega L + \frac{1}{j\omega C}}$$

2. **Normierungsfaktoren**:
   $$\displaystyle \omega_0 = \frac{1}{\sqrt{LC}}$$
   $$\displaystyle Q = \frac{1}{R} \sqrt{\frac{L}{C}}$$
   $$\displaystyle \xi = \frac{1}{2Q}$$

3. **Differentialgleichung des RLC-Kreis**:
   $$\displaystyle L \frac{d^2i}{dt^2} + R \frac{di}{dt} + \frac{i}{C} = 0$$

## Kapitel 4 - Eigenschaften realer Bauelemente

1. **Temperaturkoeffizient eines Widerstands**:
   $$\displaystyle R(\theta) = R_{20} \left(1 + \alpha_{20} (\theta - 20^\circ C)\right)$$

2. **Umrechnungsformeln für Spulenmodelle**:
   $$\displaystyle L_P = L_S (1 + Q_L^2)$$
   $$\displaystyle R_P = R_S (1 + Q_L^2)$$

3. **Impedanz einer verlustbehafteten Spule**:
   $$\displaystyle Z = R + j\omega L$$

4. **Spannungsteiler**:
   $$\displaystyle \frac{U_2}{U} = \frac{Z_2}{Z_1 + Z_2}$$

5. **Parallelschaltung von Impedanzen**:
   $$\displaystyle \frac{1}{Z} = \frac{1}{Z_1} + \frac{1}{Z_2}$$

## Kapitel 5 - Induktion und Selbstinduktion

1. **Induktionsspannung**:
   $$\displaystyle u_S(t) = \frac{d\Phi}{dt}$$

2. **Magnetische Größen**:
   $$\displaystyle B = \frac{\Phi}{A}$$
   $$\displaystyle H = \frac{B}{\mu}$$
   $$\displaystyle \mu = \mu_0 \mu_r$$

3. **Spule als passiver Zweipol**:
   $$\displaystyle \Psi(t) = L i(t)$$
   $$\displaystyle u(t) = L \frac{di(t)}{dt}$$

4. **Gespeicherte Energie in einer Spule**:
   $$\displaystyle W = \frac{1}{2} L i^2$$

5. **Koppelfaktor von Spulen**:
   $$\displaystyle M = k \sqrt{L_1 L_2}$$

## Allgemeine Formeln

1. **Komplexe Zahlen**:
   $$\displaystyle z = a + jb$$
   $$\displaystyle |z| = \sqrt{a^2 + b^2}$$
   $$\displaystyle \bar{z} = a - jb$$

2. **Eulersche Identität**:
   $$\displaystyle e^{j\theta} = \cos(\theta) + j\sin(\theta)$$

3. **Lineare Mittelwert**:
   $$\displaystyle X_{\text{lin}} = \frac{1}{T} \int_0^T x(t) \, dt$$

4. **Quadratischer Mittelwert (Effektivwert)**:
   $$\displaystyle X_{\text{eff}} = \sqrt{\frac{1}{T} \int_0^T x^2(t) \, dt}$$
