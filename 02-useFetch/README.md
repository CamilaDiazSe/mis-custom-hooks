# useFetch hook

Custom hook para traer datos de una api

Ejemplo de uso: 

```
    const url = "endpoin de una api";
    const state = useFetch(url);
    const {data:null, loading:true, error:null} = state;
```