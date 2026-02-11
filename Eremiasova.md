## Iracionální Rovnice

### Teorie

- Iracionální rovnice je rovnice, v níž se neznámá nachází pod odmocninou.
- Než se pustíme do samotných matematických úprav iracionální rovnice, nezapomeňme uvést podmínky
pro neznámou určit definiční obor rovnice.
- Při práci s iracionálními rovnicemi používáme často operaci umocňování. -> **Umocnění obou stran rovnice je důsledková úprava**
  - to vystihuje skutečnost, že každé řešení původní rovnice je také řešením rovnice nové, avšak obráceně to platit nemusí. Důsledkovou úpravou se žádné řešení neztratí, ale některá řešení mohou přibýt -> proto je nutnou součástí řešení těchto rovnic **ZKOUŠKA!**

### Příklady

<https://www.spszengrova.cz/wp-content/uploads/2020/04/MAT_1_Iracionalni_rovnice_MAN.pdf>
<https://is.muni.cz/do/rect/el/estud/prif/ps23/metodika_matematiky/web/pages/02_05_iracionalni_rovnice.html?lang=en>
<https://www.priklady.com/cs/index.php/rovnice-a-nerovnice/iracionalni-rovnice-a-nerovnice>

## Exponencialni Funkce

### Teorie

$$
f(x)=a^x,\quad a\in\mathbb{R},\quad a>0,\quad a\ne1
$$

#### Graf exponenciálních funkcí

<table>
  <tr>
    <td align="center">
      <img src="https://www.matweb.cz/pictures/exp1.png" width="500"><br>
      <em>a &lt; 1</em>
    </td>
    <td align="center">
      <img src="https://www.matweb.cz/pictures/exp2.png" width="500"><br>
      <em>a &gt; 1</em>
    </td>
  </tr>
</table>

#### Vlastnosti exponenciálních funkcí
 - Definiční obor je množina všech R
 - Obor hodnot je interval (0, ∞)
 - Je zdola omezená, a^x > 0. Shora neomezená.
 - Nemá maximum, ani minimum.
 - Monotonnost funkce pak záleží na hodnotě a. Pokud je a z intervalu (0, 1), pak je funkce klesající. Pokud je z intervalu (1, ∞), pak je rostoucí.

#### Posuny exponenciálních funkcí

<img width="1000" alt="{CC17D522-647E-404A-B27A-D824CF7E402E}" src="https://github.com/user-attachments/assets/abdb5469-9d08-4c21-bbb4-26dc2909bca7" />
<img width="1000" alt="{C29ACDCA-E414-4431-8A1F-E7B49E7E5FFE}" src="https://github.com/user-attachments/assets/1737542b-ef62-4163-ac33-1fcc4eb93ab3" />
<img width="1000" alt="{F1BC72BD-FF47-43C2-90D7-A3A70489088B}" src="https://github.com/user-attachments/assets/fae32f9c-aa33-4c0a-83b5-13b6121c4bca" />

## Exponencialni Rovnice

### Vzorce

$$
\begin{aligned}
a^0 &= 1, && \text{pokud } a \ne 0 \\
a^1 &= a \\
0^n &= 0, && \text{pokud } n > 0 \\
(a \cdot b)^n &= a^n \cdot b^n \\
\left(\frac{a}{b}\right)^n &= \frac{a^n}{b^n}, && \text{pokud } b \ne 0 \\
a^m \cdot a^n &= a^{m+n} \\
\frac{a^m}{a^n} &= a^{m-n}, && \text{pokud } a \ne 0 \\
(a^m)^n &= a^{m \cdot n} \\
a^{-n} &= \frac{1}{a^n}, && \text{pokud } a \ne 0 \\
\sqrt[n]{a} &= a^{\frac{1}{n}}, && \text{pokud } a \ge 0 \\
\sqrt[n]{a^m} &= a^{\frac{m}{n}}, && \text{pokud } a \ge 0 \\
\sqrt[n]{a \cdot b} &= \sqrt[n]{a}\ \cdot \sqrt[n]{b}, && \text{pokud } a \ge 0,\ b \ge 0 \\
\sqrt[n]{\frac{a}{b}} &= \frac{\sqrt[n]{a}}{\sqrt[n]{b}}, && \text{pokud } a \ge 0,\ b > 0
\end{aligned}
$$

### Počítání

1. pokud to lze tak dostat obě strany rovnice na stejný základ

$$
\begin{aligned}
2^x &= 8 \\
2^x &= 2^3 \quad &(\text{protože } 8 = 2^3) \\
x &= 3
\end{aligned}
$$

2. pokud to nelze tak musíme logaritmovat

$$
\begin{aligned}
2^x &= 7 \\
\log_2(2^x) &= \log_2 7 \\
x \cdot \log_2 2 &= \log_2 7 \\
x &= \log_2 7
\end{aligned}
$$
