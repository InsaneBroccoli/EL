### Skript Kapitel 1 - Schaltverhalten einer Spule

#### Die Induktivität einer Spule

$$\displaystyle u_L(t) = L \frac{d i(t)}{dt}$$

#### Ausschaltvorgang bei einer stromführenden Spule

Maschensatz:
$$\displaystyle R i_R(t) + L \frac{d i_L(t)}{dt} = 0$$

Bauteilgleichungen:
$$\displaystyle u_R(t) = R i_R(t) \quad \text{und} \quad u_L(t) = L \frac{d i_L(t)}{dt}$$

#### Einschaltvorgang bei einer Spule

$$\displaystyle u(t) = R i(t) + L \frac{d i(t)}{dt}$$

Lösungen:
$$\displaystyle i(t) = I_0 e^{-\frac{R}{L}t} \quad \text{und} \quad u_L(t) = L \frac{d i(t)}{dt}$$

### Skript Kapitel 2 - Grundlagen der Wechselstromlehre

#### Harmonische Signale und Ihre Darstellung

- Summe einer komplexen Zahl mit ihrer Konjugierten:
$$\displaystyle x + x^* = 2 \Re (x)$$

- Produkt einer komplexen Zahl mit ihrer Konjugierten:
$$\displaystyle x \cdot x^* = |x|^2$$

- Eulersche Form der imaginären Einheit:
$$\displaystyle i = e^{i\frac{\pi}{2}}$$

- Eulersche Form der negativen reellen Einheit:
$$\displaystyle -1 = e^{\pm i\pi}$$

#### Linearer Mittelwert eines beliebigen periodischen Signals \(x(t)\)

$$\displaystyle X_{\text{lin}} = \frac{1}{T} \int_{0}^{T} x(t) \, dt$$

#### Quadratischer Mittelwert, Effektivwert

$$\displaystyle X_{\text{eff}} = \sqrt{\frac{1}{T} \int_{0}^{T} x^2(t) \, dt}$$

#### Impedanz eines Serienschwingkreises

$$\displaystyle Z = R + j\omega L + \frac{1}{j\omega C}$$

#### Resonanzfrequenz

$$\displaystyle \omega_r = \frac{1}{\sqrt{LC}}$$

#### Leistungsanpassung

Wirkleistung:
$$\displaystyle P_{\text{max}} = \frac{U^2}{4R_Q}$$

Blindleistung:
$$\displaystyle Q = \frac{U^2}{4X_Q}$$

#### Momentanleistung

$$\displaystyle p(t) = u(t) \cdot i(t)$$

#### Wirkleistung

$$\displaystyle P = V \cdot I \cdot \cos(\phi)$$

#### Blindleistung

$$\displaystyle Q = V \cdot I \cdot \sin(\phi)$$

#### Scheinleistung

$$\displaystyle S = V \cdot I$$

#### Berechnung der Kapazität

$$\displaystyle C = \frac{Q}{V}$$

#### Umrechnung von Serie- in Parallelmodell für einen induktiven Zweipol

$$\displaystyle Z = R_S + j\omega L_S$$

$$\displaystyle Y = \frac{1}{Z} = \frac{1}{R_S} + \frac{1}{j\omega L_S}$$

Umrechnung:
$$\displaystyle R_P = \frac{Z^2}{R_S}$$

$$\displaystyle L_P = \frac{Z^2}{\omega L_S}$$

### Kapitel 4 - Eigenschaften realer Bauelemente

#### Temperaturkoeffizient

$$\displaystyle R(\theta) = R_{20}(1 + \alpha_{20}(\theta - 20^\circ \text{C}))$$

#### Gütefaktor von Kondensatoren

$$\displaystyle Q_C = \frac{\omega C_P R_S}{1 + \omega^2 C_P^2 R_S^2}$$

#### Umrechnungsformeln für äquivalente Kondensatormodelle

$$\displaystyle C_S = \frac{C_P}{1 + \left(\frac{1}{Q_C}\right)^2}$$

$$\displaystyle R_S = \frac{R_P}{1 + \left(\frac{Q_C}{\omega R_P C_P}\right)^2}$$

$$\displaystyle C_P = \frac{C_S}{1 + \left(\frac{Q_C}{\omega R_S C_S}\right)^2}$$

$$\displaystyle R_P = R_S (1 + Q_C^2)$$

#### Frequenzabhängigkeit

Für die normierte Impedanz eines Widerstandes:
$$\displaystyle Z(f) = \frac{R}{\sqrt{1 + \left(\frac{f}{f_c}\right)^2}}$$

### Kapitel 5 - Induktion und Selbstinduktion

#### Magnetischer Fluss

$$\displaystyle \Phi = \int_{A} \vec{B} \cdot d\vec{A}$$

#### Induktionsspannung

$$\displaystyle u_S(t) = -\frac{d\Phi}{dt}$$

#### Selbstinduktionsgesetz

$$\displaystyle u_L(t) = L \frac{di(t)}{dt}$$

#### Energie in der Spule

$$\displaystyle W_L = \frac{1}{2} L i^2$$

### Kapitel 3 - Frequenzverhalten linearer Netzwerke

#### Verstärkung, Dämpfung, Differentiation, Integration

- Verstärkung:
$$\displaystyle y(t) = k x(t)$$

- Differentiation:
$$\displaystyle y(t) = \frac{d x(t)}{dt}$$

- Integration:
$$\displaystyle y(t) = \int x(t) \, dt$$

#### Frequenzgang eines RC-Glieds

Frequenzgangfunktion:
$$\displaystyle H(\omega) = \frac{U_2}{U_1} = \frac{1}{1 + j\omega RC}$$

#### Umrechnung von Serie- in Parallelmodell für eine Kapazität

$$\displaystyle Z = \frac{1}{Y} = \frac{1}{G + j\omega C}$$

$$\displaystyle G = \frac{Z^2}{R_P}$$

$$\displaystyle C = \frac{Z^2}{\omega R_P}$$
