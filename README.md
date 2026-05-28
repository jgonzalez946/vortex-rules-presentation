# 🎤 Presentación VortexRules

Presentación interactiva en HTML para mostrar al cliente la plataforma VortexRules.

## 🎨 Paleta de Colores (Brand VortexRules)

La presentación utiliza la paleta oficial del logo sobre fondo claro para máximo contraste:

| Color | HEX | Uso |
|-------|-----|-----|
| 🔵 **Azul Eléctrico** | `#0511F2` | Primario, títulos, énfasis |
| 🩵 **Turquesa** | `#04BFBF` | Secundario, acentos, gradientes |
| 🟡 **Amarillo/Dorado** | `#F2E205` | Acentos, highlights, badges |
| 🟠 **Naranja** | `#F2811D` | Warnings, estados en progreso |
| ⬜ **Gris Claro** | `#f8f9fa` | Fondo principal |
| ⬛ **Negro** | `#0D0D0D` | Texto principal |

## 🚀 Cómo usar

### Opción 1: Abrir directo (Más fácil)
1. Hacé doble click en `index.html`
2. Se abre en tu navegador predeterminado
3. ¡Listo para presentar!

### Opción 2: Servidor local (Recomendado)
Si querés una experiencia más profesional o compartir en red local:

```bash
# Con Python 3
python -m http.server 8080

# Con Node.js (si tenés http-server instalado)
npx http-server -p 8080

# Con PHP
php -S localhost:8080
```

Después abrí: http://localhost:8080

## 🎮 Controles

| Tecla | Acción |
|-------|--------|
| `→` o `Espacio` | Slide siguiente |
| `←` | Slide anterior |
| `Home` | Ir al primer slide |
| `End` | Ir al último slide |
| `Swipe` (touch) | Navegación en mobile |

## 📋 Contenido de la presentación (15 slides)

1. **Portada** - Logo VortexRules + tagline
2. **Agenda** - Qué vamos a ver
3. **El Problema** - Pain points y métricas
4. **La Solución** - VortexRules en una oración
5. **Arquitectura** - Diagrama de microservicios
6. **Dashboard** - KPIs y métricas en tiempo real
7. **Authoring Wizard** - Creación de reglas
8. **QA Simulator** - Testing integrado
9. **Governance** - Workflow de aprobaciones
10. **Demo Flujo** - Paso a paso completo
11. **Integraciones** - API REST + BPMN
12. **Diferenciadores** - Tabla comparativa
13. **Roadmap** - Timeline Q1-Q4
14. **Beneficios** - ROI y métricas
15. **Next Steps** - Cómo empezar + Q&A

## 🎨 Características

- ✅ **Logo integrado** - En portada (grande) y esquina superior (pequeño)
- ✅ **Paleta brand** - Colores oficiales del logo (#0511F2, #04BFBF, #F2E205, #F2811D)
- ✅ **Diseño profesional** - Tema claro con alto contraste y gradientes azul-turquesa
- ✅ **Totalmente responsive** - Funciona en mobile y desktop
- ✅ **Navegación limpia** - Solo teclado y touch (sin botones visibles)
- ✅ **Animaciones suaves** - Transiciones y efectos visuales
- ✅ **Sin dependencias** - Solo necesitás el logo.png + index.html

## 📁 Estructura

```
presentacion-vortexrules/
├── index.html      # Presentación completa
├── logo.png        # Logo oficial VortexRules (obligatorio)
└── README.md       # Este archivo
```

## 💡 Tips para presentar

1. **Conocé la audiencia**: Si hay gente de negocio, enfocate en el valor (velocidad, ROI). Si hay técnicos, profundizá en arquitectura.

2. **Demo en vivo**: Si podés, mostrá el sistema real en paralelo a los slides 6-10.

3. **Timing**: La presentación completa debería durar entre 20-30 minutos.

4. **Preparate para preguntas**: Tené a mano el PRD_VortexRules_v1.md y el ROADMAP.md para datos técnicos.

## 🔧 Personalización

Si querés modificar algo:

- **Colores**: Editá las variables CSS en `:root` (línea ~30 del HTML)
- **Contenido**: Editá directamente los slides en el HTML

## 🌐 Compatibilidad

- Chrome/Edge (recomendado)
- Firefox
- Safari
- Mobile browsers (iOS Safari, Chrome Android)

---

**¿Problemas?** Abrí el archivo directo con doble click. No necesitás servidor ni instalar nada.

**¿Preguntas?** Consultá el `PRESENTATION_PROMPT.md` en la raíz del proyecto para más contexto.

---

*Generado el: 2026-05-28*
