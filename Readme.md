Estudo sobre Git e Github

* site para download Git:

	https://git-scm.com/
	
* configurar git
	
	*Username
		git config --global user.name "HLAM"

	*email
		git config --global user.email "hemilioaraujo@gmail.com"
	
	*editor padrão(se não configurado ele utiliza vim)
		git config --global core.editor (emacs,vim)
	
	*exibir configurações utilizadas
		git config chave		chave = user.name, user.email, core.editor
	
		git config --list		exibe todas as configurações

* gerenciando pastas projeto
		
	*criar pasta para salvar arquivos do projeto
		
		mkdir - comando criar pastas
		
		mkdir nome da pasta
	
	*acessar diretórios ou retornar para diretórios anteriores
	
		comando cd ou dir
		
		*acessar diretórios
		
			cd nome da pasta
			
		*retornar
		
			cd retorna para diretório raiz
			cd .. retorna para diretório anterior
	
	*inicializar repositório(monitorar alterações do diretório)
		
		git init
	
	*exibir diretórios ou arquivos existentes
	
		ls -la  exibe diretórios
		ls 		exibe arquivos
		
	*diretório .git contém todos os dados sobre o repositório
	
* editar arquivos com vim

	vim nome do arquivo.extenção
	
	i - insert
	:w - escrever(salvar)
	:q - sair
	
* status do arquivo no repositório

	*untracked - arquivo recém adicionado no repositório mas o 
		git ainda não conhece nenhuma versão deste arquivo.
	
	*unmodified - arquivo recém adicionado no git porém nunca modificado.

	*modified - arquivo já modificado anteriormente.
	
	*staged - momento em que é criada a versão do arquivo(commit).
		Quando é realizado o commit, o arquivo volta para o modo de unmodified.

* comandos git


	*git status - exibe o status do repositório(em qual branch(diretório), se existe algum commit pendente)
	
	*clear - limpa prompt
	
	bunda
