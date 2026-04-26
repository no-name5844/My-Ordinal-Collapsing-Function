# 0.前置
$ \forall\alpha\in On \forall A(\forall\beta\exists\gamma(\beta,\gamma\in A\leftrightarrow\beta\in\gamma))\leftrightarrow A \,\mathrm{aft}\,\alpha=\{\mu:\alpha\in\mu,\mu\in A\} $
$ A=(a_1,\dots,a_n)(a_i\in On,1\le i \le n) $:
- $ (n=1\rightarrow B=\Pi_{a_1})\lor(n>1\land((a_1\le a_2\rightarrow B=\Pi_{a_n}\;onto\;seqturnrefl((a_2,\dots,a_n)))\lor(a_1>a_2\rightarrow B=\Pi_{a_n}\cap seqturnrefl((a_2,\dots,a_n)))))\leftrightarrow seqturnrefl(A)=B $
- $ gp(A)=\begin{cases}
(0) & n \le 1\\
(a_{i+1},\dots,a_n) & \exists i(i\in\{1,\dots,n\}\land a_i < a_1\land\lnot\exists j(j\in i\land a_j < a_1))\\
(a_{2},\dots,a_n) & \lnot\exists i(i\in\{1,\dots,n\}\land a_i < a_1\land\lnot\exists j(j\in i\land a_j < a_1))
\end{cases}
$
- $ bp(A)=\begin{cases}
(a_1-1) & n \le 1\\
(a_2,\dots,a_i,a_1-1) & \exists i(i\in\{1,\dots,n\}\land a_i < a_1\land\lnot\exists j(j\in i\land a_j < a_1))\\
(a_2,\dots,a_n,a_1-1) & \lnot\exists i(i\in\{1,\dots,n\}\land a_i < a_1\land\lnot\exists j(j\in i\land a_j < a_1))
\end{cases}$
$(A\;onto)^\alpha \,B=\begin{cases}
A\;onto\,(A\;onto)^\beta \,B & \alpha=\beta+1 \\
\{\mu\mid\forall\beta<\alpha,\mu\in(A\;onto)^\beta\,B\}
\end{cases}$
<!-- # 1.OCF(集合论)
$ C(\alpha,\beta,A,0)=\beta\,th\,A $
$ C(\alpha,\beta,A,n+1)=\{min\ (A,\mathrm{aft})^\mu\nu:\nu,\mu\in C(\alpha,\beta,A,n)\}
\cup\{\psi_\pi(\mu,A)\mid\mu\in C(\alpha,\beta,n)\cap\alpha \}
$
$ C(\alpha,\beta,A)=\bigcup_{n\in \omega} C(\alpha,\beta,A,n) $
$ \psi_\pi(\alpha,A)=min\{ \nu : \pi\cap C(\alpha,\nu,A)\subseteq\nu  \} $ -->
# 1. MOCF
$ C(\alpha,\beta,0)=\beta $
$ C(\alpha,\beta,n+1) = \{ \nu+\mu,\nu*\mu,\nu^\mu,\psi_\xi(\gamma),\Omega_\nu,\Iota_\nu:\gamma,\nu,\mu,\xi\in C(\alpha,\beta,n)\land\gamma\in\alpha\cap C(\gamma,\xi) \} $
$ C(\alpha,\beta)=\bigcup_{i\in \omega} C(\alpha,\beta,i) $
$ \psi_\pi(\alpha)=min \{ \nu : \pi\cap C(\alpha,\nu)\subseteq\nu \} $
