## Туынды
$$
\begin{align*}
f^{\prime}(x)=\lim_{h\rightarrow 0}\frac{f(x+h)-f(x)}{h} \\
\end{align*}
$$
$$
\begin{align*}
(f(x)+g(x))^\prime&=f^{\prime}(x)+g^{\prime}(x) \\
(f(x)-g(x))^\prime&=f^{\prime}(x)-g^{\prime}(x)\\
(f(x)\cdot g(x))^\prime&=f^{\prime}(x)\cdot g(x)+ g^{\prime}(x)\cdot f(x) \\
(\frac{f(x)}{g(x)})^\prime&=\frac{f^{\prime}(x) g(x)-g^{\prime}(x)f(x)}{g^2(x)} \\
\end{align*}
$$
$$
\begin{align*}
c^\prime&=0, c=\text{const}\\
(cx^\alpha)^\prime&=\alpha cx^{\alpha-1}, \alpha \in R \\
(a^x)^\prime&=a^x \ln(a) \\
(\log_a(x))^\prime&=\frac{1}{x\ln(a)} \\
(\sin(x))^\prime&=\cos(x)\\
(\cos(x))^\prime&=-\sin(x) \\
(\tan(x))^\prime&=\sec^2(x) \\
(\ctg(x))^\prime&=-\csc^2(x) \\
(\arcsin(x))^\prime&=\frac{1}{\sqrt{1-x^2}} \\
(\arccos(x))^\prime&=-\frac{1}{\sqrt{1-x^2}} \\
(\arctan(x))^\prime&=\frac{1}{1+x^2} \\
(\arcctg(x))^\prime&=-\frac{1}{1+x^2} \\
(f_1(f_2(\ldots(f_n(x))))))^\prime&=f_1^\prime(f_2(\ldots(f_n(x))))\cdot f_2^\prime(f_3(\ldots(f_n(x))))\cdot\ldots\cdot f_n^\prime(x) \\
(f^{-1}(x))^\prime&=\frac{1}{f^\prime(f^{-1}(x))} \\
\end{align*}
$$

Графикке жанама $:y=f^\prime(x_0)(x-x_0)+f(x_0)$
Егер $f^\prime(x_0)=0$ болса, онда функция $x_0$ нүктесінде экстремум мәнін(минимум немесе максимум) қабылдайды


1) Егер $f(x)$ функциясы $[a,b]$ интервалында дифференциацияланатын функция болса, және $f(a)=f(b)$ болса онда $\exists x_0:f^\prime(x_0)=0 (x_0\in [a,b])$ $\textbf{(Ролль)}$
&nbsp;
2) Егер f(x) функциясы $[a,b]$ интервалында дифференциацияланатын функция болса, онда  $\exists x_0\in [a,b]:f^\prime(x_0)=\frac{f(a)-f(b)}{a-b}$ $\textbf{(Лагранж)}$
&nbsp;
3) $f(x), g(x)$ функциялары $[a,b]$ интервалында дифференфиацияланатын функциялар болсын және $g^\prime(x)\neq 0 \ \forall x\in [a,b]$; онда $\exists x_0\in[a,b]:$ $\frac{f(b)-f(a)}{g(b)-g(a)} = \frac{f^\prime(x_0)}{g^\prime(x_0)}$ $\textbf{(Коши)}$
&nbsp;
4) Егер $\lim_{x\rightarrow x_0}{f(x)}=\lim_{x\rightarrow x_0}{g(x)}=0 $ немесе $ \lim_{x\rightarrow x_0}{f(x)}=\lim_{x\rightarrow x_0}{g(x)}=\infty$ болса, онда 
$$
\lim_{x\rightarrow x_0}\frac{f(x)}{g(x)}=\lim_{x\rightarrow x_0}\frac{f^\prime(x)}{g^\prime(x)}\ \text{болады} \textbf{(Лопиталь)}
$$
