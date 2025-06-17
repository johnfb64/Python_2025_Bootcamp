

### 🧰 Archivo ansible.cfg – #Ansible

**📅 Fecha:** 2025-06-16  
**📘 Curso o Fuente:**  
**📍 Tema relacionado:**  

---

#### 💡 Descripción del concepto  
> Explicación del módulo o funcionalidad de Ansible con tus propias palabras.

---

#### 📌 Sintaxis básica  
```yaml
[defaults]
inventory = ./inventory
remote_user = user
ask_pass = false

[privilege_escalation]
become = true
become_method = sudo
become_user = root
become_ask_pass = false

```

---

#### 🛠 Ejemplo práctico  
```yaml
# Ejemplo funcional usando [defaults]
inventory = ./inventory
remote_user = user
ask_pass = false

[privilege_escalation]
become = true
become_method = sudo
become_user = root
become_ask_pass = falseel módulo o concepto
```

---

#### 🧠 Explicación del ejemplo  
> Este archivo se crea para indicar a ansible de donde obtener el inventario. Se puede dejar en la carpeta donde se desplegara el proyecto o rol de ansible. 

---

#### 🧪 Casos comunes de uso  
-  El archivo base esta ubicado en /etc/ansible/ansible.cfg
-  SI se quiere configurar desde home de usuario "~/.ansible.cfg"
- Si se quiere dedicar a un proyecto en una carpeta "./ansible.cfg"
- Desde variable de entorno con ANSIBLE_CONFIG


---

#### ❓Errores comunes  
-  

---

#### 🧩 Relación con otros conceptos o módulos  
> ¿Este concepto se combina con roles, Jinja2, facts, handlers, etc.?

---

#### 📝 Anotaciones personales  
> ask_pass = false or true
> Siempre habia puesto false, pero la razon de ser es que al ser false se da por entendido que se utiliza relacion de confianza. En caso de no tenerla, se usa password. 
> become_true: Esta directiva es para que escale a root. debe tener la configuracion del visudo "someuser ALL=(ALL) NOPASSWD:ALL".

---

#### ⚠️ Importante
> La práctica recomendada es crear un archivo `ansible.cfg` en un directorio desde el que ejecute comandos de Ansible. El directorio también contendría archivos usados por su proyecto Ansible, como un inventario y una guía. Esta es la ubicación más común usada para el archivo de configuración de Ansible. Es inusual usar un archivo `~/.ansible.cfg` o `/etc/ansible/ansible.cfg` en la práctica.

---
#### ⚠️ Importante
> El orden de en el que Ansible tomara el ansible cfg es el siguiente:


> - **Variable de entorno** [[ANSIBLE_CONFIG
    
- Archivo `ansible.cfg` en el **directorio actual**
    
- Archivo en `~/.ansible.cfg`
    
- Archivo global en `/etc/ansible/ansible.cfg`

---

#### 🔁 Práctica en laboratorio  
- [x] Probado en un playbook real  
- [x] Verificado en múltiples hosts  
- [x] Incluido en un rol o flujo más complejo  

---

#### 📚 Recursos complementarios  
- [Documentación oficial de Ansible](https://docs.ansible.com/)
