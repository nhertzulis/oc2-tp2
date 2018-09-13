# Trabajo práctico II
Organización del Computador II - Departamento de Computación, FCEN, UBA - Segundo cuatrimestre 2018

Esto es el esqueleto del TP 2 tal como fue provisto por los docentes de la materia con los siguientes agregados:

- Script `configure` para instalar los paquetes de LaTeX
- `Makefile` para el informe
- Archivo `.gitignore`

## Informe

Para instalar los paquetes (solo necesario una vez):
```
chmod +x configure
sudo ./configure
```

Para generar el PDF:
```
make
```

## Cómo usar este esqueleto en un TP

```
git clone https://github.com/nhertzulis/oc2-tp2.git
cd oc2-tp2
git remote rm origin
git remote add origin git@git.exactas.uba.ar:tu-usuario/tu-proyecto.git
rm README.md
echo '# oc2-tp2' >> README.md
git add -A
git commit -m "Commit inicial"
git push -u origin --all
git push -u origin --tags
```
