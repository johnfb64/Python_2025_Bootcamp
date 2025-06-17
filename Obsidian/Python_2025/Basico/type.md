#python
<%*
let concepto = "type()"
let fecha = tp.date.now("YYYY-MM-DD")
%>

### 🐍 type – Python

**📅 Fecha:** <% fecha %>  
**📘 Curso o Fuente:** Python a fondo  
**📍 Tema relacionado:** Tipos de datos, introspección, debugging  

---

#### 💡 Descripción del concepto  
> `type()` es una función incorporada en Python que permite conocer el tipo de un objeto o crear clases dinámicamente (uso avanzado).

---

#### 🔧 Función  
```python
type(objeto)
```

---

#### 📌 Sintaxis básica  
```python
# Devuelve el tipo del objeto
type(5)          # <class 'int'>
type("hola")     # <class 'str'>
type([1, 2, 3])   # <class 'list'>
```

---

#### 🛠 Ejemplo práctico  
```python
a = 10
b = "texto"
c = [1, 2, 3]
d = {"clave": "valor"}

for x in [a, b, c, d]:
    print(f"{x} -> {type(x)}")
```

---

#### 📤 Resultado  
> 
10 -> <class 'int'>  
texto -> <class 'str'>  
[1, 2, 3] -> <class 'list'>  
{'clave': 'valor'} -> <class 'dict'>

---

#### 🧠 Explicación del ejemplo  
> Se crean variables con distintos tipos de datos. Luego se itera sobre cada una, imprimiendo su contenido y su tipo usando `type()`.

---

#### 🧪 Variaciones o casos comunes  
- Usar `type()` para verificar el tipo antes de operar con una variable.
- Comparar tipos: `if type(x) == int:` (aunque se recomienda usar `isinstance()` en su lugar).

---

#### 🧭 Buenas prácticas  
- Prefiere `isinstance(x, tipo)` en lugar de `type(x) == tipo` cuando hagas validación de tipos.

---

#### ❓Errores comunes  
- Usar `type(x) == tipo` en vez de `isinstance(x, tipo)`, lo cual puede fallar si hay herencia.

---

#### 🧩 Relación con otros conceptos  
> Relacionado con `isinstance()`, clases (`class`), introspección, debugging.
> 	[[cadena]], [[lista]], [[numero]]

---

#### 📝 Anotaciones personales  
> `type()` es útil para entender cómo Python interpreta los datos internamente.

---

#### 🔁 Ejercicios propuestos  
- [ ] Crea una lista con diferentes tipos y usa `type()` para imprimir su tipo.
- [ ] Investiga cómo `type()` puede crear una clase dinámicamente.

---

#### 📚 Recursos complementarios  
- [Documentación oficial](https://docs.python.org/3/library/functions.html#type)
