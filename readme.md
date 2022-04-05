# Projeto Loteca
Este é um projeto de simulador de loteria, onde o usuário digita 6 números e realiza um sorteio de outros 6 números. No final é verificado quantos números ele acertou.

## Tecnologias utilizadas
- **HTML**: estrutura do site
- __CSS__: estilização do site
- *_JS_*: funções do site
- ~~BootStrap~~: não foi utilizado

### Melhorias possíveis
1. [X] Subir para GitHubPages
2. [ ] Alterar os Alerts
3. [ ] Utilizar o BootStrap
4. [ ] Deixar responsivo

### Disponibilizado em
[GitHubPage](https://zeinabtermos.github.io/loteca/)

### Prints da tela

| ID | Primeira tela | Segunda tela | 
|----|----------------|-----------------|
| 1  | loteca Limpa  | loteca Preenchida |
| 2  | ![image](https://user-images.githubusercontent.com/99741162/161781609-d9de0559-7fb0-4378-a3ad-65ac06c588b4.png) | ![image](https://user-images.githubusercontent.com/99741162/161782478-8233333c-5208-4c88-97af-9b180ff77400.png) |


#### Função Principal
```
function sorteio() {
    cont=0
    while (cont < 6) {
        let num = Math.random() * 60 //math.random sorteia um num entre 0 e 1, e multiplica por 60 que é o máximo
        num = Math.ceil(num) //arredonda o número pra cima
        if (!numSort.includes(num)) { //ele verifica se já existe o número
            numSort[cont] = num
            console.log(numSort)
            cont++
        }
    }
```

#### comando git
Para iniciar o projeto
```
git init
```
