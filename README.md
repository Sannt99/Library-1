def calculoIMC (peso,altura):
   IMC = peso / (altura**2)
    
   if IMC > 40.0:
        return "obeso grau 3"
   elif IMC > 35.0:
        return "obeso grau 2"
   elif IMC > 30.0:
        return "obeso grau 1"
   elif IMC > 25.0:
        return 'sobrepeso'
   elif IMC > 18.5:
        return "normal" 
   else:
        return "muito magro"


def iniciaresporte(esporte):
        if esporte == "Corrida":
            return "Inicie correndo 5km por semana"
        elif esporte == "Ciclismo":
            return "Inicie pedalando 10km por semana"
        elif esporte == "Musculação":
            return "Inicie treinando 3 vezes por semana"
        else:
            return "esporte não cadastrado"   
        
def tempo(mes = 4):
   if mes == "0":
       return "tempo não informado"
   elif mes == "1":
        return "tempo curto"
   elif mes == "2":
        return "depende"
   elif mes == "3":
        return "tempo ideal"
