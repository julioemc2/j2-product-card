# j2-Product-Card

Este es un paquete de despliegue en NPM

### Julio Galindo

## Ejemplo
```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'j2-product-card';
```

```
<ProductCard 
    key={ product.id }
    product={ product } 
    initialValues={{
        count: 4,
    //    maxCount: 10
    }}

>
    {
        //( args ) => (
        ({ reset, count, isMaxCountReached, maxCount, increaseBy }) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>
        )
    }
</ProductCard>
```