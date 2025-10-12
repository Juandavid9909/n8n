# ¿Qué es?

Es una plataforma de automatización de flujos de trabajo low-code pero extensible con código. Permite conectar APIs, bases de datos, y herramientas SaaS. Funciona On-Premise o en la nube y es Open Source.


# Ejecutar n8n localmente

Para ejecutar n8n con node, debemos ejecutar el siguiente comando:

```bash
npx n8n
```

Y para ejecutarlo directamente en una imagen de Docker, podemos hacer lo siguiente:

```bash
docker volume create n8n_data

docker run -it --rm --name n8n -p 5678:5678 -v n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n
```
