# 🚀 Pereira Tech Talks.

Este es el repositorio web oficial de [pereiratechtalks.com](https://pereiratechtalks.com), una comunidad vibrante de profesionales, desarrolladores e investigadores dedicados a compartir conocimiento sobre tecnología.

![Pereira Tech Talks Banner](readme-banner.png)

## 🌟 Acerca del Proyecto.

Pereira Tech Talks es una iniciativa que busca fomentar el intercambio de ideas y experiencias en el mundo de la tecnología. Nuestra plataforma web es el punto de encuentro para nuestra comunidad, donde compartimos eventos, recursos y contenido valioso.

## 🤝 Cómo Contribuir

¡Nos encanta recibir contribuciones de la comunidad! Si quieres aportar, aquí tienes algunas formas de hacerlo:

1. **Reportar bugs**: Si encuentras algún error, por favor crea un issue detallando el problema.
2. **Sugerir mejoras**: Tienes ideas para mejorar el sitio? Compártelas a través de los issues.
3. **Crear pull requests**: ¿Quieres agregar una nueva funcionalidad o corregir algo? ¡Genial! Sigue estos pasos:
   - Haz fork del repositorio
   - Crea una nueva rama (`git checkout -b feature__amazing_feature`)
   - Haz commit de tus cambios (`git commit -m 'Add some Amazing Feature'`)
   - Push a la rama (`git push origin feature__amazing_feature`)
   - Abre un Pull Request

## 🛠 Configuración del Proyecto

Puedes ejecutar el proyecto localmente de dos formas:

### 1. Usando VSCode containers

#### Pre requisitos

- Instalar Docker: [Link](https://docs.docker.com/engine/install/)
- Instalar Visual Studio Code: [Link](https://code.visualstudio.com/download)
- Instalar "Dev Containers" plugin en Visual Studio Code: [Link](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- Crear una carpeta ".devcontainer". Crearla como una copia de la carpeta ".devcontainer_example".
- Una vez dentro de VSCode, podemos encontrar la opción para abrir en container todo el repositorio, usando el plugin "Dev Containers".

- Finalmente una vez abierto el proyecto dentro del contenedor, podemos ir a la terminal e instalar dependencias y levantar el proyecto:

```
npm install
npm run dev
```

### 2. Instalando nodejs y npm localmente

- Instalar NodeJs: [Link](https://nodejs.org)
- Instalar npm: [Link](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)

- Navegar al folder del proyecto en una terminal y ejecutar:

```
npm install
npm run dev
```

## Comandos para testing y mantenibilidad

A continuación encontrarás algunos comandos importantes a la hora de contribuir al proyecto, que debes ejecutar antes de subir nuevos cambios al proyecto:

Verificar linters:

```
npm run eslint:fix
```

Verificar formato de código:

```
npm run prettier:fix
```

Validar pruebas:

```
npm run test
```

## 📜 Lineamientos de Contribución

Para mantener la calidad y consistencia del proyecto, te pedimos que sigas estos lineamientos:

1. Sigue las convenciones de código existentes en el proyecto.
2. Asegúrate de que tu código esté bien documentado.
3. Escribe pruebas para las nuevas funcionalidades cuando sea posible.
4. Mantén tus pull requests enfocados en una sola funcionalidad o corrección.

## 📝 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

## 📞 Contacto

Si tienes preguntas o sugerencias, no dudes en unirte a nuestra comunidad en telegram y seguirnos en nuestras diferentes redes sociales:

- [Comunidad en Telegram](https://t.me/PerTechTalks)
- [Comunidad en Whatsapp](https://chat.whatsapp.com/EzYAadvUWyVBHt3m1FU77U)
- [Website](https://www.pereiratechtalks.com/)
- [X - @PerTechTalks](https://x.com/pertechtalks)
- [Instagram](https://www.instagram.com/pertechtalks)
- [Facebook](https://www.facebook.com/PerTechTalks)
- [LinkedIn](https://www.linkedin.com/company/35508463/)
- [Linktr](https://linktr.ee/pertechtalks)
- Email: pereiratechtalks@gmail.com

---

¡Gracias por ser parte de Pereira Tech Talks! Juntos estamos construyendo una comunidad tecnológica más fuerte y colaborativa.
Pequeño cambio para probar el workflow

is just a changePequeño cambio para probar el workflow
