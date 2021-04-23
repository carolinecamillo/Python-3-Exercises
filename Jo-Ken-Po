print(16 * '\033[36m-_\033[m')
print(' \033[33;1mJO KEN PÔ! TENTE VENCER A CPU!\033[m')
print(16 * '\033[36m-_\033[m')
import random
lista = ['papel', 'pedra', 'tesoura']
cpu = random.choice(lista).upper()
user1 = str(input('> > Informe pedra, papel ou tesoura: ')).upper()
user = user1.strip()
print('\nJO... ', end='')
import time
time.sleep(1)
print('KEN... ', end='')
time.sleep(1)
print('PÔ!')
time.sleep(1)
print('\n\033[33mVocê:\033[m', user, end='')
import emoji
if user == 'PAPEL':
    print(emoji.emojize(' :hand:', use_aliases=True))
elif user == 'TESOURA':
    print(emoji.emojize(' :v:', use_aliases=True))
elif user == 'PEDRA':
    print(emoji.emojize(' :punch:', use_aliases=True))
elif user != 'PEDRA' or user != 'TESOURA' or user != 'PAPEL':
    print(emoji.emojize(' :poop:', use_aliases=True))
time.sleep(1)
print('\n\033[36mCPU:\033[m', cpu, end='')
if cpu == 'PAPEL':
    print(emoji.emojize(' :hand:', use_aliases=True))
elif cpu == 'TESOURA':
    print(emoji.emojize(' :v:', use_aliases=True))
elif cpu == 'PEDRA':
    print(emoji.emojize(' :punch:', use_aliases=True))
time.sleep(1)
if user == cpu:
    print('\n> > \033[1;35m{} é igual a {}!\033[m < <'.format(user, cpu))
    print('\n\033[36mCPU:\033[m Empate... Vamos de novo!')
elif user == 'PAPEL' and cpu == 'PEDRA' or user == 'PEDRA' and cpu == 'TESOURA' or user == 'TESOURA' and cpu == 'PAPEL':
    print('\n> > \033[1;32m{} ganha de {}!\033[m < <'.format(user, cpu))
    print('\n\033[36mCPU:\033[m Impossível... Você me venceu...')
elif cpu == 'PAPEL' and user == 'PEDRA' or cpu == 'PEDRA' and user == 'TESOURA' or cpu == 'TESOURA' and user == 'PAPEL':
    print('\n> > \033[1;31m{} ganha de {}!\033[m < <'.format(cpu, user))
    print('\n\033[36mCPU:\033[m Aconteceu o esperado. Eu venci!')
elif user != 'PEDRA' or user != 'TESOURA' or user != 'PAPEL':
    print('\n\033[36mCPU:\033[m Você já jogou isso antes...?')
print('\n (Pressione F6 para jogar novamente)')