# 💵 Walletify

**Walletify** es una aplicación full stack para gestionar tu billetera virtual. Permite controlar el saldo disponible, registrar ingresos y gastos, y llevar un seguimiento detallado de tus finanzas personales de forma sencilla y eficiente.

## Características

- **Gestión de saldo**: Visualiza tu saldo disponible.
- **Registro de gastos e ingresos**: Añade, edita o elimina tus gastos e ingresos.
- **Autenticación de usuario**: Inicia sesión y gestiona tus finanzas de forma segura con JWT.
- **Interfaz sencilla**: Una interfaz de usuario limpia y fácil de usar para un control eficiente de tus finanzas.

## Tecnologías
- **Frontend**: Vue.js, Vuetify.
- **Backend**: Node.js, Express.
- **Base de datos**: SQLite.
- **Autenticación**: JWT (JSON Web Tokens).
- **Otros**: Axios, bcryptjs, concurrently.

## Instalación

### Clonación del repositorio

```bash
git clone https://github.com/lucasnbarbero/walletify.git
cd walletify
```

### Instalación de dependencias

Asegúrate de instalar las dependencias tanto para el frontend como para el backend

1. **Frontend**:

```bash
cd frontend
npm install
```

2. **Backend**:

```bash
cd backend
npm install
```

### Ejecución del proyecto

Para correr el proyecto en modo desarrollo (frontend y backend)

```bash
npm run dev
```

Este comando ejecutará ambos servidores simultáneamente utilizando `concurrently`.

### Build para Producción

Si deseas compilar el proyecto para producción:

```bash
npm run build
```

### Ejecutar en Producción

Una vez que hayas construido el proyecto, puedes ejecutarlo en modo producción con:

```bash
npm run start
```

## Estructura del Proyecto

```bash
/WalletTrack
  /frontend         # Proyecto del frontend (Vue.js)
    /src            # Código fuente del frontend
    package.json    # Dependencias y scripts del frontend
  /backend          # Proyecto del backend (Node.js / Express)
    /src            # Código fuente del backend
    package.json    # Dependencias y scripts del backend
  package.json      # Dependencias y scripts globales
  README.md         # Este archivo
```

## Contribución
Si deseas contribuir a este proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/mi-nueva-caracteristica`).
3. Realiza tus cambios y haz commit (`git commit -am 'Agregué una nueva característica'`).
4. Haz push a la rama (`git push origin feature/mi-nueva-caracteristica`).
5. Abre un pull request.

## Licencia

Este proyecto está bajo la licencia MIT - consulta el archivo [LICENSE](./LICENSE) para más detalles.
