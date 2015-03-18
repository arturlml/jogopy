import random
you= 0
sorteio_pontuacao= 0
while (you!=3) or (sorteio_pontuacao!=3):
    you_escolha= input('escolha uma opcao: papel;pedra;tesoura;spock;lagarto ')
    x = 'papel' 
    y = 'pedra'
    z = 'tesoura'
    w = 'spock'
    v = 'lagarto' 
    lista = [v,w,x,y,z]
    sorteio = random.choice(lista)
    print ('o elemento sorteado foi: ',sorteio)
    if (you_escolha=='spock') and (sorteio=='tesoura'):
        print ('vc ganhou')
        you=you+1
        sorteio_pontuacao=0
    elif you_escolha=='pedra' and sorteio=='tesoura':
        print ('vc ganhou')
        you=you+1
        sorteio_pontuacao=0
    elif you_escolha=='tesoura' and sorteio=='lagarto':
        print ('vc ganhou')
        you=you+1
        sorteio_pontuacao=0
    elif you_escolha=='pedra'and sorteio=='lagarto':
        print ('vc ganhou')
        you=you+1
        sorteio_pontuacao=0
    elif you_escolha== 'papel' and sorteio=='pedra':
        print ('vc ganhou')
        you=you+1
        sorteio_pontuacao=0
    elif you_escolha=='spock' and sorteio=='pedra':
        print ('vc ganhou')
        you=you+1
        sorteio_pontuacao=0
    elif you_escolha=='lagarto' and sorteio=='spock':
        print ('vc ganhou')
        you=you+1
        sorteio_pontuacao=0
    elif you_escolha=='papel' and sorteio=='spock':
        print ('vc ganhou')
        you=you+1
        sorteio_pontuacao=0
    elif you_escolha=='tesoura' and sorteio=='papel':
        print ('vc ganhou')
        you=you+1
        sorteio_pontuacao=0
    elif you_escolha=='lagarto' and sorteio=='papel':
        print ('vc ganhou')
        you=you+1
        sorteio_pontuacao=0
    elif you_escolha==sorteio:
        print ('empate')
        you=you+0
        sorteio_pontuacao=sorteio_pontuacao+0
    else :
        print ('vc perdeu')
        you=0
        sorteio_pontuacao=sorteio_pontuacao+1
    print("you",you)
    print("computador",sorteio_pontuacao)
print('fim')
