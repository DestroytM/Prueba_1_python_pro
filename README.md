# Prueba_1_python_pro
palabras={
  "Hi":"Hola"
  "Ok":"Si"
  "Cringe":"Pena ajena"
  "Understand":"Entender"
}
palabra=input("Escribe una palabra que no entiendas con mayúscula inicial")
if palabra in palabras.keys():
  print(palabras[palabra])
else:
  print("Todavía no tenemos la palabra que buscas......., pero estamos trabajando en ella")
