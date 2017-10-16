# Analyse fonctionnelle

Remarques de analyse fonctionnelle.

---
Auteurs: [André ROCHA](https://github.com/rochamatcomp), 

---

# Les espaces $\ell^{p}(n)$


#### Définition. 
Soit $1 \le p \le \infty$. L'espace $\ell^{p}(n)$ est défini comme étant l'espace $\mathbb{R}^{n}$ muni de la norme :


\begin{cases}
    ||x||_{p} = \left( \sum\limits_{i=1}^{n} |x_{i}|^{p} \right)^{1/p}, &\mbox{si} \quad 1 \le p < \infty, \\
    ||x||_{\infty} = \max\limits_{1 \le i \le n} |x_{i}|. & (p = \infty).
\end{cases}

#### Propositions à preuver.
L'espace $\ell^{p}(n)$ est un espace vectoriel normé complet (espace de Banach).

##### Remarque.
> Regarde que $\ell^{p}(n)$ est l'espace $\mathbb{R}^{n}$ muni de la norme euclidienne, la quelle est derivé de un produit intérieur.