from colorama import init, Fore, Back, Style


init()

print(Fore.RED + "Цей текст червоний")
print(Back.YELLOW + "Фон цього тексту жовтий")
print(Style.BRIGHT + "Цей текст яскравий")
print(Style.RESET_ALL + "Скинуто до стандартного вигляду")
