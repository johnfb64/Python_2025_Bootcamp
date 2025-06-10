## 🧪 Ejercicio: Intercambio de variables (vasos)

**📝 Instrucción:**  
Tienes dos variables:  
```python
glass1 = "milk"
glass2 = "juice"
```

Tu objetivo es intercambiar el contenido de las variables, de modo que:

- `glass1` termine con `"juice"`
- `glass2` termine con `"milk"`

🚫 **Restricción:** No puedes volver a escribir las palabras `"milk"` o `"juice"` en el código. Solo puedes usar variables.

---

### 🔧 Código solución

```python
glass1 = "milk"
glass2 = "juice"

glass3 = glass1
glass1 = glass2
glass2 = glass3
```

---

### 📤 Resultado esperado

```python
print(glass1)  # "juice"
print(glass2)  # "milk"
```

---

### 💡 Conceptos clave

- Las variables pueden sobrescribirse.
- Si no quieres perder el contenido original, debes **guardarlo en una variable temporal** antes de sobrescribir.
- Este patrón se llama **intercambio de valores usando variable auxiliar**.

---

### 🧠 Reflexión

Este tipo de ejercicios te enseña a pensar en **cómo fluye la información entre variables**. Es una base muy útil para más adelante, por ejemplo, al trabajar con algoritmos, funciones, estructuras de datos, etc.

[[Variables]]

---

