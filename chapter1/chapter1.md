# chapter1

## 1.1逻辑命题

### 命题

* p的否命题记为 ┐p或者 

$$
\overline{p}
$$

* p命题与q命题的合取(与) 记为 p∧q (AND)。
* 析取(或，同或)记为 p∨q (OR)。
* 异或记为p⊕q(XOR)。

### 条件命题

* p→q：条件语句，if p then q。p为true，q为false，则p→q为false，其余皆为true。如果p→q为true，则p为true时q为true。p为条件q为结论。
* p↔q：双蕴含(重复必要条件)。



## 1.2命题等价

### 练习题 

15.  (┐q ∧ (p→q) ) → ┐p ≡ (┐q ∧ (┐p ∨ q) ) → ┐p ≡ ((┐q ∧ ┐p) ∨ (┐q ∧ q)) → ┐p

     ≡ ((┐q ∧ ┐p) ∨ F) → ┐p ≡ (┐q ∧ ┐p) → ┐p ≡ ┐ (q ∨ p) → ┐p ≡ (q ∨ p) ∨ ┐p

     ≡ q ∨ (p ∨ ┐p)  ≡ q ∨ T   ≡ T