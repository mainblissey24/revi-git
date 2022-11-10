# Welcome to GitHub Desktop!



This is your README. READMEs are where you can communicate what your project is and how to use it.



Write your name on line 6, save it, and then head back to GitHub Desktop.



## outras branchs

para cada nova funcionalidade ou correção de bugs é criada uma nova branch



### Padrões para criar nomes de branchs

"!IMPORTANTE! Nomes de branchs não tem acento nem ç

Para a correção de bugs: fix_identificacao_do_bug

exemplo: fix_botao_de_login, fix_cor_do_cabecalho



Para novas funcionalidades:

feat_identificacao_da_novo_funcionalidade

Exemplo: feat_integracao_com_google, feat_nova_tela_de_contato



Para atualizar documentação: doc_identificacao_da_aletaracao

exemplo: doc_adicionado_nova_imagem



Para criação/alteraçaõ de tarefas que não interfere no código:

chore_identificacao_da_modificacao

exemplo: chore_atualizacao

exemplo: chore_atualizado_a_versao_do_banco

## Criação de novas branchs
git checkout -b nome_da-nova_branch
Exemplo: git checkout -b fix_botao_da_tela_login
Obs: O ideal é sempre criar as branchs a partir da main

### Listar as branchs existentes
git branch list

### Trocar de branch
git switch nome_da_branch_que_deseja_entrar
Exemplo 01: git switch fix_botao_da_tela_login

### Excluir uma branch
git branch -D nome_da_branch_que_deseja_fechar
Exemplo: git branch -D fix_botao_da_tela_login