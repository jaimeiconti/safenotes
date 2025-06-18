# safenotes
Seguridad Integrada con DevSecOps

Paso 2
Abre el archivo de reporte y responde:
- Que dependencias tienen vulnerabilidades ?

R: evidencias\dependency-check-1.png (Revisar Imagen)

- Que versiones se sugiere Actualizar ?

R: evidencias\dependency-check-recomendations.png (Revisar Imagen)

Paso 4
Explora los reportes:
- ¿Se detectaron posibles ataques XSS, headers inseguros o vulnerabilidades CSRF?

R:
    Cabecera Content Security Policy (CSP) no configurada	
    Falta de cabecera Anti-Clickjacking	
    El servidor divulga información mediante un campo(s) de encabezado de respuesta HTTP ''''X-Powered-By''''	
    Falta encabezado X-Content-Type-Options

    (Revisar evidencias\app.js reporte zap.html)

Paso 5:
R: Revisar evidencias\pipeline github-actions simulado

¿En qué etapa del desarrollo debe integrarse cada herramienta?
R: Lo mejor sería que se integraran en fases tempranas de desarrollo (Desarrollo y Testing (QA)), para identificar vulnerabilidades, mejorar la seguridad del software y la calidad del desarrollo.

¿Cuál ofrece más valor para prevenir fallos en producción?
R Creo que el Analisis estático(SAST), ya que nos permite detectar fallos criticos y hasta bloquear un paso a producción.