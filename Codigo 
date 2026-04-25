import time
import os

# Función para limpiar la pantalla
def limpiar():
    os.system('cls' if os.name == 'nt' else 'clear')

# Corazón ASCII
corazon = [
    "    **     **    ",
    "   ****   ****   ",
    "  ******* *******  ",
    "  *************** ",
    "   ************** ",
    "    *********** ",
    "     ******* ",
    "      ***** ",
    "       *** ",
    "        * "
]

# Colores ANSI (para terminal)
ROJO = "\033[91m"
ROSA = "\033[95m"
RESET = "\033[0m"

print("\n" * 3)
print("=" * 50)
print(" " * 12 + "💖 CORAZÓN ANIMADO 💖")
print("=" * 50 + "\n")

# Animación latido
for latido in range(3):
    # Latido 1 (normal)
    for linea in corazon:
        print(f"{ROJO}{linea}{RESET}")
    time.sleep(0.5)
    
    limpiar()
    print("\n" * 3)
    print("=" * 50)
    print(" " * 12 + "💖 CORAZÓN ANIMADO 💖")
    print("=" * 50 + "\n")
    
    # Latido 2 (más grande)
    corazon_grande = [
        "     ***      ***     ",
        "    *****    *****    ",
        "   ******* *******   ",
        "   ******************",
        "    ******************",
        "     ***************  ",
        "      **************  ",
        "       **********    ",
        "        ********     ",
        "         ****        ",
        "          **         "
    ]
    
    for linea in corazon_grande:
        print(f"{ROSA}{linea}{RESET}")
    time.sleep(0.5)
    
    limpiar()
    print("\n" * 3)
    print("=" * 50)
    print(" " * 12 + "💖 CORAZÓN ANIMADO 💖")
    print("=" * 50 + "\n")

print("¡Listo! ❤️")