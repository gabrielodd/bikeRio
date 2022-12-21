# Bike Rio

## Visite em

https://gabrielodd.github.io/bikeRio/

## Descrição

Para utilizar o programa, o usuário deverá buscar qualquer local no [Nominatim Search Engine for OpenStreetMap](https://nominatim.openstreetmap.org/ui/search.html) e inserir o link do API que se encontra no topo da página, o programa retorna os bicicletários mais próximos em ordem decrescente de distância. O Ícone dourado mostra o local do usuário no mapa, e os Ícones azuis mostram os locais dos Bicicletários.

O API pode incluir mais de um endereço, o programa utiliza a latitude e longitude que possui a maior importância (normalmente o mais relevante da busca)

Para gerar o mapa e os plot points, foi utilizado o [LeafletJs](https://leafletjs.com/) (Biblioteca Open Source para mapas interativos), a distância é calculado usando a fórmula de haversine, que fornece distâncias entre dois pontos de uma esfera a partir de suas latitudes e longitudes.
