# ft_strace

## 42 project - strace command

strace est un outil de débogage sous Linux pour surveiller les appels système utilisés
par un programme, et tous les signaux qu’il recoit, similaire å l’outil truss sur les autres
systèmes Unix. Il a été rendu possible grace à une fonctionnalitée du noyau Linux appelée
ptrace


• Vous devez être sous une VM avec un noyau linux > 3.4, (Ubuntu 14.10)
• Vous pourrez en bonus, faire l’option -c et la gestion du PATH, ce sont les seules bonus valables.
• L’executable devra se nommer ft_strace

• Vous n’avez pas le droit d’utiliser les options suivantes :
    ◦ PTRACE_TRACEME
    ◦ PTRACE_ATTACH

• Vous devez gérer les binaires 64 ET 32 bits