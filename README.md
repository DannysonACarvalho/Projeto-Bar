# Projeto-Bar
Lista de produtos

print('OLÁ, SEJA BEM VINDO AO BAR DO JOTA!')
print('')

codigo_bebidas = ['CERVEJAS:',
                  '',
                  'Amstel 269ml = 1',
                  'Brahma Duplo 350ml = 2',
                  'Brahma Duplo 600ml = 3',
                  'Corona 330ml = 4',
                  'Heineken LongNeck = 5',
                  'Heineken 600ml = 6',
                  'Heineken zero alcool 350ml = 7',
                  'Itaipava 350ml = 8',
                  'Skol 350ml = 9 ',
                  'Skol 269ml = 10 ',
                  'Skol 600ml = 11 ',
                  'Skol 1L = 12',
                  'Original 600ml = 13',
                  '',
                  'DOSES:',
                  '',
                  '51 = 14',
                  '51 Ouro = 15',
                  'Askov = 16',
                  'Bombeiro = 17',
                  'Campari = 18',
                  'Catuaba = 19',
                  'Cinzano = 20',
                  'Contini = 21',
                  'Cynar = 22',
                  'Domecq = 23',
                  'Dreher = 24',
                  'Fernet = 25',
                  'Fogo Paulista = 26',
                  'Jurubeba = 27',
                  'Licor de Cacau = 28',
                  'Menta = 29',
                  'Montilla = 30',
                  'Paratudo = 31',
                  'Piga com Limão = 32',
                  'Pinga com Raiz = 33',
                  'Pinga Mineira = 34',
                  'Pitu = 35',
                  'São Francisco = 36',
                  'São Joao da Barra = 37',
                  'Smirnoff = 38',
                  'Velho Barreiro = 39',
                  'Vinho Cantinho do vale = 40',
                  'Vinho San Tomé = 41',
                  'Whisly Pass Port = 42',
                  'Whisky White Horse = 43',
                  'Xiboquinha = 44',
                  'Ypioca = 45'
                  

                  
                  ]

print('Codigo dos produtos: ')
print('')
print('\n'.join(codigo_bebidas))
print('')
bebidas = { 
           '1': 'Amstel 269ml R$ 3,50',
           '2': 'Brahma Duplo 350ml R$ 5,00',
           '3': 'Brahma Duplo 600ml R$ 12,00',
           '4': 'Corona 330ml R$ 7,50',
           '5': 'Heineken LongNeck R$ 7,50',
           '6': 'Heineken 600ml R$ 14,00',
           '7': 'Heineken Zero Alcool 350ml R$ 7,00',
           '8': 'Itaipava 350ml R$ 4,00',
           '9': 'Skol 350ml R$ 4,00',
           '10':'Skol 269ml R$ 3,50',
           '11': 'Skol 600ml R$ 8,00',
           '12': 'Skol 1L    R$ 12,00',
           '13': 'Original 600ml R$ 12,00'
} 

bebida_usuario = input('DIGITE O CÓDIGO DA BEBIDA: ')

if bebida_usuario in bebidas:
    print(f'{bebidas[bebida_usuario]}')

else:
   print('Desculpe não temos a informação sobre a bebida')
