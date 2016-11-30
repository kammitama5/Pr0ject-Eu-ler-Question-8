# Pr0ject-Eu-ler-Question-8
Pseudo-code

I think...unless columns and word-searchiness is allowed (eg diagonals) or snake-iness,
//read in first thirteen numbers
//find product of those numbers
//read in next thirteen numbers and do the same
//if the product is larger than the previous product
//is more than the previous product\
//replace the old product with new product
//keep going until you run out of input file-ness :)

--Possible Haskell-esque/functionally solution
--Split every thirteen values (will give an array for each one)
--Map over each array separately with foldl1(*) and get product


?use partition, take items and fold * => Clojure or Haskell


