# tarea-proyecto
echo 'printf("Hola Mundo\n");' > prog-01.c
echo '## Compilar y Ejecutar\n\nPara compilar el programa, utiliza el siguiente comando:\n\n```bash\ngcc prog-01.c -o prog-01\n```\n\nPara ejecutar el programa:\n\n```bash\n./prog-01\n```' > README-es.md
git add .
git commit -m "Añadir archivo base y README para master"
git checkout -b ingles
echo 'printf("Hello World!!!\n");' > prog-01-ing.c
echo '## Compile and Run\n\nTo compile the program, use the following command:\n\n```bash\ngcc prog-01-ing.c -o prog-01-ing\n```\n\nTo run the program:\n\n```bash\n./prog-01-ing\n```' > README-ing.md
git add .
git commit -m "Añadir programa y README para ingles"

git checkout -b francés
echo 'printf("Salut Monde!!!\n");' > prog-01-fra.c
echo '## Compiler et Exécuter\n\nPour compiler le programme, utilisez la commande suivante :\n\n```bash\ngcc prog-01-fra.c -o prog-01-fra\n```\n\nPour exécuter le programme :\n\n```bash\n./prog-01-fra\n```' > README-fra.md
git add .
git commit -m "Añadir programa y README para francés"

echo '# Multilingual Hello World Program\n\nEste programa simple imprime saludos en varios idiomas.\n\n## Compilar y Ejecutar\n\nPara compilar el programa, utiliza el siguiente comando:\n\n```bash\ngcc prog-01.c -o prog-01\n```\n\nPara ejecutar el programa:\n\n```bash\n./prog-01\n```' > README.md
git add .
git commit -m "Añadir README principal"
