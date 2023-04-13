# Eliza

Eliza chatbot in Spanish under Python.

https://en.wikipedia.org/wiki/ELIZA

## Running

```
python3 eliza.py
```

## Pipe to sayanything

```
python3 eliza.py | tee >(~/Development/go-sayanything/sayanything -k /path/to/googlekeys.json -l="es-ES" -voice="es-ES-Neural2-E")
```
