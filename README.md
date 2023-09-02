# Solid y Clean Code

### Nombres de variables

- Mal
```
const n = 30
const ls = 0.15
const cat = 'hola'
const ddmmyyyy = new Date('August 15, 1990 00:00:00')
```

- Bien
```
const numeroLimite = 30
const impuesto = 0.15
const saludo = 'hola'
const fecha_nacimiento = new Date('August 15, 1990 00:00:00')
```

#### Ausencia de informacion técnica en nombres

- Mal
```
class AbstractUser { }
class UserMixin { }
class UserImplementation { }
interface UserInterface { }
```

- Bien
```
class User { }
interface User { }
```
