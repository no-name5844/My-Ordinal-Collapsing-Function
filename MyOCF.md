# 1.反射闭包
## 1.1
\( A(0)=\{ \Pi_i \mid 0 < i < \omega \} \)
\( A(\beta+1)=\{ (a-)^{\Omega_{\alpha+1}} b \mid a \in A(n) \land b \in A(n) \} \cup A(\beta) \)
\( A(\beta)=\bigcup_{n<\beta} A(n) \)
## 1.2

\( B^\alpha(\beta,\eta,0)=0 \)
\( B^\alpha(\beta,\eta,n+1)=\{f_1(\nu+1,\eta),\psi^\alpha(\gamma) \mid \nu,\gamma \in B^\alpha(\beta,\eta,n)\land \gamma\in \beta\land \gamma\in C(\beta,0) \}\cup B^\alpha(\beta,\eta,n) \)
\( B^\alpha(\beta)=\bigcup_{n\le\eta} B^\alpha(n) \)
\(f_1(\beta,\eta)\)=\(\begin{cases}
  \alpha  & \beta\in\mathbb{N} \land \beta\ge\eta \\
  \beta & \beta\in\mathbb{N} \land \beta<\eta \ \\ 
  f(f_1(\gamma,\eta)) & \exists \gamma \exists  f(f(\gamma)=\beta)
  \end{cases}\) 
\( \psi^\alpha(\beta)=max(B^\alpha(\beta)) \)
## 2 BOCF
\( C^B(\alpha,\beta,0)=\Omega_\beta \)
\( C^B(\alpha,\beta,n+1)=\{\nu+\mu\mid \nu,\mu\in C^B(\alpha,\beta,n) \}\cup\{ \psi_\nu(\mu)\mid \nu,\mu\in C^B(\alpha,\beta,n)\land  \mu \in C^B(\mu,\nu)\cap\alpha \}\cup\{\mu\: th\: a\mid a \ge \Pi_2\land a\in A(\omega)\land \mu\in C^B(\alpha,\beta,n)\cap\alpha\ \}\cup\{\mu\: th\:(a \:onto)^\nu\:b\mid \mu,\gamma\in C^B(\alpha,\beta,n)\cap\alpha\land b\ge \Pi_2\land a,b\in A(\omega)\land\nu\in B^\alpha (\text{(待定)},\gamma) \}\cup C^B(\alpha,\beta,n) \)
\(C^B(\alpha,\beta)=\bigcup_{n<\omega} C^B(\alpha,\beta,n) \)
\( \psi^B_\beta(\beta)=min\{\mu\mid \mu \in Ord\land \mu \notin C^B(\alpha,\beta) \}  \) 
## 3 WOCF
\( C^W(\alpha,\beta,0)=\Omega_\beta \)
\( C^W(\alpha,\beta,n+1)=\{\nu+1\mid \nu\in C^W(\alpha,\beta,n) \}\cup\{ \psi_\nu(\mu)\cap\mid \nu,\mu\in C^W(\alpha,\beta,n)\land  \mu \in C^W(\mu,\nu)\cap\Omega_{max\{\beta,\nu+1\}}\cap\alpha \}\cup\{\mu\: th\: a\mid a \ge \Pi_2\land a\in A(\omega)\land \mu\in C^W(\alpha,\beta,n)\cap\alpha\ \}\cup\{\mu\: th\:(a \:onto)^\nu\:b\mid \mu,\gamma\in C^W(\alpha,\beta,n)\cap\alpha\land b\ge \Pi_2\land a,b\in A(\omega)\land\nu\in B^\alpha (\gamma,\gamma) \}\cup C^W(\alpha,\beta,n) \)
\(C^W(\alpha,\beta)=\bigcup_{n<\omega} C^W(\alpha,\beta,n) \)
\( \psi^W_\beta(\beta)=min\{\mu\mid \mu \in Ord\land \mu \notin C^W(\alpha,\beta) \}  \) 

