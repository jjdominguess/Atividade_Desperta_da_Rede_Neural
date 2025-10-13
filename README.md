# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href="https://www.fiap.com.br/"><img src="Assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Administração Paulista" border="0" width=40% height=40%></a>
</p>

<br>


# Atividade - Despertar da Rede Neural #


## Grupo
João José Domingues Siva, William Xavier, Murílo Santana, William Ferreira


## 👨‍🎓 Integrantes:
- João José Domingues Siva
- William Xavier
- Murílo Santana
- William Ferreira



## 👩‍🏫 Professores:
### Tutor(a)
- Lucas Gomes
### Coordenador(a)
- André Godoi

---


## 📜 Descrição
  - Esta projeto tem como intensão mostrar o treinamento de um algoritmo visando identificar por meio de uma base de imagem de 32 fotos mais 4 fotos de validação e 4 fotos de teste, tendo dois grupos diferentes, um barco e outro um animal. Ambos nas mesmas proporções.
   - [Drive](https://drive.google.com/drive/folders/1vhr3W9ZUDsXY8vWKU0pXzZJ1k-Ma5Iar?usp=drive_link).

## 📊 Resultados
 - No grupo de identificação do animal, o teste com as epochs em 40 no conjunto das 4 imagens de teste, somente esta <a href="Assets/img-exp9-identificado-37%25.jpeg">imagem </a>foi identificada. Já com as epochs mais elevadas, em 60, 3 das 4 imagens foram identificadas, <a href="Assets/img-exp11-identificada-43%25.jpeg"> primeira </a>, <a href="Assets/img-exp11-identificada-52%25.jpeg"> segunda </a>, <a href="Assets/img-exp11-identificada-58%25.jpeg"> terceira </a>.
 A que possuia 37% de acerto de identificação, subiu para 52% com o aumento das epochs. A única não identificada foi a <a href="Assets/img-n-identificada.jpeg"> imagem</a>.

  - No grupo de identificação da embarcação, o teste feito com 40 epochs no conjunto de 4 imagens de teste duas foram identificadas,  <a href="Assets/img-exp16-identificada-30%25.jpeg"> BarcoB </a> e o <a href="Assets/img-exp16-identificada-39%25.jpeg"> BarcoA </a>. Quando foi elevado o numero de epochs essas imagens aumentaram as porcentagens <a href="Assets/img-exp15-identificada-61%.jpeg"> BarcoA </a>,  <a href="Assets/img-exp15-identificada-68%.jpeg"> BarcoB </a> esse foi identificado <a href="Assets/img-exp15-identificada-31%.jpeg"> barcoC </a> e restando o não identificado <a href="Assets/img-n-identificada-barco.jpeg"> barcoD</a>.

## 🏁 Conclusão
  - Percebe-se que ao aumentar o número de epochs o modelo consegue identificar melhor as imagens, porem deve-se ter cuidado com esse aumento para não causar um overfitting, e caso ocorra alguma alteração de luminosidade para cima ou para baixo o modelo não conseguir identificar.
  
---

## 📁 Estrutura de Pastas

- <b><a href="Assets/">Assets/</a></b>: Imagens do projeto.
- <b><a href="Scripts/">Scripts/</a></b>: Contém o notebook principal.
  - <b><a href="Scripts/JoaoJose_rm564111_pbl_fase4.ipynb">JoaoJose_rm564111_pbl_fase6.ipynb</a></b>: Notebook principal com todo o desenvolvimento, análises e modelos.
- <b><a href="README.md">README.md</a></b>: Apresentação do projeto, com resultados comparativos.


## 🔧 Como executar o código
 - Abrindo o arquivo Notebook no Collab, conterá as instruções para execução do algoritmo.

## 🗃 Histórico de lançamentos

* 1.0.0 - 14/10/2025
    * Versão final do projeto

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>

> Projeto desenvolvido para fins acadêmicos, seguindo boas práticas de ciência de dados e aprendizado de máquina.
