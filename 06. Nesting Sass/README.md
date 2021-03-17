# Nesting en Sass

Refactorear el código generado en el ejercicio anterior para aprovechar el poder de la anidación.

Por ejemplo

```
	.info{
		border:$bordes;
		box-shadow:$sombras;
		h2,h3{
			color:$primary;
			strong{
				color:$dark
			}
		}
	}
```
