# 📊 Funciones Cuadráticas con MATLAB - Manual de Usuario

## 🚀 Inicio Rápido

### 1. Abrir la Aplicación
- Abre el archivo `index.html` en tu navegador web
- La aplicación se cargará automáticamente con la pestaña "Trayectoria de Proyectil"

### 2. Configurar MATLAB
1. Haz clic en **"⚙️ Configurar Conexión"**
2. Selecciona tu método de conexión:
   - **ThingSpeak** (Recomendado)
   - **MATLAB Online**
   - **MATLAB Local**
3. Ingresa tus credenciales
4. Haz clic en **"🔍 Probar Conexión"**
5. Si es exitosa, haz clic en **"💾 Guardar Configuración"**

## 📚 Problemas Disponibles

### 🎯 1. Trayectoria de Proyectil
**¿Qué hace?** Calcula la trayectoria de un objeto lanzado al aire.

**Parámetros:**
- **Coeficiente a**: Aceleración gravitacional (usualmente -5)
- **Coeficiente b**: Velocidad inicial vertical (m/s)
- **Coeficiente c**: Altura inicial (m)

**Ejemplo:**
- a = -5, b = 10, c = 2
- Resultado: h(t) = -5t² + 10t + 2

### 💰 2. Maximización de Ganancias
**¿Qué hace?** Encuentra el precio óptimo para maximizar ganancias.

**Parámetros:**
- **Cantidad máxima**: Demanda máxima esperada
- **Costo de producción**: Costo por unidad
- **Costos fijos**: Gastos independientes de la cantidad

**Ejemplo:**
- Cantidad máxima: 100, Costo producción: 20, Costos fijos: 1000
- Resultado: G(x) = -x² + 120x - 2000

### 🌉 3. Diseño de Arcos Parabólicos
**¿Qué hace?** Diseña arcos arquitectónicos con forma parabólica.

**Parámetros:**
- **Ancho del arco**: Distancia entre soportes (m)
- **Altura máxima**: Altura del vértice (m)
- **Separación entre soportes**: Distancia entre puntos de apoyo (m)

**Ejemplo:**
- Ancho: 20m, Altura: 8m, Separación: 2m
- Resultado: y = -0.08(x-10)² + 8

## 🔬 Análisis Avanzados

### 📊 Análisis de Sensibilidad
**¿Qué hace?** Estudia cómo los cambios en parámetros afectan los resultados.

**Cómo usar:**
1. Resuelve un problema básico
2. En la sección "Análisis Avanzado", haz clic en **"Análisis de Sensibilidad"**
3. Espera a que MATLAB procese (2-3 segundos)
4. Revisa los resultados y gráficos generados

**Qué muestra:**
- Rango de variación de resultados
- Coeficiente de sensibilidad
- Gráficos 3D de la superficie de respuesta

### 🎲 Simulación Monte Carlo
**¿Qué hace?** Genera miles de escenarios aleatorios para analizar incertidumbre.

**Cómo usar:**
1. Resuelve un problema básico
2. Haz clic en **"Simulación Monte Carlo"**
3. Espera el procesamiento (3-5 segundos)
4. Analiza las distribuciones estadísticas

**Qué muestra:**
- Distribución de probabilidad de resultados
- Intervalos de confianza del 95%
- Estadísticas descriptivas (media, desviación estándar)

### ⚡ Análisis de Optimización
**¿Qué hace?** Encuentra los valores óptimos de parámetros.

**Cómo usar:**
1. Resuelve un problema básico
2. Haz clic en **"Análisis de Optimización"**
3. Revisa los parámetros óptimos encontrados
4. Analiza las curvas de nivel y puntos óptimos

**Qué muestra:**
- Valores óptimos de parámetros
- Valor óptimo de la función objetivo
- Validación matemática de la solución

## 📖 Explicaciones Educativas

### Cómo Acceder
1. Busca el icono **ℹ️** junto a cualquier ecuación
2. Haz clic en el icono
3. Se abrirá un modal con explicación detallada

### Contenido Incluido
- **Conceptos teóricos** explicados paso a paso
- **Fórmulas matemáticas** con notación profesional
- **Código MATLAB** con sintaxis resaltada
- **Aplicaciones prácticas** en ingeniería
- **Objetivos de aprendizaje** para cada tema

## 🎨 Interfaz de Usuario

### Navegación
- **Pestañas**: Cambia entre los 3 problemas
- **Botones de cálculo**: Resuelven problemas básicos
- **Botones de MATLAB**: Ejecutan análisis con MATLAB
- **Iconos de información**: Abren explicaciones educativas

### Indicadores de Estado
- **🟢 Verde**: MATLAB conectado y listo
- **🔴 Rojo**: MATLAB desconectado
- **🟡 Amarillo**: Procesando análisis

### Notificaciones
- **✅ Éxito**: Operación completada correctamente
- **❌ Error**: Problema que requiere atención
- **ℹ️ Información**: Mensajes informativos
- **⏳ Cargando**: Proceso en ejecución

## ⚙️ Configuración Avanzada

### Métodos de Conexión MATLAB

