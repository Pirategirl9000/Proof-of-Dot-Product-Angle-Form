# Proof of Dot Product Equivilent Form
### Show $\vec{v} \cdot \vec{u} = |\vec{v}||\vec{u}|cos(\theta)$
---

### Theorem
#### For any two vectors $\vec{v}$ and $\vec{u}$ and the angle between them $\theta$
> #### $\vec{v} \cdot \vec{u} = |\vec{v}||\vec{u}|cos(\theta)$

---
### Proof
---

### Lemma 1 -  Law of Cosines:
#### Let A, B, and C be the vertices of a triangle and $\alpha$, $\beta$, and $\gamma$ be the angles at those respective points
> #### (i) $A = B^2 + C^2 - 2BCcos(\alpha)$
> #### (ii) $B = A^2 + C^2 - 2ACcos(\beta)$
> #### (iii) $C = A^2 + B^2 - 2ABcos(\gamma)$
> #### Assume this statement holds true for any points A, B, and C

---

### Lemma 2 - Distance and Magnitude Formula:
#### Let A and B be two points such that $A,B \in\reals^n$ and let vector $\vec{v} = \vec{AB}$
> #### (i)   The distance between A and B is $\sqrt{(B_1-A_1)^2+(B_2-A_2)^2+\cdots+(B_n-A_n)^2}$
> #### (ii)  The vector between A and B is $\vec{v} = \begin{bmatrix}B_1-A_1&B_2-A_2&\cdots&B_n-A_n\end{bmatrix}$
> #### (iii) The magnitude of the vector  $|\vec{v}| = \sqrt{v_1^2 + v_2^2 + \cdots + v_n^2}$
> #### Therefore the magnitude of a vector $\vec{v}$ between points A and B is the distance between A and B

---

### Lemma 3 - Magnitude Squared Dot Product Equivilence:: 
#### Let $\vec{v}$ be a vector such that $\vec{v} \in V^n$
> #### (i)     $|\vec{v}| = \sqrt{v_1^2 + v_2^2 + \cdots + v_n^2}$ by Lemma 2
> #### (ii)    $\vec{v} \cdot \vec{v} = v_1 \cdot v_1 + v_2 \cdot v_2 + \cdots + v_n \cdot v_n = v_1^2 + v_2^2 + \cdots + v_n^2$
> #### (iii)   $|\vec{v}|^2 = v_1^2+v_2^2+v_n^2$
> #### Therefore $|\vec{v}|^2 = \vec{v} \cdot \vec{v}$

---

#### Let A, B, C be three points such that
> * #### $A,B,C\in \reals^n$
> * #### $\vec{v} = \vec{AB} = \begin{bmatrix}B_1-A_1&B_2-A_2&\cdots&B_n-A_n\end{bmatrix}$
> * #### $\vec{u} = \vec{AC} = \begin{bmatrix}C_1-A_1&C_2-A_2&\cdots&C_n-A_n\end{bmatrix}$
> * #### $\vec{w} = \vec{BC} = \begin{bmatrix}C_1-B_1&C_2-B_2&\cdots&C_n-B_n\end{bmatrix}$

> #### (i)    $\vec{u} - \vec{v} = \begin{bmatrix}C_1-A_1+A_1-B_1&C_2-A_2+A_2-B_2&\cdots&C_n-A_n+A_n-B_n\end{bmatrix} = \begin{bmatrix}C_1-B_1&C_2-B_2&\cdots&C_n-B_n\end{bmatrix} = \vec{w}$
> #### Therefore $\vec{u} - \vec{v} = \vec{w}$
> #### (ii)   $|\vec{u}-\vec{v}|^2 = (\vec{u} -\vec{v}) \cdot (\vec{u} - \vec{v})$ by Lemma 3
> #### (iii) $(\vec{u} - \vec{v}) \cdot (\vec{u} - \vec{v}) = \vec{u} \cdot \vec{u} + \vec{v} \cdot \vec{v} - 2({\vec{v} \cdot \vec{u})}$ by distributive property of vectors
> #### (iv) $|\vec{u} - \vec{v}|^2 = |\vec{v}|^2 + |\vec{u}|^2 - 2|\vec{v}||\vec{u}|cos(\theta)$ by Lemma 1
> #### (v) $|\vec{v}|^2 + |\vec{u}|^2-2|\vec{v}||\vec{u}|cos(\theta) = |\vec{u}|^2+|\vec{v}|^2 - 2(\vec{v}\cdot\vec{u}) \iff |\vec{v}||\vec{u}|cos(\theta) = \vec{v} \cdot \vec{u}$

### Therefore for any two vectors $\vec{v}$ and $\vec{u}$ and the angle between them $\theta$ 
> ### $\vec{v} \cdot \vec{u} = |\vec{v}||\vec{u}|cos(\theta)$ 
### is proven true by direct proof






<sup>quod erat demonstrandum &#8718;
