# FHF-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Felipe Hinojosa

## Ejemplo

```javascript
import {
  ProductCard,
  ProductImage,
  ProductTitle,
  ProductButtons,
} from 'fhf-product-card';
```

```javascript
<ProductCard
  product={product}
  initialValues={{
    count: 4,
    maxCount: 10,
  }}
>
  {({ reset, increaseBy, isMaxCountReached, count, maxCount }) => (
    <>
      <ProductImage />
      <ProductTitle />
      <ProductButtons />
    </>
  )}
</ProductCard>
```
