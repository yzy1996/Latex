# 关于 Algorithm 的一些





## Package

见到过的包括：algorithm, algorithmic, algorithmicx, algorithm2e



初步认识：

- **algorithm** - float wrapper for algorithms.
- **algorithmic** - first algorithm typesetting environment.
- **algorithmicx** - second algorithm typesetting environment.
- **algpseudocode** - layout for `algorithmicx`.
- **algorithm2e** - third algorithm typesetting environment.

 

一般用法：

```latex
\usepackage{algorithm}
\usepackage{algorithmic}
```



```
\begin{algorithm}
    \caption{Algorithm caption}
    \label{alg:algorithm-label}
	\begin{algorithmic}
    	\IF{some condition is true}
        \STATE do some processing
    \ELSIF{some other condition is true}
        \STATE do some different processing
    \ELSE
        \STATE do the default actions
    \ENDIF
	\end{algorithmic}
\end{algorithm}
```

