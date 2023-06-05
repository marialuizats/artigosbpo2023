# artigosbpo2023
Instâncias do artigo submetido ao 55° Simpósio Brasileiro de Pesquisa Operacional (SBPO 2023).

# Instâncias

---

Os arquivos aqui encontrados foram os utilizados na execução de testes para o artigo submetido ao SBPO 2023.

Ao todo, são apresentadas cinco instâncias com 500 clientes (endereços) diferentes, onde cada cliente tem o seu respectivo pedido, com os produtos que deverão ser entregues. Além disso, as instâncias apresentam os tipos de veículos analisados, assim como as suas respectivas capacidades. Por fim, temos os estoques dos centros de distribuição para cara tipo de cenário, conforme explicado no artigo.

As informações contidas nos arquivos são detalhadas abaixo.

### Pastas:

- Instances:
    - Cada arquivo corresponde a uma instância diferente;
    - O conteúdo do arquivo é explicado como segue:
        - A primeira linha contém uma lista de listas (matriz de distâncias) que correspondem às distâncias de cada endereço para cada endereço.
        - As duas últimas listas internas correspondem às distâncias de cada centro de distribuição em relação aos clientes.
        - Os dois últimos elementos de cada lista interna correspondem às distâncias do cliente/centro em relação aos dois centros de distribuição selecionados.
- Scenarios-Values:
    - Arquivo Itens-Weight:
        - Lista com valores inteiros onde cada valor corresponde ao peso dos itens disponíveis na instância, 100 itens. Cada posição corresponde a um item, de maneira contínua.
    - Para os demais arquivos, cada um corresponde a uma instância diferente;
    - O conteúdo do arquivo é explicado como segue:
        - Orders:
            - Lista de listas que correspondem aos pedidos dos clientes, para um total de 100 produtos diferentes. Caso o valor seja 0, significa que o cliente não solicitou o produto em questão, enumerado pelo índice da lista. Caso o valor seja superior a zero, corresponde à quantidade de itens do produto solicitados pelo cliente.
        - Vehicles Capacities:
            - Lista de valores inteiros onde cada valor corresponde à capacidade de um veículo, sendo 10000g para os de pequeno porte (Motos), 1200000g para os de médio porte (Carros) e 7500000g para os de grande porte (Vans).
        - Vehicles:
            - Lista de nomes que correspondem ao tipo de veículo utilizado. Para cada posição da lista acima (Vehicles Capacities), a posição correspondente da lista (Vehicles) representa o nome do veículo com a sua respectiva capacidade.
        - Depots Stocks:
            - Depots Stock_Cen1:
                - Lista com duas listas internas que correspondem ao estoque de cada produto (baseado na posição da lista), para os dois centros de distribuição selecionados, dentro do Cenário 1.
            - Depots Stock_Cen2:
                - Lista com duas listas internas que correspondem ao estoque de cada produto (baseado na posição da lista), para os dois centros de distribuição selecionados, dentro do Cenário 2.
            - Depots Stock_Cen3:
                - Lista com duas listas internas que correspondem ao estoque de cada produto (baseado na posição da lista), para os dois centros de distribuição selecionados, dentro do Cenário 3.

Desenvolvedora: Maria Luíza Teixeira Santos.
