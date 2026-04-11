## 0.反射前置
\( \omega_n=\begin{cases}
min\{ \alpha \mid \alpha \in Ord \land \Vert \alpha \Vert = \aleph_n \} & n>0 \\
1 & n=0
\end{cases}
\)
对于反射定义等全体序数在当前情况下，均指\( \in \omega_2 \)
以\(\{\alpha\mid \alpha<\omega_1\}\)作为\(\omega_1\)的基本列
\(\Pi_0=Ord\)
\(\forall a,b\in Refl_n\rightarrow a \cap b \in Refl_n\land \forall\alpha(\alpha\in Ord\land\alpha\ge n)\rightarrow \Pi_\alpha \,onto\,A , \Pi_\alpha \,onto\,B \in Refl_n\)
\( \Omega_n=\begin{cases}
n\,th\,\Pi_2 & \exists \beta (\alpha=\beta+1 ) \\
\beta \,th\,\Pi_1\,onto\,\Pi_2 & \exists \beta (\alpha=\omega*\beta )
\end{cases}
\)
\( Inc(\alpha)=\begin{cases}
Inc(\mu)+Inc(\nu) & \alpha=\mu+\nu \\
\psi_{\omega_1+Inc(\nu)}(Inc(\mu)) & \alpha=\psi_\nu(\mu)\land \nu>0 \\
n & \alpha=n\land n\in \mathbb{N_0} \\
(\omega_1+n)\,th\,A & A\in Refl_2
\end{cases}
\)
\( (A\,onto)^\alpha B=\begin{cases}
A\,onto(A\,onto)^\beta B & \alpha=\beta+1 \\
\{\beta\mid\forall\nu<\alpha,\exists\beta\in (A\,onto)^\nu B \} & cf(\alpha)=\omega \\
\{\nu\mid\forall\beta<\nu,\nu\in(A\,onto)^{\alpha[\beta]}B\} & cf(\alpha)=\omega_1
\end{cases} \)
## 2. BOCF
\( C(\alpha,\beta,0)=\Omega_\beta\cup\{\omega_1\}\cup\{\Pi_n\mid 0 < n < \omega \} \)
\( C(\alpha,\beta,n+1)=\{\nu+\mu\mid \nu,\mu\in C(\alpha,\beta,n) \}\cup
\{ \psi_\nu(\mu)\mid \nu,\mu\in C(\alpha,\beta,n)\land \mu \in C(\mu,\nu)\land ((\beta<\omega_1\land\nu\ge\omega_1\land\mu< Inc(\alpha))\lor(\mu<\alpha)) \}\cup
\{\mu\: th\: A\mid A\in Refl_2\cap C(\alpha,\beta,n)\land \mu\in C(\alpha,\beta,n)\land((\mu\ge\omega_1\land\mu< Inc(\alpha))\lor(\mu<\alpha)) \}\cup
\{(A\, onto)^\mu\: B\mid \mu\in C(\alpha,\beta,n)\land A,B\in C(\alpha,\beta,n)\land B\in Refl_2 \land((\mu\ge\omega_1\land\mu< Inc(\alpha))\lor(\mu<\alpha)) \}\cup 
C(\alpha,\beta,n) \)
\(C(\alpha,\beta)=\bigcup_{n<\omega} C(\alpha,\beta,n) \)
\( \psi_\beta(\beta)=min\{\mu\mid \mu \in Ord\land \mu \notin C(\alpha,\beta) \}  \) 

