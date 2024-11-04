<h1>textbasedgame</h1>
print(f"bem vindo a floresta!: ")
escolha=input("Vens jogar ZÉ?: ")
if escolha == "s":
  print(f"Vamos começar!")
nome=input("Qual o teu nome ó GOAT?: ")
print(f"{nome}?É mesmo de GOAAAAAAAAAAAAAAAAAAAAAAAAAAAATTTTTTTTTTT ")
caminho=input("Queres mesmo jogar?(s)ou(n): ")
if caminho == "n":
  print("Fim")
  exit()
if caminho == "s":
  print("Encontraste o goblin larilas")
  goblin=input("Queres combate-lo?(s) ou (n): ")
  if goblin == "s":
   print("Mataste o goblin!Ganhaste uma espada!")
  if goblin == "n":
    print("Ele atacoute e morreste!")
lobo=input("Seguiste em frente.Apareceu um lobo,queres lutar com ele?(s)ou(n): ")
if lobo == "s":
    espada=input("Queres usar a espada?(s)ou(n)): ")
if espada == "s":
    print("Mataste o lobo!")
if espada  == "n":
      print("Morreste!")
      exit()
templo=input("Depois de andar por muito na floresta chegas a um templo.Vais entar?(s) ou (n): ")
if templo == "s":

  armadilha=input("Caiste numa armadilha!Pra sair tens de sacrificar a tua espada senão serás esmagado!Vais usar?(s) ou (n): ")
if armadilha == "s":
  print("Sacrificaste a espada mas sobreviveste!")
if armadilha == "n":
  print("Falhaste na missão")
  exit()
armadilha2=input("Encontraste mais uma armadilha!É um lago de labo o caminho desce e sobe tens de escolher o tempo certo pra passar!Escolhes (5) ou (3)?: ")
if armadilha2 == "3":
  print("Passaste pela armadilha!Como recompensa recebeste um bastão que amplia e encolhe!")
armadilha3=input("A proxima armadilha é um buraco sem fundo!O teu bastão fica comprido mas fica fino,mas fica mais grosso e pequeno qual escolhes pra passar o buraco?Alternativas (g)ou(f): ")
if armadilha3 == "g":
  print("O teu bastão não esticou o suficiente e caiste no buraco sem fundo!MORRESTE!")
  exit()
if armadilha3 == "f":
  print("Conseguiste chegar ao outro lado!")
boss=input("Chegaste ao boss final!Vais ter de usar o bastão pra combatelo!Vais ampliar ou encolher o bastão(e)ou(a): ")
if boss == "e":
  print("O teu bastão não chega a ele e ele cortate ao meio!Morreste!")
if boss == "a":
  print("O teu bastão acertou-lhe no olho!")
  fugir=input("Ele está distraido vais fugir?(s)ou(n): ")
if fugir == "s":
  print("Fugiste e ganhaste uma espada que vale 1 bilhão")
if fugir == "n":
  print("O mosntro voltou a ação e matoute!")
  exit()
venda =input("Vais vender a espada ao ronaldo?(s)ou(n)ou esperar e vender depois(e): ")
if venda == "s":
  print("Ficaste rico e as tuas proximas 3 gerações da tua familia vão ser milionarias!Acabaste!")
if venda == "n":
  print("Ficaste pobre e morreste em  5 anos!Acabaste!")
if venda == "e":
  print("Enquanto aguardavas morreste de cancro!")
  exit()
