<!-- .slide: data-background="#ffffffcc" -->
## Vector Math and Notation

---

<!-- .slide: data-background="#ffffffcc" -->
### Vector notation

\vec{v} = v\_1\hat{\imath} + v\_2\hat{\jmath} + v\_3\hat{k} + \ldots + v\_n\hat{e\_n} = \left&lt; v\_1, v\_2, v\_3, \ldots, v\_n \right&gt; <!-- .element: class="display math" -->

---


---

<!-- .slide: data-background="#ffffffcc" -->
### Vector addition / subtraction

\vec{a} + \vec{b} = \left&lt; a\_1 + b\_1, a\_2 + b\_2, a\_3 + b\_3, \ldots, a\_n + b\_n \right&gt; <!-- .element: class="display math" -->

\vec{a} - \vec{b} = \left&lt; a\_1 - b\_1, a\_2 - b\_2, a\_3 - b\_3, \ldots, a\_n - b\_n \right&gt; <!-- .element: class="display math" -->

---


---

<!-- .slide: data-background="#ffffffcc" -->
### Scalar multiplication

c\vec{v} = \left&lt; cv\_1, cv\_2, cv\_3, \ldots, cv\_n \right&gt; <!-- .element: class="display math" -->

---


---

<!-- .slide: data-background="#ffffffcc" -->
### Magnitude / Unit Vector

||\vec{v}|| = \sqrt{v\_1^2+v\_2^2+v\_3^2+\ldots+v\_n^2} <!-- .element: class="display math" -->

\text{unit vector of }\vec{v} = \frac{\vec{v}}{||\vec{v}||} <!-- .element: class="display math" -->

---


---

<!-- .slide: data-background="#ffffffcc" -->
### Dot Product / Projection

\vec{a} \cdot \vec{b} = a\_1b\_1 + a\_2b\_2 + a\_3b\_3 + \ldots + a\_nb\_n <!-- .element: class="display math" -->

\text{proj}\_{\vec{a}}\vec{b} = \frac{\vec{a} \cdot \vec{b}}{||\vec{a}||^2}\vec{a} <!-- .element: class="display math" -->

---


---

<!-- .slide: data-background="#ffffffcc" -->
### Cross Product (3D vectors only)

\begin{aligned}\vec{a}\times\vec{b}&=\begin{vmatrix}\hat{\imath}&\hat{\jmath}&\hat{k}\\\\a\_1&a\_2&a\_3\\\\b\_1&b\_2&b\_3\end{vmatrix}\\\\&=\begin{vmatrix}a\_2&a\_3\\\\b\_2&b\_3\end{vmatrix}\hat{\imath}+\begin{vmatrix}a\_1&a\_3\\\\b\_1&b\_3\end{vmatrix}\hat{\jmath}+\begin{vmatrix}a\_1&a\_2\\\\b\_1&b\_2\end{vmatrix}\hat{k}\\\\&=\left(a\_2b\_3-b\_2a\_3\right)\hat{\imath}+\left(a\_1b\_3-b\_1a\_3\right)\hat{\jmath}+\left(a\_1b\_2-b\_1a\_2\right)\hat{k}\\\\&=\left&lt;a\_2b\_3-a\_3b\_2,a\_1b\_3-a\_3b\_1,a\_1b\_2-a\_2b\_1\right&gt;\end{aligned} <!-- .element: class="display math" -->

---
