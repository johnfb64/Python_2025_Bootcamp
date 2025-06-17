

### 🧰 Variable de entorno ANSIBLE_CONFIG – #Ansible

**📅 Fecha:** 2025-06-16  
**📘 Curso o Fuente:**  
**📍 Tema relacionado:**  

---

#### 💡 Descripción del concepto  
> Es la variable de entorno con la que Ansible le dara prioridad al archivo [[ansible.cfg]]. La ruta de este archivo es la que guardara esta variable. 
> "Si defines `ANSIBLE_CONFIG`, **Ansible usará exclusivamente ese archivo**, sin seguir buscando en otras rutas."

---

#### 📌 Sintaxis básica  
```yaml
# Estructura típica del módulo/concepto
```

---

#### 🛠 Ejemplo práctico  
```bash
# Ejemplo funcional usando el módulo o concepto
export ANSIBLE_CONFIG=/ruta/a/mi/ansible.cfg
```

---

#### 🧠 Explicación del ejemplo  
> Línea por línea, qué hace el código anterior.

---

#### 🧪 Casos comunes de uso  
-  Cuando se tienen varios proyectos con configuraciones distintas. 
-  Evitar conflictos entre configuraciones
- Se estan haciendo pruebas y no se quieren tocar los archivos de configuración. 

---

#### ❓Errores comunes  
-  

---

#### 🧩 Relación con otros conceptos o módulos  
> ¿Este concepto se combina con roles, Jinja2, facts, handlers, etc.?

---

#### 📝 Anotaciones personales  
> Ideas, problemas que encontraste, aprendizajes, etc.

---

#### ⚠️ Importante
>Si usas `ANSIBLE_CONFIG` y ese archivo tiene errores o no existe, Ansible **no buscará otro archivo**, y puede fallar. Úsalo cuando tengas claro que ese es el archivo correcto.

---

#### 🔁 Práctica en laboratorio  
- [ ] Probado en un playbook real  
- [ ] Verificado en múltiples hosts  
- [ ] Incluido en un rol o flujo más complejo  

---

#### 📚 Recursos complementarios  
- [Documentación oficial de Ansible](https://docs.ansible.com/)
