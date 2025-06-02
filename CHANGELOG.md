# 📘 Caderno de Bitácora
Todos os cambios significativos no servidor de GalizaTTD estarán documentados nesta canle.

O formato está baseado en [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
e o proxecto adhírese a [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.3.0 - 2025-06-02]
### ✨ Engadidos
- Engadidos JP+ Tracks para usar como ferrocarrís base
- Engadidas casas suecas e xaponesas agora que se poden poñer manualmente as casas.
### 🏗️ Cambios
- Actualizada a versión base do xogo a JGRPP 0.65.3 e múltiples packs de obxectos.
### ⏪ Eliminados
- Pack propio de ferrocarrís de Galicia.

## [1.2.0 - 2024-12-08]
### ✨ Engadidos
- Engadidos vehículos Húngaros para autobuses, camións e tranvías.
### 🏗️ Cambios
- Actualizada a versión base do xogo a JGRPP 0.63.1 e múltiples packs de obxectos.

## [1.1.1 - 2024-11-03]
### 🐛 Arranxos
- Arranxado erro co RenewedVillageGrowth que impedía o arranque da partida.

## [1.1.0 - 2024-11-03]
### ✨ Engadidos
- Permitir as "persoas" (o vehículo) utilizar as estradas de terra.
### 🏗️ Cambios
- Cambiado o ano de comezo a 2024 e as estradas preconstruidas a asfalto básico.
- Actualizada a versión base do xogo a JGRPP 0.63.0 e múltiples packs de obxectos.
### ⏪ Eliminados
- Pack de casas xaponesas. Únicamente quedamos coas europeas aínda que non teñan neve.



## [1.0.0 - 2024-09-22]
### ✨ Engadidos
- Traducións das embarcacións de vela ó galego.
- Paquetes de trens de Europa e de Corea do Norte, traducidos ó galego.
- Paquete de trens de China en alta calidade (pendentes de tradución).
- Script de Crecemento das Vilas, para que haxa que suministrarlles máis recursos para que medren.
- Engadidas liñas verde, vermella e LGBT do tranvía (a partir de 1975)
- Engadidos novos tipos de ferrocarril: Ancho estándar, estreito, dobre, urbáns e metro.
- Engadida a industria "Praza" para poder deseñar zonas ou vilas "artificiais" (con decoracións) e levar e traer pasaxeiros, correo e lixo delas.
- Engadidos novas casas e obxectos para decorar o escenario.
- Engadidas estradas entre as vilas por defecto (xeradas polo propio xogo)
- Engadidas estradas decorativas: Bulevar, piñeiros, palmeiras, alumeado, quitamedos, setos, e moito máis!
- Engadidas industrias extractoras de auga, plantas de electrólise, fábricas de cerámica, xestión de refugallos.
- Globos aerostáticos e mástis para atracar os cepelíns.
- Engadidas tuberías (oleoductos), para o transporte de líquidos.
- Personalizacións das estacións de autobuses e camións.
### 🏗️ Cambios
- Actualizada a versión base do xogo a JGRPP 0.61.0 e múltiples packs de obxectos.
- Cadeas industriais refeitas para representar máis a economía galega, asturiana e leonesa.
- Os pasaxeiros agora queren ir a unha estación de destino e volver despois (tráfico simétrico).
- Modificadas as velocidades máximas das pontes para poder usar o estilo que máis nos interese.
- Aumentada a velocidade dos avións para que sexa realista (Orixinalmente está a 1/4 para que o resto de transportes sexan competitivos).
- Aumentado o coste de fundar industrias, construír aeroportos x2048(e mantelos x256) e a construción de canles e exclusas(x128).
- Fixado o autogardado cada 5 minutos reais e coas desconexións de rede, para minimizar a perda de progreso.
- A Central eléctrica agora amósase coma unha subestación eléctrica, para poder decorala como central de carbón, hidróxeno, ou o que se queira.
### 🐛 Arranxos
- Corrixidas as maiúsculas no nome "Fábrica de mobles" no pack de industrias.
- Cando aparecían novos vehículos poñía "Novo estrada agora dispoñíbel", no canto de "Novo vehículo de estrada"
- Corrido o nome das estacións no pack de industrias nos "Serradoiros" e "Pasteiras".  Anteriormente poñía "Panificadora".
- Os tranvías non podían circular polas vías de tranvía industrial.
- Os depósitos frontais dos arboriductos tiñan os sprites invertidos.
- Os trens estaban collendo as curvas fechadas a +300km/h sen despeinarse.
### ⏪ Eliminados
- Pack de trens de España e FEVE (Moitos destes trens están incluídos no de trens de Europa con mellor calidade)
- Industria "Multiplayer Trade Center": Non tiña uso xa que podemos facer estacións compartidas.
- Deshabilitada a compra/venda de accións de outras compañías (causaba confusión e non implicaba nada realmente)
- Os factores de lonxitude do día e xeración de carga restablecidos a configuración por defecto, xa que dende OpenTTD 14 hai períodos para manter a data fixa.

## [0.1.0 - 2022-07-02]

### 🏗️ Cambios
- Modificado o factor de lonxitude do día a 120, facendo que cada día dure 2 horas do xogo (aprox 5 mins reais).
- Modificado o factor de xeración de carga das industrias a 5.0 (x32).
- Modificado o factor de xeración de carga das vilas (pasaxeiros,correo) a 5.0 (x32)