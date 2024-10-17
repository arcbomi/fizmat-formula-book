<style> 
.markdown-section { 
    padding: 0.25rem 10px;
} 
</style>
## кері функция 
$f^{-1}(f(x))=x$, $f^{-1}(x)$ функциясы $f(x)$ функциясының $\textbf{кері функциясы}$ деп аталады

## Тригонометрия
$$
\begin{align*}
\sin^{-1}(x)&=\arcsin(x) \\
\cos^{-1}(x)&=\arccos(x) \\
\tan^{-1}(x)&=\arctan(x) \\
\ctg^{-1}(x)&=\arcctg(x) \\
\end{align*}
$$

## Properties
$$
\begin{align*}
\sin(\arccos(x))&=\sqrt {1-x^2} \\
\cos(\arcsin(x))&=\sqrt {1-x^2} \\
\sin(\arctan(x))&=\frac{x}{\sqrt{1+x^2}} \\
\cos(\arctan(x))&=\frac{1}{\sqrt{1+x^2}} \\
\tan(\arcsin(x))&=\frac{x}{\sqrt{1-x^2}} \\
\tan(\arccos(x))&=\frac{\sqrt{1-x^2}}{x} \\
\ctg(\arcsin(x))&=\frac{\sqrt{1-x^2}}{x} \\
\ctg(\arccos(x))&=\frac{x}{\sqrt{1-x^2}} \\
\end{align*}
$$

## Domains
$$
\begin{align*}
\arcsin(x)&\in [-\frac{\pi}{2}; \frac{\pi}{2}], x\in[-1;1] \\
\arccos(x)& \in [0; \pi], x\in[-1;1] \\
\arctan(x)&\in (-\frac{\pi}{2}; \frac{\pi}{2}), x\in R \\
\arcctg(x)&\in (0; \pi), x\in R \\
\end{align*}
$$
## Complementary Relationship
$$
\begin{align*}
\arcsin(-x)&=-\arcsin(x) \\
\arccos(-x)&=\pi-\arccos(x) \\
\arctan(-x)&=-\arctan(x) \\
\arcctg(-x)&=\pi-\arcctg(x)\\
\end{align*}
$$
$$
\begin{align*}
\arcsin(x)&+\arccos(x)=\frac{\pi}{2} \\
\arctan(x)&+\arcctg(x)=\frac{\pi}{2} \\
\end{align*}
$$

## Equivalence of Inverse

$$
\begin{align*}
\arcsin f(x) & = \arcsin g(x) & \Leftrightarrow  
\begin{cases}
   f(x) = g(x) \\
   |f(x)| \leq 1
\end{cases} \\
& & \Leftrightarrow
\begin{cases}
   f(x) = g(x) \\
   |g(x)| \leq 1
\end{cases}\\
\arccos f(x)&=\arccos g(x) & \Leftrightarrow
\begin{equation*}
 \begin{cases}
   f(x)=g(x) \\
   |f(x)|\leq 1\\
 \end{cases}
 \end{equation*}\\
& & \Leftrightarrow
\begin{equation*}
 \begin{cases}
 f(x)=g(x) \\
 |g(x)|\leq 1\\
 \end{cases} 
\end{equation*} \\
\end{align*}
$$

$$
\arctan f(x)=\arctan g(x) \Leftrightarrow f(x)=g(x) \\
\arcctg f(x)=\arcctg g(x) \Leftrightarrow f(x)=g(x)\\
$$

$$
\begin{align*}
\arcsin f(x)&=\arccos g(x) \Rightarrow f^2(x)+g^2(x)=1 \\
\arctg f(x)&=\arcctg g(x) \Rightarrow f(x)g(x)=1 \\
\arcsin f(x)&=\arcctg g(x) \Rightarrow f^2(x)=\frac{1}{g^2(x)+1} \\
\arccos f(x)&=\arctan g(x) \Rightarrow f^2(x)=\frac{1}{g^2(x)+1} \\
\arcsin f(x)&=\arctan g(x) \Rightarrow f^2(x)=\frac{g^2(x)}{g^2(x)+1} \\
\arccos f(x)&=\arcctg g(x) \Rightarrow f^2(x)=\frac{g^2(x)}{g^2(x)+1}\\
\end{align*}
$$

## Inequalities
$$
\begin{align*}
\arcsin f(x)&\leq \arcsin g(x) \Leftrightarrow  
\begin{equation*}
 \begin{cases}
   f(x)\leq g(x) \\
   f(x)\geq -1\\
   g(x)\leq 1 
 \end{cases}
 \end{equation*} \\
\arccos f(x)&\leq \arccos g(x) \Leftrightarrow
\begin{equation*}
 \begin{cases}
   f(x)\geq g(x) \\
   f(x)\leq 1\\
   g(x)\geq -1
\end{cases}
\end{equation*} \\[3ex]
\arctan f(x)&\leq \arctan g(x) \Leftrightarrow f(x)\leq g(x) \\
\arcctg f(x)&\leq \arcctg g(x) \Leftrightarrow f(x)\geq g(x) 
\end{align*}
$$



## $f(x) = a $

