#Nome: Cícera Bruna Silva de Sousa. 
#Atividade n• 4

habituacao = input("O animal está habituado? (S/N) ").upper()

#OBS: Nesse caso t está em segundos

def Fase1() :
    acertou= 0
    t = 0
    while acertou < 20 or t < 1800:
        som1 = input("O som 1 tocou? (S/N) ").upper()
        som2 = input("O som 2 tocou? (S/N) ").upper()

        if som1 == 'S' and som2 == 'S':
            print('Houve um erro técnico, o tempo gasto não será contabilizado')

        elif som1 == 'S' and som2 == 'N':
            barra_esquerda = input("O animal tocou na barra esquerda? (S/N): ").upper()
            if barra_esquerda == 'S':
                print('O animal ganhou 0,5ml de rec')
                acertou =+ 1
                t =+ 36
            else:
                print('O animal não ganhou nada')
                t =+ 36


        elif som1 == 'N' and som2 == 'S':
            barra_direita = input("O animal tocou na barra direita? (Sim/Não): ").upper()
            if barra_direita == 'S':
                print('O animal ganhou 0,5ml de rec')
                acertou =+ 1
                t =+ 36
            else:
                print('Não ganhou nada')
                t =+ 36


        else:
            print('Nenhum som foi tocado, toque algum som')

    else:
        print('O experimento seguirá para a próxima fase')
            

if habituacao == 'S':
    distancia = int(input("Qual a distância, em centímetros, que o animal iniciou o movimento? "))
    chegou = input("O animal chegou na distância do experimento? (S/N): ").upper()
    while chegou == 'N':
        caminhou = input('O animal caminhou em direção as barras? (S/N): ').upper()
        if caminhou == 'S':
            print('O animal ganhou 0,5ml de suco')
        else:
            print('O animal continua parado')
        chegou = input("O animal chegou na distância do experimento? (S/N): ").upper()
    else:
        Fase1()
else:
    print('O animal não está habituado para o experimento. Faça as sessões de habituação antes do projeto')
