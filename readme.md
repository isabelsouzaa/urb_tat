## Georreferenciamento dos acidentes de trânsito - RECIFE-PE

## OBJETIVO GERAL:
Analisar a distribuição espacial dos acidentes de trânsito na cidade de Recife-PE que envolvam pedestres e ciclistas, observando também as zonas de trânsito calmo e ciclovias da cidade.


## BASE DE DADOS:
Foram utilizados dados fornecidos pela prefeitura da cidade de Recife - PE, que continham a descrição detalhada de cada acidente de trânsito ocorrido na cidade para cada ano a partir de 2015. Também foram utilizados arquivos já georreferenciados que continham a localização das ciclovias e pontos de intervenção de trânsito calmo.

## ROTEIRO

Importação
- Extração dos dados dos acidentes ocorridos em cada ano oriundos da CTTU ( Autarquia de Trânsito e Transporte Urbano do Recife) a partir do site oficial da prefeitura da cidade, disponível em: http://dados.recife.pe.gov.br/dataset/acidentes-de-transito-com-e-sem-vitimas
- Separação dos acidentes que forneciam endereço dos demais. Em cada ano, esse número variou entre 40% e 50% de toda população de sinistros. 
Tratamento
- Georreferenciamento dos sinistros oriundos da etapa anterior (latitude e longitude). 
Visualização
- Construção dos mapas atravês do QGis.

## RESULTADOS

- Atropelamentos em 2016 (Linhas verdes são as ciclovias)
![Atrop_2016total](https://user-images.githubusercontent.com/123265569/213933821-ee3b6922-3b04-4ea9-a270-3493ecdc08f2.png)

- Atropelamentos em 2021 com a implementação das áreas de Trânsito Calmo
![Atrop_2021total](https://user-images.githubusercontent.com/123265569/213933835-d18c5046-32e6-4982-86e0-19d867f497bc.png)




