$$
\begin{align*}
\sin(x)=a \\
|a|&>1 \Rightarrow x\in \varnothing \\
|a|&\leq 1\Rightarrow x=(-1)^k\arcsin(a)=\pi k, k\in Z \\
\sin(x)&=1\Rightarrow x=\frac{\pi}{2}+2\pi k, k\in Z \\
\sin(x)&=0\Rightarrow x=\pi k, k\in Z \\
\sin(x)&=-1\Rightarrow x=-\frac{\pi}{2}+2\pi k, k\in Z \\
\cos(x)=a \\
|a|&>1 \Rightarrow x\in \varnothing \\
|a|&\leq 1\Rightarrow \pm\arccos(a)+2\pi k, k\in Z \\
\cos(x)&=1\Rightarrow x=2\pi k, k\in Z \\
\cos(x)&=0\Rightarrow x=\frac{\pi}{2}+\pi k, k\in Z \\
\cos(x)&=-1 \Rightarrow x=\pi+2\pi k, k\in Z \\
\tan(x)=a\\
a&\in R\Rightarrow x=\arctan(a)+\pi k, k\in Z \\
\tan(x)&=0\Rightarrow x=\pi k, k\in Z \\
\ctg(x)=a\\
a&\in R\Rightarrow x=\arcctg(a)+\pi k, k\in Z \\
ctg(x)&=0\Rightarrow x=\frac{\pi}{2}+\pi k, k\in Z \\
\end{align*}
$$

## $f(x) > a $
$$
\begin{align*}
\sin(x)>a \\
a&\geq 1 \Rightarrow x\in \varnothing\\
a&<-1 \Rightarrow x\in R \\
-1&\leq a<1 \Rightarrow \arcsin(a) +2\pi k<x<\pi -\arcsin(a)+2\pi k, k\in Z\\
\cos(x)>a \\
a&\geq 1 \Rightarrow x\in \varnothing\\
a&<-1 \Rightarrow x\in R \\
-1&\leq a<1 \Rightarrow -\arccos(a) +2\pi k<x<\pi \arccos(a)+2\pi k, k\in Z\\
\tan(x)>a \\
a&\in R \Rightarrow \arctan(a)+\pi k<x<\frac{\pi}{2}+\pi k, k\in Z \\
\ctg(x)>a \\
a&\in R \Rightarrow \pi k<x<\arcctg(a)+\pi k, k\in Z \\
\end{align*}
$$

## $f(x) < a $
$$
\begin{align*}
\sin(x)<a \\
a&>1 \Rightarrow x\in R\\
a&\leq-1 \Rightarrow x\in \varnothing \\
-1&< a\leq1 \Rightarrow -\pi-\arcsin(a) +2\pi k<x< \arcsin(a)+2\pi k, k\in Z\\
\cos(x)<a \\
a&>1 \Rightarrow x\in R\\
a&\leq-1 \Rightarrow x\in \varnothing \\
-1&< a\leq 1 \Rightarrow \arccos(a) +2\pi k<x<2\pi- \arccos(a)+2\pi k, k\in Z\\
\tan(x)<a \\
a&\in R \Rightarrow -\frac{\pi}{2} +\pi k<x<\arctan(a)+\pi k, k\in Z \\
\ctg(x)<a \\
a&\in R \Rightarrow \arcctg(a)+\pi k<x<\pi +\pi k, k\in Z \\
\end{align*}
$$

## $f(x) \geq a $
$$
\begin{align*}
\sin(x)\geq a \\
a&>1 \Rightarrow x\in \varnothing  \\
a&\leq -1 \Rightarrow x\in R\\
-1&<a<1  \Rightarrow \arcsin(a) +2\pi k\leq x\leq \pi -\arcsin(a)+2\pi k, k\in Z\\
a&=1 \Rightarrow x=\frac{\pi}{2}+2\pi k, k \in Z \\
\cos(x)\geq a \\
a&> 1 \Rightarrow x\in \varnothing\\
a&\leq-1 \Rightarrow x\in R \\
-1&< a<1 \Rightarrow -\arccos(a) +2\pi k\leq x\leq \pi \arccos(a)+2\pi k, k\in Z\\
a&=1 \Rightarrow x=2\pi k, k\in Z \\
\tan(x)\geq a \\
a&\in R \Rightarrow \arctan(a)+\pi k\leq x \frac{\pi}{2}+\pi k, k\in Z \\
\ctg(x)\geq a \\
a&\in R \Rightarrow \pi k< x\leq \arcctg(a)+\pi k, k\in Z \\
\end{align*}
$$

## $f(x) \leq a $
$$
\begin{align*}
\sin(x)\leq a \\
a&\geq 1 \Rightarrow x\in R\\
a&<-1 \Rightarrow x\in \varnothing \\
-1&< a<1 \Rightarrow -\pi-\arcsin(a) +2\pi k\leq x\leq \arcsin(a)+2\pi k, k\in Z\\
a&=-1\Rightarrow x=-\frac{\pi}{2}+2\pi k, k\in Z \\
\cos(x)\leq a \\
a&\geq 1 \Rightarrow x\in R\\
a&<-1 \Rightarrow x\in \varnothing \\
-1&< a<1 \Rightarrow \arccos(a) +2\pi k\leq x\leq 2\pi- \arccos(a)+2\pi k, k\in Z\\
a&=1\Rightarrow x=\pi+2\pi k, k\in Z \\
\tan(x)\leq a \\
a&\in R \Rightarrow -\frac{\pi}{2} +\pi k<x\leq \arctan(a)+\pi k, k\in Z \\
\ctg(x)\leq a \\
a&\in R \Rightarrow \arcctg(a)+\pi k\leq x<\pi +\pi k, k\in Z \\
\\
\end{align*}
$$