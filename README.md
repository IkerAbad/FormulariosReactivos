# FormulariosReactivos

Aplicación Angular 14 (abril de 2023) con un formulario de registro hecho con formularios reactivos, para practicar validación.

## Qué hay

- Formulario con nombre completo, usuario (de 6 a 20 caracteres), correo, contraseña (de 6 a 40), confirmación de contraseña y casilla de aceptar los términos.
- Validadores de Angular (`required`, `minLength`, `maxLength`, `email`, `requiredTrue`) y un validador propio en `validation.ts` que comprueba que las dos contraseñas coinciden.
- Los errores se muestran al enviar. Si todo es válido, el formulario se escribe en la consola; no se envía a ningún servidor.
- `ng build` compila sin errores. No he abierto la aplicación en un navegador desde aquí.

## Cómo probarlo

```
npm ci
npx ng serve
```

y abre `http://localhost:4200/`.

## Licencia

MIT, ver [LICENSE](LICENSE).

---

# FormulariosReactivos (English)

An Angular 14 app (April 2023) with a sign-up form built with reactive forms, to practice validation.

## What's inside

- A form with full name, username (6 to 20 characters), email, password (6 to 40), password confirmation and a terms checkbox.
- Angular validators (`required`, `minLength`, `maxLength`, `email`, `requiredTrue`) and a custom validator in `validation.ts` that checks both passwords match.
- Errors show on submit. If everything is valid, the form is written to the console; nothing is sent to a server.
- `ng build` compiles without errors. I have not opened the app in a browser from here.

## Trying it

```
npm ci
npx ng serve
```

then open `http://localhost:4200/`.

## License

MIT, see [LICENSE](LICENSE).
