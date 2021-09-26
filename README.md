# LibreriaAngular

Crear libreria
```
ng g library <name_library> -p=GB  #-p === --prefix (Usado para que no se use el app-nombre-componete, sino el GB-nombre-componente)
```

# Compilar Libreria
(Primero en la raiz del proyecto tsconfig.json -> "angularCompilerOptions": {"enableIvy": false})
```
ng build <name_library> 
```