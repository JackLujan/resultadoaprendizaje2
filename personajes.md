# 📘 Guía de Creación de Personajes y NPCs

## 🎮 Propósito
Este documento tiene como objetivo definir los lineamientos y estructuras para la creación de personajes jugables (PCs) y personajes no jugables (NPCs) dentro del juego. Se busca garantizar coherencia narrativa, visual y funcional.

---

## 🧍‍♂️ Estructura General de un Personaje

### Datos Generales
Nombre completo:  
Edad:  
Género:  
Raza / Especie:  
Clase / Profesión:  
Alineamiento:  
Lugar de origen:  

### Descripción Física
Altura:  
Peso:  
Color de ojos:  
Color de cabello:  
Peculiaridades físicas (cicatrices, tatuajes, prótesis, etc.):  

### Personalidad
Rasgos principales:  
Motivaciones:  
Miedos:  
Debilidades:  
Frases típicas o muletillas:  

### Historia Personal
Breve resumen de su historia, eventos importantes y su situación actual.

---

## 🤖 Estructura General de un NPC

### Datos Generales
Nombre:  
Función en el juego (comerciante, enemigo, guía, etc.):  
Ubicación habitual:  
Disponibilidad horaria (si aplica):  

### Comportamiento
Rutina diaria:  
Reacciones al jugador:  
Frases comunes:  

### Relación con el Jugador
Misiones que ofrece:  
Vínculos con otros personajes:  
Impacto en la historia principal o secundarias:  

---

## 🎨 Diseño Visual (opcional)
Incluir referencias visuales o links a ilustraciones/concept art.

---

## 🛠️ Datos Técnicos
ID del personaje:  
Estado (activo/inactivo/provisional):  
Nivel de dificultad (si es enemigo o jefe):  
Habilidades especiales:  

---

## 📂 Ejemplo de Ficha de Personaje

```json
{
  "id": "npc_merchant_001",
  "nombre": "Elia la Mercader",
  "tipo": "NPC",
  "funcion": "Comerciante de pociones",
  "ubicacion": "Aldea Verde",
  "dialogo_inicial": "¡Hola, viajero! ¿Te interesa una poción?",
  "rutina": {
    "mañana": "Abre tienda",
    "tarde": "Atiende clientes",
    "noche": "Cierra tienda y regresa a casa"
  },
  "relacion_jugador": {
    "misiones": ["Entrega de hierbas", "Recupera la caja robada"],
    "impacto": "Acceso a pociones raras si completas todas sus misiones"
  }
}
