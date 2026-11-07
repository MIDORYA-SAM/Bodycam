# ECHO — Operação Zero
Protótipo de FPS 3D em HTML, CSS e JavaScript, inspirado na estética de câmera corporal. Single player contra 8 inimigos. Não é uma reprodução do Bodycam comercial.

## Executar
Com Python 3 instalado, abra um terminal nesta pasta e execute:

    python3 -m http.server 8080 --directory dist

Acesse http://localhost:8080. Use um servidor HTTP: abrir index.html diretamente pode bloquear módulos e modelos.
Para celular, hospede a pasta dist em um serviço estático com HTTPS ou use o endereço IP do computador na mesma rede e a porta 8080.

PC: WASD mover, mouse mirar, clique esquerdo atirar, direito aproximar mira, R recarregar, F lanterna, Shift correr, Esc pausar.
Celular: joystick esquerdo, deslize na área direita para mirar e use os botões de tiro, recarga e lanterna. Horizontal recomendado.

## Recursos
Three.js 0.169.0, GLTFLoader, BufferGeometryUtils e SkeletonUtils baixados de jsDelivr (MIT; licença em dist/assets/THREE-LICENSE.txt).
Soldier.glb e brick_diffuse.jpg baixados do repositório oficial mrdoob/three.js, pasta examples. Modelo Soldier de referência do exemplo webgl_animation_skinning_blending, com animações incluídas.
Cenário e arma construídos em geometria 3D. Efeitos WAV originais gerados para este protótipo. Nenhum recurso do jogo comercial Bodycam foi utilizado.
Fontes Google Fonts opcionais; fontes locais de sistema servem como alternativa. Todos os recursos necessários ao jogo estão na pasta dist.

## Verificação
Sintaxe JavaScript e integridade dos arquivos verificadas. Validação visual em navegador e testes em aparelhos físicos não executados neste ambiente. O desempenho depende da GPU; use Desempenho no menu se necessário.
