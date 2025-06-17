

### 🧰 Consulta Inventarios – #Ansible

**📅 Fecha:** 2025-06-16  
**📘 Curso o Fuente:**  
**📍 Tema relacionado:**  

---

#### 💡 Descripción del concepto  
> Como consultar los inventarios. 

---

#### 📌 Comandos Basicos
```bash
# Revisar todos los hosts inscritos
ansible all --list-hosts

#Revisar todos los hosts desagrupados
ansible ungrouped --list-hosts

#Ver los hosts dentro de un grupo
ansible webservers --list-hosts
```

---

#### 🛠 Ejemplo práctico  
```yaml
#Sintaxis del archivo
[webservers]
server[a:d].lab.example.com

[raleigh]
servera.lab.example.com
serverb.lab.example.com

[mountainview]
serverc.lab.example.com

[london]
serverd.lab.example.com

[development]
servera.lab.example.com

[testing]
serverb.lab.example.com

[production]
serverc.lab.example.com
serverd.lab.example.com

[us:children]
raleigh
mountainview

```

---

#### 🧠 Explicación del ejemplo  
> Estos son los nombres de los grupos para ser utilizados luego en un play o comando adhoc. 
> Los "children" son combinaciones de dos grupos, en el ejemplo hay dos ciudades. 

---

#### 🧪 Casos comunes de uso  
-  Inventario y diseccion de servidores por area, region, pais, etc..
-  

---

#### ❓Errores comunes  
-  

---

#### 🧩 Relación con otros conceptos o módulos  
> ¿Este concepto se combina con roles, Jinja2, facts, handlers, etc.?
> [[inventario]]
> Se puede configurar su ruta en [[ansible.cfg]]

---

#### 📝 Anotaciones personales  
> Su comando `ansible` debe incluir la opción `-i inventory`. Esto hace que `ansible` use su archivo `inventory` en el directorio de trabajo actual en lugar del archivo de inventario del sistema `/etc/ansible/hosts`.

---

#### 🔁 Práctica en laboratorio  
- [ ] Probado en un playbook real  
- [ ] Verificado en múltiples hosts  
- [ ] Incluido en un rol o flujo más complejo  

---

#### 📚 Recursos complementarios  
- [Documentación oficial de Ansible](https://docs.ansible.com/)

