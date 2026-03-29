## 0.反射前置
\( (a-)^{\lambda\alpha.(\alpha)}\,b=\{ \mu \mid \forall \beta <  \mu\land\mu\in(a-)^\beta\,b \} \)
\( (a-)^{\lambda\alpha(\beta+\alpha)}\,b=\{ \mu \mid \forall \nu <  \mu\land\mu\in(a-)^{\lambda\alpha(\beta+\nu)}\,b \} \)
\( (a-)^{\lambda\alpha(\beta*\alpha)}\,b=\{ \mu \mid \forall \nu <  \mu\land\mu\in(a-)^{\lambda\alpha(\beta*\nu)}\,b \} \)
\( (a-)^{\lambda\alpha(\beta^\alpha)}\,b=\{ \mu \mid \forall \nu <  \mu\land\mu\in(a-)^{\lambda\alpha(\beta^\nu)}\,b \} \)
\( (a-)^{\lambda\alpha(\alpha\,th \forall \beta \mapsto f(\beta) )}\,b=\{ \mu \mid \forall \nu <  \mu\land\mu\in(a-)^{\lambda\alpha(\nu\,th \forall \beta \mapsto f(\beta) )}\,b \} \)(可以到\(\alpha\)的\(BHO\)类似物)
# 1.反射闭包
## 1.1
\( A(0)=\{ \Pi_i \mid 0 < i < \omega \} \)
\( A(\beta+1)=\{ (a \, onto)^{\lambda\alpha.(\Omega_{\alpha+1})
} b \mid a \in A(\beta) \land b \in A(\beta) \} \cup A(\beta) \)
\( A(\beta)=\bigcup_{n<\beta} A(n) \)
## 1.2

## 2 BOCF
\( C^B(\alpha,\beta,0)=\Omega_\beta \)
\( C^B(\alpha,\beta,n+1)=\{\nu+\mu\mid \nu,\mu\in C^B(\alpha,\beta,n) \}\cup\{ \psi_\nu(\mu)\mid \nu,\mu\in C^B(\alpha,\beta,n)\land  \mu \in C^B(\mu,\nu)\cap\alpha \}\cup\{\mu\: th\: a\mid a \ge \Pi_2\land a\in A(\omega)\land \mu\in C^B(\alpha,\beta,n)\cap\alpha\ \}\cup\{\mu\: th\:c\mid \mu,\gamma\in C^B(\alpha,\beta,n)\cap\alpha\land b\ge \Pi_2\land a,b\in A(\omega)\land\nu\in B(\text{(待定)},\gamma) \}\cup C^B(\alpha,\beta,n) \)
\(C^B(\alpha,\beta)=\bigcup_{n<\omega} C^B(\alpha,\beta,n) \)
\( \psi^B_\beta(\beta)=min\{\mu\mid \mu \in Ord\land \mu \notin C^B(\alpha,\beta) \}  \) 
## 3 WOCF
\( C^W(\alpha,\beta,0)=\Omega_\beta \)
\( C^W(\alpha,\beta,n+1)=\{\nu+1\mid \nu\in C^W(\alpha,\beta,n) \}\cup\{ \psi_\nu(\mu)\cap\mid \nu,\mu\in C^W(\alpha,\beta,n)\land  \mu \in C^W(\mu,\nu)\cap\Omega_{max\{\beta,\nu+1\}}\cap\alpha \}\cup\{\mu\: th\: a\mid a \ge \Pi_2\land a\in A(\omega)\land \mu\in C^W(\alpha,\beta,n)\cap\alpha\ \}\cup\{\mu\: th\:(a \:onto)^\nu\:b\mid \mu,\gamma\in C^W(\alpha,\beta,n)\cap\alpha\land b\ge \Pi_2\land a,b\in A(\omega)\land\nu\in B^\alpha (\gamma,\gamma) \}\cup C^W(\alpha,\beta,n) \)
\(C^W(\alpha,\beta)=\bigcup_{n<\omega} C^W(\alpha,\beta,n) \)
\( \psi^W_\beta(\beta)=min\{\mu\mid \mu \in Ord\land \mu \notin C^W(\alpha,\beta) \}  \) 