#### ThingSpeak (Recomendado)
1. Crea cuenta en [ThingSpeak.com](https://thingspeak.com)
2. Obtén tu User API Key
3. Crea un canal y anota el Channel ID
4. Ingresa ambos valores en la configuración

#### MATLAB Online
1. Crea cuenta en [MathWorks.com](https://mathworks.com)
2. Obtén un API Token de MATLAB Online
3. Ingresa el token en la configuración

#### MATLAB Local
1. Instala MATLAB en tu computadora
2. Configura un servidor local (puerto 3000)
3. Ingresa la URL del servidor local
4. Opcionalmente, agrega una API Key local

### Persistencia de Datos
- La configuración se guarda automáticamente
- Los datos persisten entre sesiones
- Puedes cambiar la configuración en cualquier momento

## 🔧 Solución de Problemas

### Error: "No se puede conectar a MATLAB"
**Solución:**
1. Verifica tu conexión a internet
2. Confirma que las credenciales son correctas
3. Prueba con un método de conexión diferente
4. Revisa que MATLAB esté funcionando correctamente

### Error: "Parámetros inválidos"
**Solución:**
1. Asegúrate de que todos los campos estén llenos
2. Verifica que los valores sean números válidos
3. Revisa que los rangos sean apropiados para el problema

### Error: "Análisis falló"
**Solución:**
1. Verifica que MATLAB esté conectado
2. Intenta con parámetros más simples
3. Revisa la consola del navegador para errores detallados

### La aplicación se ve mal
**Solución:**
1. Actualiza tu navegador a la versión más reciente
2. Verifica que JavaScript esté habilitado
3. Limpia la caché del navegador

## 📊 Interpretación de Resultados

### Gráficos
- **Eje X**: Variable independiente (tiempo, cantidad, distancia)
- **Eje Y**: Variable dependiente (altura, ganancia, altura del arco)
- **Puntos rojos**: Valores óptimos o críticos
- **Líneas de color**: Diferentes escenarios o análisis

### Estadísticas
- **Media**: Valor promedio
- **Desviación estándar**: Variabilidad de los datos
- **Intervalo de confianza**: Rango probable de valores
- **Coeficiente de variación**: Sensibilidad relativa

### Código MATLAB
- **Comentarios en verde**: Explicaciones del código
- **Palabras clave en azul**: Comandos de MATLAB
- **Strings en naranja**: Texto y etiquetas
- **Números en blanco**: Valores numéricos

## 🎓 Consejos para el Aprendizaje

### Para Estudiantes
1. **Empieza simple**: Usa parámetros básicos primero
2. **Experimenta**: Cambia valores y observa los resultados
3. **Lee las explicaciones**: Usa los iconos ℹ️ para aprender más
4. **Prueba análisis avanzados**: Una vez que entiendas lo básico

### Para Profesores
1. **Usa las explicaciones**: Son perfectas para clases
2. **Demuestra conceptos**: Los gráficos ayudan a visualizar
3. **Análisis avanzados**: Para estudiantes de nivel superior
4. **Código MATLAB**: Muestra implementación real

### Para Ingenieros
1. **Análisis de sensibilidad**: Para evaluar robustez de diseños
2. **Monte Carlo**: Para análisis de riesgo
3. **Optimización**: Para encontrar soluciones óptimas
4. **Código reutilizable**: Adapta el código MATLAB a tus proyectos

## 🔄 Flujo de Trabajo Recomendado

### 1. Configuración Inicial
1. Abre la aplicación
2. Configura MATLAB
3. Prueba la conexión

### 2. Resolución de Problemas
1. Selecciona un problema
2. Ingresa los parámetros
3. Haz clic en "Analizar"
4. Revisa los resultados básicos

### 3. Análisis Avanzado
1. Haz clic en "Análisis Avanzado"
2. Selecciona el tipo de análisis
3. Espera los resultados
4. Interpreta los gráficos y estadísticas

### 4. Aprendizaje
1. Haz clic en los iconos ℹ️
2. Lee las explicaciones educativas
3. Estudia el código MATLAB
4. Experimenta con diferentes parámetros

## 📱 Compatibilidad

### Navegadores Soportados
- **Chrome**: Versión 80+
- **Firefox**: Versión 75+
- **Safari**: Versión 13+
- **Edge**: Versión 80+

### Dispositivos
- **Desktop**: Experiencia completa
- **Tablet**: Funcionalidad completa con interfaz adaptada
- **Móvil**: Funcionalidad básica (se recomienda desktop para análisis avanzados)

### Requisitos del Sistema
- **RAM**: Mínimo 4GB (8GB recomendado)
- **Procesador**: Cualquier procesador moderno
- **Conexión**: Internet para MATLAB Online/ThingSpeak

## 🆘 Soporte y Ayuda

### Recursos Adicionales
- **Documentación MATLAB**: [mathworks.com/help](https://mathworks.com/help)
- **ThingSpeak**: [thingspeak.com/docs](https://thingspeak.com/docs)
- **SweetAlert2**: [sweetalert2.github.io](https://sweetalert2.github.io)

### Contacto
- **Problemas técnicos**: Revisa la consola del navegador
- **Sugerencias**: Documenta el problema con capturas de pantalla
- **Mejoras**: Describe la funcionalidad deseada

---

**¡Disfruta aprendiendo matemáticas con MATLAB! 🎓📊**

