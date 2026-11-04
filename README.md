# Radar na Rota

Projeto pessoal e sem fins lucrativos: um app web (PWA) que mostra os equipamentos fixos de fiscalização eletrônica divulgados publicamente pela CET-SP ao longo de uma rota de carro na cidade de São Paulo, e compara rotas alternativas.

Funções: até 3 opções de rota com o número de radares de cada uma, navegação curva a curva com voz, seta de direção, mapa inclinado em 3D na navegação, recálculo automático, velocidade e limite da via (OpenStreetMap), tema claro/escuro e modo simulação. A versão anterior fica em `v1/` como reserva.

**Não é um detector de radar.** O app não detecta, não bloqueia e não interfere em nenhum equipamento. Ele só mostra informação pública, como fazem os apps de navegação.

## Uso responsável

- Respeite o Código de Trânsito Brasileiro (Lei 9.503/1997) e a sinalização em todo o trajeto, com ou sem câmera.
- Monte a rota antes de sair. Não manuseie o celular dirigindo (CTB, art. 252).
- Agentes de trânsito, radares móveis e câmeras novas não aparecem no app.

## Sem garantia

Os dados vêm de fontes públicas de terceiros e são mostrados como estão. Podem estar incompletos ou desatualizados. O autor não responde por multas, acidentes ou prejuízos decorrentes do uso. Sem relação com a CET, a Prefeitura de São Paulo, o OpenStreetMap ou qualquer órgão de trânsito.

## Privacidade

Sem cadastro, servidor próprio, anúncios ou rastreamento. A localização só é usada com permissão e é enviada apenas aos serviços de rota e endereço (OpenStreetMap/FOSSGIS e Photon/komoot) quando você pede uma rota ou quando a rota é recalculada durante a navegação. O trajeto não é gravado.

## Fontes e licenças

- Câmeras: painel público "Fiscalização Eletrônica – CET" (CET-SP), consultado no navegador de quem usa o app, completado com radares de velocidade cadastrados no OpenStreetMap (cópia em `radares_osm.json`, ODbL).
- Mapa e dados viários: © colaboradores do OpenStreetMap, ODbL — https://www.openstreetmap.org/copyright
- Rotas: OSRM (servidor de demonstração) para caminhos e tempo sem trânsito; Valhalla (servidor público da FOSSGIS e.V.) para instruções e desvio de radares. Endereços: Photon (komoot) e Nominatim.
- Desenho do mapa: OpenFreeMap / OpenMapTiles (dados do OpenStreetMap). Biblioteca de mapa: MapLibre GL JS (BSD-3).
- Código deste repositório: licença MIT.

Se alguma fonte pedir a retirada dos dados, eles serão removidos.
