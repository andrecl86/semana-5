class ListaPrecios:
    def __init__(self, precios):
        self.precios = precios

    def obtener_menor(self):
        return min(self.precios)

    def obtener_mayor(self):
        return max(self.precios)

# Crear un objeto con la lista de precios
lista = ListaPrecios([50, 75, 46, 22, 80, 65, 8])

# Mostrar el menor y el mayor precio
print("El precio menor es:", lista.obtener_menor())
print("El precio mayor es:", lista.obtener_mayor())
