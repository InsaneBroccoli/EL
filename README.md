### Skript Kapitel 1 - Schaltverhalten einer Spule

#### Die Induktivität einer Spule

$$
\displaystyle u_L(t) = L \frac{d i(t)}{dt}
$$

#### Ausschaltvorgang bei einer stromführenden Spule

Maschensatz:
$$
\displaystyle R i_R(t) + L \frac{d i_L(t)}{dt} = 0
$$

Bauteilgleichungen:
$$
\displaystyle u_R(t) = R i_R(t) \quad \text{und} \quad u_L(t) = L \frac{d i_L(t)}{dt}
$$

#### Einschaltvorgang bei einer Spule

$$
\displaystyle u(t) = R i(t) + L \frac{d i(t)}{dt}
$$

Lösungen:
$$
\displaystyle i(t) = I_0 e^{-\frac{R}{L}t} \quad \text{und} \quad u_L(t) = L \frac{d i(t)}{dt}
$$

### Skript Kapitel 2 - Grundlagen der Wechselstromlehre

#### Harmonische Signale und Ihre Darstellung

- Summe einer komplexen Zahl mit ihrer Konjugierten:
$$
\displaystyle x + x^* = 2 \operatorname{Re}(x)
$$

- Produkt einer komplexen Zahl mit ihrer Konjugierten:
$$
\displaystyle x \cdot x^* = |x|^2
$$

- Eulersche Form der imaginären Einheit:
$$
\displaystyle i = e^{i\frac{\pi}{2}}
$$

- Eulersche Form der negativen reellen Einheit:
$$
\displaystyle -1 = e^{\pm i\pi}
$$

#### Linearer Mittelwert eines beliebigen periodischen Signals \(x(t)\)

$$
\displaystyle X_{\text{lin}} = \frac{1}{T} \int_{0}^{T} x(t) \, dt
$$

#### Quadratischer Mittelwert, Effektivwert

$$
\displaystyle X_{\text{eff}} = \sqrt{\frac{1}{T} \int_{0}^{T} x^2(t) \, dt}
$$

#### Impedanz eines Serienschwingkreises

$$
\displaystyle Z = R + j\omega L + \frac{1}{j\omega C}
$$

#### Resonanzfrequenz

$$
\displaystyle \omega_r = \frac{1}{\sqrt{LC}}
$$

#### Leistungsanpassung

Wirkleistung:
$$
\displaystyle P_{\text{max}} = \frac{U^2}{4R_Q}
$$

Blindleistung:
$$
\displaystyle Q = \frac{U^2
