# n8n

- para lanzar contenedor de n8n

```
docker run -it --rm --name n8n -p 5678:5678 -v n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n
```

- ngrok para tunel de dominio publico

```
ngrok http 5678
```


