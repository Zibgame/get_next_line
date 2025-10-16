# 📜 get_next_line — Zibrian Cadinot (École 42)

> Projet de l’**École 42** visant à implémenter une fonction capable de **lire une ligne à la fois** depuis un descripteur de fichier.  
> Ce projet permet de mieux comprendre la gestion des **buffers**, la **mémoire dynamique**, et le fonctionnement bas niveau de la **lecture de fichiers en C**.

---

## 🧠 Objectif du projet

La fonction `get_next_line` doit lire **une seule ligne à la fois** depuis un fichier, une entrée standard ou tout autre descripteur de fichier.  
Elle doit fonctionner correctement **quelle que soit la taille du buffer** et permettre de continuer la lecture là où elle s’était arrêtée.

---

## ⚙️ Prototype de la fonction

```c
char	*get_next_line(int fd);

### 1. Cloner le dépôt
```bash
git clone https://github.com/Zibgame/get_next_line.git
cd libft
