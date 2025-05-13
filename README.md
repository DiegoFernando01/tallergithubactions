<p align='center'>
  <img width='200' heigth='225' src='https://user-images.githubusercontent.com/62605744/171186764-43f7aae0-81a9-4b6e-b4ce-af963564eafb.png'>
</p>

# 🚀 GitHub Actions

## 📋 Descripción

Este repositorio contiene un proyecto de demostración utilizado en un taller sobre GitHub Actions, una herramienta poderosa para automatizar flujos de trabajo de desarrollo. El proyecto consiste en una simple función JavaScript que suma dos números, junto con pruebas automatizadas utilizando Jest.

## 🛠️ Estructura del Proyecto

- `sum.js` - Función de suma simple
- `sum.test.js` - Prueba unitaria para la función de suma
- `.github/workflows/main.yaml` - Configuración de GitHub Actions

## 🔄 GitHub Actions

Este proyecto incluye un flujo de trabajo de CI (Integración Continua) configurado para:

- Ejecutarse automáticamente en cada Pull Request hacia la rama master
- Utilizar Node.js v14
- Instalar dependencias
- Ejecutar pruebas con Jest

## 🧪 Pruebas

Para ejecutar las pruebas localmente:

```bash
npm install
npm test
```

## 📚 Aprendizaje

Este taller demuestra cómo:

- Configurar flujos de trabajo básicos en GitHub Actions
- Automatizar pruebas en un proyecto JavaScript
- Implementar integración continua en un repositorio de GitHub

## 🔗 Referencias

- [Documentación oficial de GitHub Actions](https://docs.github.com/es/actions)
- [Documentación de Jest](https://jestjs.io/docs/getting-started)
