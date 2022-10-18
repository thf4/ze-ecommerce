# Products

> ## Success Case

1. ✅  Receive request **POST** router /product
1. ✅  Validate request if user has expecific authorization.
2. ✅  Create product with descriptions and others parameters.
3. ✅  Updated product data with id **PUT** router /product/${productId}
4. ✅ List all products created **GET** router /products
5. ✅ Search products with especifc parameters **GET** router /products?params=params
6. ✅ Delete products with id **DELETE** router /product/${productID}


> ## Exceptions
1. ✅ Return 404 when api doesn't exist.
2. ✅ Return 401 when user don't have expecific authorization.
3. ✅ Return 500 when admin try create product and service doesn't work.
4. ✅ Return 500 when admin try to update product data and service doesn't work.
5. ✅ Return 404 when api don't have any product.
6. ✅ Return 404 when api don't find that especific product with parameters.
7. ✅ Return 404 when api don't find product with id.