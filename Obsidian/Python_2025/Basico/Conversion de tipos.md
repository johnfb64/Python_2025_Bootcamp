#python


### 🐍 conversion_de_tipos #python – Python

**📅 Fecha:** 2025-06-16  
**📘 Curso o Fuente:**  
**📍 Tema relacionado:**  

---

#### 💡 Descripción del concepto  
> En python se pueden convertir explicitamente tipos usando funciones [[Constructor]]as. 


> |Función|Convierte a...|Ejemplo|
|---|---|---|
|`int()`|Entero|`int("5") → 5`|
|`float()`|Decimal|`float("3.14") → 3.14`|
|`str()`|Cadena|`str(10) → "10"`|
|`bool()`|Booleano|`bool(0) → False`, `bool("a") → True`|
|`list()`|Lista|`list("abc") → ['a', 'b', 'c']`|
|`tuple()`|Tupla|`tuple([1, 2]) → (1, 2)`|


---
#### 🔧 Función  
```python
#Conversion tipos en python
texto = "25"
numero = int(texto)

```

---

#### 📌 Sintaxis básica  
```python
# Sintaxis o estructura general

```

---

#### 🛠 Ejemplo práctico  
```python
# Código de ejemplo funcional
texto = "25"
numero = int(texto)
print (f"{texto} como entero es {numero}")
  

decimal = float(numero)
print(f"{numero} como float es {decimal}")

cadena = str(decimal)
print(f"{decimal} como cadena es '{cadena}'")

#Booleanos

  

print(bool(""))
print(bool("Hola"))
print(bool(0))
print(bool(1))
```

---

#### 📤 Resultado  
> 25 como entero es 25
25 como float es 25.0
25.0 como cadena es '25.0'
False
True
False
True

---

#### 🧠 Explicación del ejemplo  
> Aqui, cuando texto originalmente era 25, por medio de "[[numero]] = int(texto)" se le esta indicando a python que convierta ese dato de tipo texto a entero "int". Asi mismo con el resto del codigo. 

---

#### 🧪 Variaciones o casos comunes  
-  
-  

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
