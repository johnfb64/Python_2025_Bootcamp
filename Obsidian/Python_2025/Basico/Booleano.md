

### 🐍 Booleano – Python

**📅 Fecha:** 2025-06-10  
**📘 Curso o Fuente:**  
**📍 Tema relacionado:**  

---

#### 💡 Descripción del concepto  
> Es un tipo de [[Datos]] que puede ser verdadero (true) o falso (false). En terminos de veracidad de una variable u objeto, por defecto todos los objetos se consideran inicialmente verdaderos. 
> El [[Constructor]] de objetos de tipo [[Booleano]] es bool y permite convertir cualquier objeto en su valor. 
> 
> Que se considera falso en python? Ejemplos:
> 
bool(0)         # False
bool("")        # False
bool([])        # False
bool({})        # False
bool(None)      # False

---
#### 🔧 Función  
```python
# Definicion de la funcion. 
def mi_funcion():
    pass
```

---


#### 📌 Sintaxis básica  
```python
# Sintaxis o estructura general
print(bool(True), bool(False))
```


---

#### 🛠 Ejemplo práctico  
```python
# Código de ejemplo funcional
print(bool(0), bool(0j), bool(''), bool(complex(0)))

print(bool(1), bool(-1), bool('casa'), bool(24))
```

---

#### 🧠 Explicación del ejemplo  
> La primera linea genera false, false, false, false, por que estos valores serian equivalentes a false. 
> En el caso de la segunda linea, estos valores siempre corresponderan a true. 

---

#### 🧪 Operaciones con booleanos  
-  or       x or y # Si x es falso, entonces y, de otro modo x. (O es uno, o es otro...)
- and     x and y # Si x es falso, entonces x, de otro modo y. 
-  not     not x    Si x es falso, entonces True, de otro modo False. 

---

#### 🧭 Buenas prácticas  
-  
-  

---

#### ❓Errores comunes  
-  

---

#### 🧩 Relación con otros conceptos  
>  

---

#### 📝 Anotaciones personales  
>  

---

#### 🔁 Ejercicios propuestos  
- [ ]  
- [ ]  

---

#### 📚 Recursos complementarios  
- [Link a documentación oficial](https://docs.python.org/3/)
