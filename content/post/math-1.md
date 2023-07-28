---
title: "Math 1"
date: 2023-07-28T23:19:30+07:00
katex: true
---

### Nomor 14
##### Selesaikan limit trigonomettri berikut
\\(
    \begin{aligned}
    \displaystyle 
    \lim\limits_{x \to 0} \left (\frac{\sin x - \tan x} {x^2 \tan x} \right) 
    &= \lim\limits_{x \to 0} \left (\frac{\sin x - \frac{\sin x}{\cos x}} {x^2 \frac{\sin x}{\cos x}} \times \frac{\sin x \cos x}{\sin x \cos x} \right)\\\
    &= \lim\limits_{x \to 0} \left (\frac{\sin^2 x \cos x - \sin^2 x} {x^2 \sin^2 x} \right)\\\
    &= \lim\limits_{x \to 0} \left (\frac{\sin^2 x (\cos x - 1)} {x^2 \sin^2 x} \right)\\\
    &= \lim\limits_{x \to 0} \left (\frac{\sin^2 x} {x^2} \right) \times \lim\limits_{x \to 0} \left (\frac{\cos x - 1} {\sin^2 x} \right)\\\
    &= \lim\limits_{x \to 0} \left (\frac{\sin x} {x} \right)^2 \times \lim\limits_{x \to 0} \left (\frac{\cos x - 1} {1 - \cos^2 x} \right)\\\
    &= \left (\frac{1}{1} \right)^2 \times \lim\limits_{x \to 0} \left (\frac{\cos x - 1} {1 - \cos^2 x} \right)\\\
    \end{aligned}
\\)