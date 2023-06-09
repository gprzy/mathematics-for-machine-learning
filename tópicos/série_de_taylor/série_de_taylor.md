# Séries de Taylor

De maneira geral, a série de Taylor pode ser expressa como

$$f(x) = a_0 + a_1x^1 + a_2x^2 + \dots a_nx^n$$
$$f(x) = \sum_{n=0}^{\infty}a_nx^n$$

Agora vamos detalhar a série, acrescentando os termos $a_n$

$$f(x) = \frac{f(a)}{0!}(x - a)^0 + \frac{f'(a)}{1!} (x - a)^1 + \frac{f''(a)}{2!} (x - a)^2 + \dots + \frac{f^n(a)}{n!} (x - a)^n$$

$$f(x) = f(a) + \frac{f'(a)}{1!} (x - a)^1 + \frac{f''(a)}{2!} (x - a)^2 + \dots + \frac{f^n(a)}{n!} (x - a)^n$$

Ou então, resumidamente

$$f(x) = \sum_{n=0}^{\infty}\frac{f^n(a)}{n!} (x - a)^n$$

## Expanção de $e^x$

$$e^x = 1 + \frac{x}{1
!} + \frac{x^2}{2
!} + \frac{x^3}{3
!} + \dots \frac{x^n}{n
!}$$
$$e^x = \sum_{n=0}^{\infty}\frac{x^n}{n!}$$