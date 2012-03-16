# Complex Numbers

- definition of a complex number
- the set of all complex numbers `C = { x + yi | x, y ∈ R }`
- addition
- multiplication
- associative
- commutative
- `0 + 0i` is the __additive identity__
- `-z` is the __additive inverse__
- `z = 1 + 0i` is the __multiplicative identity__
- __Unique multiplicative inverse__ z^-1 = (x - yi) / (x^2 + y^2)
  - prove uniqueness
- the complex conjugate is of z = x + yi is z-bar = x - yi
- notice that zbar = (x - yi) / (x^2 + y^2) = zbar / (z * zbar) = 1 / z
  - useful to convert to standard form (`a + bi`)
- solving complex eqn:

  ```
  z + iw = 2
  iz + 2w = 3 for z,w ∈ C
  
  => z = 2 - iw
  => i(2 - iw) + 2w = 3
     2i + 3w = 3
     w = 1 - (2/3)i
     z = 2 - i(1-(2/3)i) = 4/3 - i
  ```
## Complex Plane

- graphing, |z|, intersections of sets

## Polar Coordinates

- from `(r, θ) -> (x, y)`:

```
x = rcosθ
y = rsinθ
```
- from `(x, y) -> (r, θ)`:

```
r = sqrt(x^2 + y^2)
// solve for θ
cosθ = x / r
sinθ = y / r
```
- not that polar representations are not unique: `(r, θ) = (r, θ + 2πk) // k ∈ Z`
- we usually choose `-π <= θ <= π` or `0 <= θ <= 2π`
- the polar form of z: `z = r(cosθ + isinθ)`
  - where `r = |z|` and θ is the __argument__ of `z`
  - we abbreviate this as `z = rcisθ` where `cisθ = cosθ + isinθ`
  - not that if `z = rcisθ` then `zbar = rcis(-θ)`

ex. Prove that |z/w| = |z| / |w| for z,w in C, w != 0
```

```

## Prop 28.1 De Moivre's Theorem (DMT)

If θ in R and n in Z then `(cosθ + isinθ)^n = cos(nθ) + isin(nθ)`

Proof:
```
We'll do induction for `n >= 0` and trea `n < 0` separately
```