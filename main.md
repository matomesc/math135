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