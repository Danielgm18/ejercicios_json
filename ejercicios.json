
import json
with open("documento.json", "r") as read_file:
    data = json.load(read_file)
def ejercicio1():
    d=input("Inserta un deporte:")
    print(f"Estas personas practican {d}")
    for persona in data.values():
        if d in persona["deportes"]:
            print(f"--->{persona['nombres']} {persona['apellidos']}")
def ejercicio2():
    e=int(input("Ingrese la edad minima: " ))
    E=int(input("Ingresa la edad maxima: "))
    print(f"Personas entre {e} y {E}")
    for persona in data.values():
        E2=persona["edad"]
        if e<=E2<=E:
         print(f"--->{persona['nombres']} {persona['apellidos']}")
        
def main():
   ejercicio1()
   ejercicio2()

if __name__ == "__main__":
    main()
