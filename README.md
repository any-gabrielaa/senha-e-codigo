codigo = int(input('Digite o código de usuário: ')) #pede o código para o usuário
if codigo == 1234: #compara o código digitado com o código certo
    senha = int(input('Digite a senha: ')) #pede a senha para o usuário dentro do primeiro SE
    if senha == 9999: #cria um novo SE, comparando agora a senha digitada e a certa
        print('Acesso permitido!') #libera o acesso
    else:
        print('Senha incorreta!') #para quando a senha for incorreta, porém o código correta
else:
    print('Usuário inválido!') #para quando o código for incorreto
