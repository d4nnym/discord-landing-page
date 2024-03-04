# Astro Starter Kit: Basics

## Instalación y configuración de shadcn/ui

[Ir a la página oficial de Tailwind](https://tailwindcss.com/docs/guides/astro)

1. **Crear proyecto**

Comience creando un nuevo proyecto Astro:

```bash
npm create astro@latest
```

2. Añade React a tu proyecto

Instale React usando **`Astro CLI`**:

```bash
npx astro add react
```

3. Añade Tailwind CSS a tu proyecto

Ejecute el **`astro add`** comando para instalar ambos **`tailwindcss`** y generar un archivo. **`@astro/tailwindtailwind.config.cjs`**

```bash
npx astro add tailwind
```


4. Editar el archivo tsconfig.json

Agregue el siguiente código al **`tsconfig.json`** archivo para resolver las rutas:

```json
{
  "compilerOptions": {
    // ...
    "baseUrl": ".",
    "paths": {
      "@/*": [
        "./src/*"
      ]
    }
    // ...
  }
}
```

5. Ejecute la CLI
   
Ejecute el **`shadcn-ui`** comando init para configurar su proyecto:

```bash
npx shadcn-ui@latest init
```






