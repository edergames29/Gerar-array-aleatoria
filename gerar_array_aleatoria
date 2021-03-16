#!/usr/bin/env python3
import random

def checar(ar, i):
    #print(ar,i)
    for a in ar:
        if a == i:
            #print(f"{a} é igual a {i}")
            return 0
    #print(f"{i} não está em {ar}")
    return 1

    
def gerar(c):

    arrayale = []

    while True:
        ale = random.randint(0,c)
        if checar(arrayale,ale):
            arrayale.append(ale)

        if(len(arrayale) == c):
            break
            
        
    return arrayale



nume = gerar(100)
print(nume)
print(len(nume))
