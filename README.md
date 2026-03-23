# infraction-calculator

```
The project is an implementation of a traffic speed violation reporting system.
```
```
if(vm <= vmp): #2 e 3. Classificação da Infração e calculo de multa com base na velocidade registrada
    descricao = "Não foi aplicada multas"
else:
    if(vm <= vmp * 1.2):  
        valor_multa = 130.16
        descricao = "Infração leve: multa de R$ 130,16 e nenhum ponto na CNH."
    elif(vm <= vmp * 1.5):  
        valor_multa = 195.23
        descricao = "Infração grave: multa de R$ 195,23 e adição de 5 pontos na CNH."
    else:  
        valor_multa = 880.41
        descricao = "Infração gravíssima: multa de R$ 880,41, adição de 7 pontos na CNH e suspensão imediata do direito de dirigir."
```
