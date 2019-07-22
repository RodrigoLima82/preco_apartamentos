# Desafio Grupo ZAP - Previsão valor de venda do imóvel
# Autor: Rodrigo de Lima Oliveira

Objetivo:

Um anúncio no portal é composto por diversas características do imóvel, como tamanho, número de quartos, etc. Uma das principais características do imóvel é o seu preço de venda, identificado pelo campo price que, por sua vez, está dentro do campo princingInfos.

O objetivo é criar uma maneira automática de estimar um preço de venda para os apartamentos.

Descrição das colunas do dataset:

usableAreas: tamanho do imóvel em m²
description: descrição do anúncio
title: título do anúncio
createdAt: timestamp da criação do anúncio
publisherId: identificador do anunciante
unitTypes: tipo do imóvel (apartamento, casa, comércial, etc)
listingStatus: status do anúncio (ativo ou inativo)
id: identificador único do anúncio
parkingSpaces: número de vagas de garagem
updatedAt: timestamp do último update
owner: indicador se o anunciante é proprietário do imóvel
images: lista de links de imagens do anúncio
address: endereço do imóvel
    country: país do imóvel
    zipCode: CEP do imóvel
    city: cidade do imóvel
    streetNumber: número da rua
    zone: zona do imóvel
    geoLocation: geolocalização do imóvel
    street: nome da rua
    locationId: id da localização
    district: distrito do imóvel
    unitNumber: complemento do imóvel
    state: estado federativo do imóvel
    neighborhood: bairro do imóvel
publicationType: tipo de publicação do anúncio (normal ou premium)
bathrooms: número de banheiros
totalAreas: área total do imóvel em m²
bedrooms: número de quartos
suites: número de suites
princingInfos: informações do preço
    price: preço de venda
    yearlyIptu: preço do IPTU
    businessType: tipo do anúncio (venda, aluguel ou ambos)
    monthlyCondoFee: condomínio
    rentalTotalPrice: preço do aluguel
