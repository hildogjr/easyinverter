
GRUPO 01: teste do braço do inversor
1) Testes - OK
1a) Gate drive - OK
1b) Disable com a proteção - OK
1c) Memória de proteção - OK
1d) Proteção de temperatura - OK
1e) Proteção de tensão - OK (com proteção em 70V)
1f) Proteção de corrente - OK (reduzida para 8A)
2) Testes em parâmetros nominais - @Hildo, @Joel, @Felipe
2a) Tensão nominal e proteção de sobretensão - OK parcial, testado até 200V 8A
2b) Corrente nominal e proteção de sobrecorrente/curto-circuito - @Joel mandará um email sobre o tema
2c) Uso dos MOSFETs em paralelo - @Joel/Hildo (relato acima)

GRUPO 02: parte lógica
1) Placa
1a) Arrumar encapsulamento dos componentes no Altium - OK @Arthur/Felipe
1b) Arrumar conexões no Altium - OK @Hildo
1c) Arrumar as configurações de nome - OK @Hildo
1d) Arrumar valores dos componente para BoM automática (o Fellipe sabe fazer isso de forma automática e organizada) - OK @Arthur
1e) Arrumar as conexões de alimentação das portas lógicas - @Arthur
1f) Arrumar desenhos, alinhamentos, linhas tortas, padrões de impressão dos esquemáticos - @Arthur
1g) Layout para prototipagem interna na FEEC - @Hildo
2) Placa da fonte principal - OK
2a) Mandar separada para o JP (para ganharmos tempo de projeto) - OK
2b) Montar - OK @Hildo/Joel
2c) Testar - OK @Joel/Hildo
2d) Importar no Altium para o projeto nosso - OK @Arthur (mudar os encapsulamentos para 0805 e pino 11 do CI)
3) Teste das funções
3a) Shifet-level (3.3->5V)
3b) Memórias / reset / enable
3c) Dead time
3d) Relês
3e) Disables cruzados entre braços
4) Teste de um chaveamento completo, usando os transistores TOP e BOTTOM

GRUPO 03: discussão de detalhes de montagem
1) Sensor de temperatura - @Hildo, @Fellipe, @Joel (eu proponho a montagem dele para baixo encostando no isolador dos transistores, onde está, não está propagando bem o calor. Se for um isolador que pegue o espaçamento duplo, ele ficaria no meio de forma perfeita)
2) Compra de capacitores eletrolíticos (Arthur, você tem reserva técnica?) Liguei no PIBIC e falaram que só a FAPESP que tem isso pro IC
3) Dissipador


GRUPO 04: padrões para produção
1a) Aperfeiçoamento do layout de comando - @Fellipe (objetivo: ganhar 1cm lateral... vai na boa :-D )
1b) Acerto do silk da placa de comando @Arthur
2a) Aperfeiçoamento do layout digital - @Fellipe (colocar as trilhas finas padrão para montagem externa)
2b) Acerto do silk da placa digital @Arthur
3a) União das placas @Arthur (Felipe/Hildo?)
3b) Definição das conexões de potência e posição dos capacitores eletrolíticos
4) Revisão do padrão do Altium para produção externa (dado de montagem, BoM, links de compra, especificações...)
5) Descritivos
5a) Documento de histórico e desenvolvimento (formas de onda, histórico, registro dos membros, ...) @Arthur
5b) Manual técnico/datasheet (limites operações e conexões; modelo que coloquei na pasta) @Arthur
6) Compartilhamento do projeto na comunidade
6a) Adicionar nossos nomes, simbolo da UNICAMP e FEEC e nome do lab no Silk em local visível da placa @Arthur
6b) Definição do nome oficial
6c) Definir licença de hardware aberto com manutenção de direitos aos autores originais
6d) Upar para o GitHub - @Hildo



#2017-08-06
One phase 3.jpg


#2017-06-29
Logic (bottom).jpg
Logic (top).jpg

#2017-06-27
One phase 3.jpg


#2017-06-13
Logics only prototype [HGJr].7z

#2017-06-01
One phase (com erros).7z

#2017-05-17
Supplier (bottom).jpg
Supplier (top).jpg


#2017-04-28
One phase 2 (bottom).jpg
One phase 2 (top).jpg

#2017-04-03
One phase (bottom).jpg
One phase (top).jpg

#2017-03-13
One phase prototype [HGJr].7z

#2016-10-05


#2016-10-05
Isolated supplier 2 (bottom).jpg
Isolated supplier 2 (top).jpg

#2016-10-01
Isolated supplier 1.jpg

#2016-10-05
Isolated power supplier to the gate drivers tested and working at 400kHz.
