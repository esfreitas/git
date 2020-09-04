Passos para fazer um commit

passo 0
	consultar status opcional
1 passo
	editar os arquivos
2 passo
	git add (nome do arquivo, . ou *extensão)
3 passo
 	consultar status
4 passo
	git commit -m "incluir a descrição do commit"


Comandos de log do git

git diff --stagged
	Mostra os arquivos alterados e as alterações feitas
git log
	lista todos os commits que foram feitos
git log -p 
	mostra o diff junto com o log
git log -p -1 \\ pode ser qualquer número
	mostra o diff junto com o log e o busca apenas o quantidade de commit informado, neste caso buscaria apenas o último commit feito.
