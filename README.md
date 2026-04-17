# 🎸 El Ritual del Tono | Frontend

**El Ritual del Tono** es la plataforma definitiva para los guitarristas que buscan descubrir exactamente qué equipamiento utilizan sus ídolos para lograr ese sonido inconfundible. Desde el gear de leyendas internacionales hasta los arquitectos sónicos del rock nacional.

⚙️ **Repositorio del Backend:** [el-ritual-del-tono-backend](https://github.com/tiagocollado/el-ritual-del-tono-backend)

> 💡 **Nota:** Este repositorio contiene únicamente el código del **Frontend**. La aplicación se alimenta de una API REST propia construida con Node, Express y MongoDB.

---

## 🚀 Stack Tecnológico (Frontend)

* **Framework:** [Next.js](https://nextjs.org/)
* **Librería UI:** [React](https://react.dev/)
* **Estilos:** Tailwind CSS
* **Diseño UI/UX:** Diseñado desde cero para ofrecer una experiencia inmersiva y oscura ("Donde todo empieza").

---

## ✨ Funcionalidades Principales

La aplicación está diseñada para conectar la música con la tecnología, permitiendo a los usuarios navegar entre artistas y su equipamiento:

### 👤 Base de Datos de Artistas
Perfiles dedicados a leyendas de la guitarra con su biografía y estilo definido:
* *Internacionales:* Jimi Hendrix, David Gilmour, Kurt Cobain, etc.
* *Nacionales:* Skay Beilinson, Gustavo Cerati, Luis Alberto Spinetta, etc.

### 🎛️ Catálogo de Equipamiento ("Gear")
Un inventario completo y filtrable donde los usuarios pueden explorar el hardware que define el tono de sus héroes:
* **Filtros Dinámicos:** Categorización por *Todos, Pedales, Guitarras, Amplificadores*.
* **Fichas de Producto:** Detalles y precios de ítems icónicos como el *Electro-Harmonix Big Muff Pi*, *Vox V847 Wah* o la clásica *Fender Stratocaster*.

### 🛒 Interacción de Usuario
* **Carrito de Compras:** Sistema funcional para ir agregando el equipamiento deseado, ver el resumen y gestionar los productos seleccionados.

---

## 🛠️ Instalación y Ejecución Local

Para ejecutar el frontend en tu entorno de desarrollo, es necesario que también tengas corriendo el [servidor backend](https://github.com/tiagocollado/el-ritual-del-tono-backend) para que la base de datos responda correctamente.

1.  **Clonar el repositorio:**
    ```bash
    git clone [URL_DE_ESTE_REPOSITORIO]
    ```

2.  **Navegar al directorio:**
    ```bash
    cd el-ritual-del-tono-frontend
    ```

3.  **Instalar las dependencias:**
    ```bash
    npm install
    ```

4.  **Configurar Variables de Entorno:**
    Crear un archivo `.env.local` en la raíz del proyecto para conectar con la API local:
    ```env
    NEXT_PUBLIC_API_URL=http://localhost:PUERTO_DEL_BACKEND/api
    ```

5.  **Iniciar el servidor de desarrollo:**
    ```bash
    npm run dev
    ```

6.  **Visualizar:**
    Abrir [http://localhost:3000](http://localhost:3000) en el navegador para comenzar a explorar.

---
*Diseñado y desarrollado por **Tiago Collado**.*