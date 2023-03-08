# Borell-Brascamp-Lieb egyenlőtlenség definíciója
- $t,g,h : \Bbb{R}^n \rightarrow R_+$ integrálható
- $p \ge - \cfrac{1}{n}$
- $s \in [0,1]$
- $x,y \in \Bbb{R}^n$
$$M_s^p (a,b) = \begin{cases}
	((1-s)*a^p + s*b^{\\\ p})^{\cfrac{1}{p}} & a*b \ne 0 \\
	0& a*b = 0
\end{cases}$$
$$\int_{\Bbb{R}^n} h(x)dx \ge M_s^{\cfrac{p}{1+n*p}}\left(\int_{\Bbb{R}^n}{f(x)dx}, \int_{\Bbb{R}^n}{g(x)dx}\right)$$
$$h((1-s)*x+s*y)  \ge M_s^p(f(x),g(x))$$
