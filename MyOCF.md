# 0.前置
$ \Pi_0=On $
$ \forall\alpha\in On \forall A(\forall\beta\exists\gamma(\beta,\gamma\in A\leftrightarrow\beta\in\gamma))\leftrightarrow A \,\mathrm{aft}\,\alpha=\{\mu:\alpha\in\mu,\mu\in A\} $
$ A=(a_1,\dots,a_n)(a_i\in On,1\le i \le n) $:
- $ (n=1\rightarrow B=\Pi_{a_1})\lor(n>1\land((a_1\le a_2\rightarrow B=\Pi_{a_n}\;onto\;str((a_2,\dots,a_n)))\lor(a_1>a_2\rightarrow B=\Pi_{a_n}\cap str((a_2,\dots,a_n)))))\leftrightarrow str(A)=B $
- $ gp(A)=\begin{cases}
(a_1,\dots,a_{n-1}) & a_n\le 1\\
(a_{i+1},\dots,a_n) & \exists i(i\in\{1,\dots,n\}\land a_i < a_1\land\lnot\exists j(j\in i\land a_j < a_1))\\
(a_{2},\dots,a_n) & \lnot\exists i(i\in\{1,\dots,n\}\land a_i < a_1\land\lnot\exists j(j\in i\land a_j < a_1))
\end{cases}
$
- $ bp(A)=\begin{cases}
() & a_n\le 1\\
(a_1-1) & n \le 1\land a_1>1\\
(a_2,\dots,a_i,a_1-1) & \exists i(i\in\{1,\dots,n\}\land a_i < a_1\land\lnot\exists j(j\in i\land a_j < a_1))\\
(a_2,\dots,a_n,a_1-1) & \lnot\exists i(i\in\{1,\dots,n\}\land a_i < a_1\land\lnot\exists j(j\in i\land a_j < a_1))
\end{cases}$
$(A\;onto)^\alpha \,B=\begin{cases}
A\;onto\,(A\;onto)^\beta \,B & \alpha=\beta+1 \\
\{\mu\mid\forall\beta<\alpha,\mu\in(A\;onto)^\beta\,B\}
\end{cases}$
$ \alpha\;th\;A=\begin{cases}
sup\{\nu:\mu\;th\;A,\mu\in\alpha \} & \alpha>0\\
1 & \alpha=0
\end{cases} $

<!-- # 1.OCF(集合论)
$ C(\alpha,\beta,A,0)=\beta\,th\,A $
$ C(\alpha,\beta,A,n+1)=\{min\ (A,\mathrm{aft})^\mu\nu:\nu,\mu\in C(\alpha,\beta,A,n)\}
\cup\{\psi_\pi(\mu,A)\mid\mu\in C(\alpha,\beta,n)\cap\alpha \}
$
$ C(\alpha,\beta,A)=\bigcup_{n\in \omega} C(\alpha,\beta,A,n) $
$ \psi_\pi(\alpha,A)=min\{ \nu : \pi\cap C(\alpha,\nu,A)\subseteq\nu  \} $ -->
# 1. BOCF
$ C(\alpha,\beta,0)=\beta\cup\{ \mathrm{min}\;\Pi_i:1<i<\omega \} $
$ C(\alpha,\beta,n+1) = \{ \nu+\mu,\psi_\xi(\gamma):\gamma,\nu,\mu,\xi\in C(\alpha,\beta,n)\land\gamma\in\alpha\cap C(\gamma,\xi) \} $
$ C(\alpha,\beta)=\bigcup_{i\in \omega} C(\alpha,\beta,i) $
$ \psi_\pi(\alpha)=\begin{cases}
min \{ \nu :\nu\in (str(bp(B))\;onto\;str(gp(B)) )/ C(\alpha,\xi\;th\;A) \} & \pi=\xi+1\;th\;A\land\xi>0\land\exists B (A=str(B))\\
0 & \pi=0\\
\end{cases} $
