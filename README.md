# Memoria-Dinámica
class memDinamica:
    def __init__(self):
        self.frutas = []

    def agregar_fruta(self, fruta):
        self.frutas.append(fruta)

    def eliminar_fruta(self, indice):
        del self.frutas[indice]

    def imprimir_frutas(self):
        print(self.frutas)


if __name__ == "__main__":
    est_dmem_dinamica = memDinamica()
    est_dmem_dinamica.agregar_fruta("Mango")
    est_dmem_dinamica.agregar_fruta("Manzana")
    est_dmem_dinamica.agregar_fruta("Banana")
    est_dmem_dinamica.agregar_fruta("Uvas")

    est_dmem_dinamica.imprimir_frutas()
    est_dmem_dinamica.eliminar_fruta(0)
    est_dmem_dinamica.eliminar_fruta(1)
    est_dmem_dinamica.agregar_fruta("Sandia")
    est_dmem_dinamica.imprimir_frutas()
