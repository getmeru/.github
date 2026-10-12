## Qué cambia

<!-- Una o dos frases. Qué hace el cambio y por qué. Enlace al ticket si existe. -->

## Cómo se probó

<!-- Qué corriste y qué viste: tests unitarios, prueba manual, ambiente. Si no se probó, dilo. -->

## Riesgo y reversión

<!-- ¿Toca dinero, datos de usuarios, autenticación, proveedores? ¿Cómo se revierte: redeploy anterior, feature flag, migración reversible? -->

## Checklist

- [ ] No incluye secretos, llaves ni datos de clientes
- [ ] Si hay migración de base de datos, es reversible o tiene plan de reversión
- [ ] Si cambia un contrato (API, evento, webhook), avisé a quienes lo consumen
