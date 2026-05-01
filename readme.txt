**Setup-Anleitung**

1. **VS Code installieren** – beim Setup die Option *"Add to PATH"* anhaken
2. **Python installieren** – ebenfalls *"Add to PATH"* anhaken
3. **Miniconda installieren** – auch hier *"Add installation to my path environment"* aktivieren *(auch wenn der Installer das als "not recommended" markiert)*

Danach im Terminal folgende Befehle ausführen *(setzt Miniconda voraus – kann ein paar Minuten dauern)*:

```
conda env create -f environment.yml
conda activate capstone-2026
```