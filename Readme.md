# Archivos Hugo para [https://jardin.windmaker.net](https://jardin.windmaker.net)

# Iniciar servidor Hugo en local

Utilizamos la imagen [base_hugo](https://git.windmaker.net/a-castellano/limani/-/tree/master/base_hugo?ref_type=heads):

```bash
podman run --rm -it   -v ~/Projects/jardin-windmaker-net/:/jardin-windmaker-net   --workdir /jardin-windmaker-net   -p 1313:1313   harbor.windmaker.net/limani/base_hugo  hugo server --bind 0.0.0.0 --baseURL http://localhost:1313
```
