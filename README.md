# 🖼️ Conversor WebP - Sin Pérdida de Calidad

Herramienta web 100% cliente-side para convertir imágenes JPG y PNG a formato WebP manteniendo la máxima calidad posible. Sin necesidad de servidor, toda la conversión se realiza en tu navegador.

![Conversor WebP](https://img.shields.io/badge/WebP-Converter-00ffa3?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Privacy](https://img.shields.io/badge/Privacy-First-00ffa3?style=for-the-badge)

## ✨ Características

- 🎯 **Conversión sin pérdida**: Calidad 100% (lossless) disponible
- 🚀 **100% cliente-side**: Tus imágenes nunca salen de tu navegador
- 📦 **Descarga en lote**: Exporta todas las imágenes convertidas en un archivo ZIP
- 🎨 **Interfaz moderna**: Diseño elegante con animaciones fluidas
- 📊 **Estadísticas en tiempo real**: Visualiza el espacio ahorrado
- 🖱️ **Drag & Drop**: Arrastra tus imágenes directamente
- 📱 **Responsive**: Funciona perfectamente en móviles y tablets
- ⚡ **Sin dependencias externas**: Solo HTML, CSS y JavaScript vanilla (+ JSZip para comprimir)

## 🎯 Calidad de Conversión

| Calidad | Descripción | Uso Recomendado |
|---------|-------------|-----------------|
| **100%** | Sin pérdida (lossless) | Fotografía profesional, imágenes médicas, archivos originales |
| **95-99%** | Prácticamente imperceptible | Sitios web premium, portfolios, e-commerce |
| **85-94%** | Alta calidad | Blogs, redes sociales, web general |
| **70-84%** | Buena calidad | Miniaturas, imágenes secundarias |

## 🚀 Uso

### Opción 1: Usar directamente desde GitHub Pages

Visita: `https://tu-usuario.github.io/webp-converter`

### Opción 2: Descargar y usar localmente

1. Descarga el archivo `webp-converter.html`
2. Ábrelo en tu navegador (Chrome, Firefox, Safari, Edge)
3. ¡Listo para usar!

### Opción 3: Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/webp-converter.git
cd webp-converter
# Abre webp-converter.html en tu navegador
```

## 📖 Cómo Usar

1. **Selecciona las imágenes**:
   - Arrastra y suelta tus archivos JPG/PNG en la zona de carga
   - O haz clic para seleccionarlas desde tu explorador de archivos

2. **Ajusta la calidad** (opcional):
   - Usa el slider para configurar la calidad de 1% a 100%
   - 100% = conversión sin pérdida (recomendado)

3. **Convierte**:
   - Haz clic en "Convertir a WebP"
   - Espera a que se complete el proceso

4. **Descarga**:
   - Haz clic en cualquier imagen para descargarla individualmente
   - Usa "Descargar Todo (.zip)" para obtener todas las imágenes en un archivo comprimido

## 💡 ¿Por Qué WebP?

WebP es un formato de imagen moderno desarrollado por Google que ofrece:

- **Menor tamaño**: 25-35% más pequeño que JPG/PNG con la misma calidad
- **Soporte de transparencia**: Como PNG, pero con mejor compresión
- **Soporte de animación**: Como GIF, pero más eficiente
- **Amplia compatibilidad**: Soportado por todos los navegadores modernos (95%+ de usuarios)

### Comparativa de tamaño (promedio)

```
Imagen Original (JPG): 1.2 MB
Imagen WebP (100%):    850 KB  (-29%)
Imagen WebP (95%):     425 KB  (-65%)
Imagen WebP (85%):     280 KB  (-77%)
```

## 🔒 Privacidad y Seguridad

- ✅ **Sin servidor**: Todo el procesamiento ocurre en tu navegador
- ✅ **Sin subidas**: Tus imágenes nunca se envían a ningún servidor
- ✅ **Sin cookies**: No rastreamos ni almacenamos información
- ✅ **Sin analytics**: Respetamos completamente tu privacidad
- ✅ **Open source**: Código 100% auditable

## 🛠️ Tecnologías Utilizadas

- **HTML5 Canvas API**: Para la manipulación de imágenes
- **Vanilla JavaScript**: Sin frameworks, rendimiento óptimo
- **JSZip**: Para crear archivos ZIP con múltiples imágenes
- **CSS3**: Animaciones y diseño responsive

## 🌐 Compatibilidad de Navegadores

| Navegador | Versión Mínima |
|-----------|----------------|
| Chrome    | 32+            |
| Firefox   | 65+            |
| Safari    | 14+            |
| Edge      | 18+            |
| Opera     | 19+            |

## 📝 Notas Técnicas

### Conversión Lossless (Sin Pérdida)

Cuando seleccionas 100% de calidad, la conversión es **lossless** (sin pérdida), lo que significa:

- Los píxeles de la imagen resultante son idénticos a la original
- Ideal para fotografía profesional, diseño gráfico, y archivos master
- Aún así obtienes una reducción de tamaño de 15-30% comparado con PNG

### Limitaciones

- El tamaño máximo de imagen depende de la memoria disponible en tu navegador
- La conversión puede tardar más en imágenes muy grandes (>10 MB)
- Archivos RAW deben convertirse primero a JPG/PNG

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Si quieres mejorar este proyecto:

1. Fork el repositorio
2. Crea una rama para tu feature (`git checkout -b feature/amazing-feature`)
3. Commit tus cambios (`git commit -m 'Add amazing feature'`)
4. Push a la rama (`git push origin feature/amazing-feature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## 🙏 Agradecimientos

- [JSZip](https://stuk.github.io/jszip/) - Para la funcionalidad de ZIP
- [Google WebP](https://developers.google.com/speed/webp) - Por el formato WebP
- La comunidad de desarrolladores web

## 📧 Contacto

¿Preguntas? ¿Sugerencias? Abre un [issue](https://github.com/tu-usuario/webp-converter/issues)

---

⭐ Si te ha sido útil, ¡considera darle una estrella al repositorio!

**Hecho con ♥ para la comunidad de desarrolladores**
