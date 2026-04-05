## 0.反射前置
\( (a-)^{\lambda\alpha.(\alpha)}\,b=\{ \mu \mid \forall \beta <  \mu\land\mu\in(a-)^\beta\,b \} \)
\( (a-)^{\lambda\alpha(\beta+\alpha)}\,b=\{ \mu \mid \forall \nu <  \mu\land\mu\in(a-)^{\lambda\alpha(\beta+\nu)}\,b \} \)
\( (a-)^{\lambda\alpha(\beta*\alpha)}\,b=\{ \mu \mid \forall \nu <  \mu\land\mu\in(a-)^{\lambda\alpha(\beta*\nu)}\,b \} \)
\( (a-)^{\lambda\alpha(\beta^\alpha)}\,b=\{ \mu \mid \forall \nu <  \mu\land\mu\in(a-)^{\lambda\alpha(\beta^\nu)}\,b \} \)
\( (a-)^{\lambda\alpha(\alpha\,th \forall \beta \mapsto f(\beta) )}\,b=\{ \mu \mid \forall \nu <  \mu\land\mu\in(a-)^{\lambda\alpha(\nu\,th \forall \beta \mapsto f(\beta) )}\,b \} \)(ki到\(\alpha\)的\(BHO\)类似物)
## 1 BOCF
\( C^B(\alpha,\beta,0)=\Omega_\beta\cup\{\lambda\alpha.\Omega_{\alpha+\beta}\} \)
\( C^B(\alpha,\beta,n+1)=\{\nu+\mu\mid \nu,\mu\in C^B(\alpha,\beta,n) \}\cup
\{ \psi_\nu(\mu)\mid \nu,\mu\in C^B(\alpha,\beta,n)\land  \mu \in C^B(\mu,\nu)\cap\alpha \}\cup
\{\mu\: th\: a\mid a \ge \Pi_2\land a\in A(\omega)\land \mu\in C^B(\alpha,\beta,n)\cap\alpha\ \}\cup
\{(a\, onto)^\nu\: b\mid \nu\in C^B(\alpha,\beta,n)\land b\ge \Pi_2\land a,b\in A(\omega) \}\cup 
C^B(\alpha,\beta,n) \)
\(C^B(\alpha,\beta)=\bigcup_{n<\omega} C^B(\alpha,\beta,n) \)
\( \psi^B_\beta(\beta)=min\{\mu\mid \mu \in Ord\land \mu \notin C^B(\alpha,\beta) \}  \) 
\( \psi^B_{\lambda\alpha.(\alpha+\beta)}(\beta)=max\{\mu\mid\mu \in C^B(\alpha,\beta) \land\mu \notin Ord\land \mu < \lambda\alpha.\Omega_{\alpha+\beta+1} \}  \) 
## 2 WOCF
\( C^W(\alpha,\beta,0)=\Omega_\beta\cup\{\lambda\alpha.\Omega_{\alpha+\beta}\} \)
>
\( C^W(\alpha,\beta,n+1)=\{\nu+1\mid \nu\in C^W(\alpha,\beta,n) \}\cup\{ \psi_\nu(\mu)\cap\mid \nu,\mu\in C^W(\alpha,\beta,n)\land  \mu \in C^W(\mu,\nu)\cap\Omega_{max\{\beta,\nu+1\}}\cap\alpha \}\cup\{\mu\: th\: a\mid a \ge \Pi_2\land a\in A(\omega)\land \mu\in C^W(\alpha,\beta,n)\cap\alpha\ \}\cup\{\mu\: th\:(a \:onto)^\nu\:b\mid \nu\in C^W(\alpha,\beta,n)\land b\ge \Pi_2\land a,b\in A(\omega)\}\cup C^W(\alpha,\beta,n) \)
\(C^W(\alpha,\beta)=\bigcup_{n<\omega} C^W(\alpha,\beta,n) \)
\( \psi^W_\beta(\beta)=min\{\mu\mid \mu \in Ord\land \mu \notin C^W(\alpha,\beta) \}  \) 
\( \psi^W_{\lambda\alpha.(\alpha+\beta)}(\beta)=max\{\mu\mid\mu \in C^W(\alpha,\beta) \land\mu \notin Ord\land \mu < \lambda\alpha.\Omega_{\alpha+\beta+1} \}  \) 

