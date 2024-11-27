# FG-Product-Card

Este es un paquete de pruebas de despliegue en NPM

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'fg-product-card';
```

```
<ProductCard
  product={ product }
  initialValues={{
    count:4,
    maxCount:10
  }}
  >
    {
      ({ count, isMaxCountReached, reset, increaseBy  }) => (
        <>
          <ProductImage />
          <ProductTitle />
          <ProductButtons />
        </>
      )
    } 
</ProductCard>
```