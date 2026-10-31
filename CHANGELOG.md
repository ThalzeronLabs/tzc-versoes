# Novidades do Thalzeron Code

Cada versão nova chega sozinha ao TZC instalado, com a assinatura conferida antes de instalar.

## 0.1.169 · 31/10/2026

- **Número de build.** A aba Sobre e a página de download mostram o número de build ao lado da versão: um contador que só sobe e soma todas as versões do TZC já publicadas.

## 0.1.168 · 31/10/2026

- **Notas de versão mais claras.** As novidades de todas as versões foram reescritas: cada item diz, em poucas linhas, o que você ganha com a atualização.
- **Tema Thalzeron.** O tema padrão, preto com o verde da marca, agora se chama Thalzeron.

## 0.1.167 · 31/10/2026

- **Central dos agentes.** Nova vista Central dos agentes na barra lateral: todas as conversas em andamento lado a lado, com o passo atual, a lista de tarefas e o progresso, o gasto, o contexto e as provas de cada uma. Os pedidos de aprovação de todos os agentes ficam reunidos numa coluna, e aprovar ou negar ali vale como dentro da conversa. Embaixo, a atividade da última hora.

## 0.1.166 · 31/10/2026

- **Atualizações mais confiáveis.** Melhorias na forma como as versões novas são preparadas e conferidas antes de chegar a você.

## 0.1.165 · 31/10/2026

- **Atualização com rede de segurança.** Durante a atualização, uma janela mostra cada etapa. O TZC guarda a versão atual e, se a nova não abrir corretamente, volta sozinho para a anterior, explica o que houve e só tenta de novo quando você pedir. Computadores mais lentos não disparam a volta à toa: ela só acontece por falha real.

## 0.1.164 · 31/10/2026

- **Atualizações assinadas.** Cada versão nova sai com assinatura digital, e o TZC só instala a atualização cuja assinatura confere. Uma versão adulterada não é instalada, e a barra superior avisa.

## 0.1.163 · 31/10/2026

- **Agentes personalizados.** Peça ao agente algo como "cria um agente que revisa os meus contratos": ele cria o especialista, com o próprio jeito, cérebro e ferramentas, e passa a chamá-lo quando precisar. Regras e agentes que você já usa em outras ferramentas de terminal deste PC podem ser importados. Inclui uma equipe pronta para negócios: direção, finanças, jurídico, marketing, vendas, produto e revisão final.

## 0.1.162 · 31/10/2026

- **Slides, painéis e telas prontos.** Três novos tipos de artefato com acabamento profissional: Slides (miniaturas, navegação pelo teclado, tela cheia e download em .pptx), Painel de dados (cada número com a fonte, gráficos e ranking) e Design (telas lado a lado, com zoom). O agente escreve o conteúdo; o visual sai sempre caprichado.
- **Importar sessões.** O cartão do Início que traz as conversas iniciadas no terminal agora se chama Importar sessões, e elas chegam no grupo Importadas.

## 0.1.161 · 31/10/2026

- **Ditado que aprende.** Quando você corrige uma palavra ditada antes de enviar, a forma certa entra no seu vocabulário, e o ditado passa a escrevê-la corretamente.

## 0.1.160 · 31/10/2026

- **Monitoramento da memória e do terminal.** O TZC agora percebe quando a memória livre fica abaixo de 2 GB (o agente adia compilações e testes pesados até ela voltar) e quando o PowerShell deixa de abrir (o agente passa a usar o Bash). Você recebe um aviso com o que fazer e outro quando tudo volta ao normal.

## 0.1.159 · 31/10/2026

- **Proteção para arquivos com senhas.** Antes de o agente ler um arquivo que costuma guardar senhas e chaves (.env, chaves privadas, credenciais de programas, senhas do navegador), você recebe um cartão para liberar ou negar, inclusive no modo Liberado. Liberado uma vez, vale para aquela conversa. Modelos de exemplo, como o .env.example, passam direto.

## 0.1.158 · 31/10/2026

- **Respostas rápidas para pedidos pequenos.** Em pedidos curtos, como trocar uma cor ou corrigir uma linha, o agente faz, confere e responde, sem as etapas das tarefas grandes. A prova de que funcionou continua.

## 0.1.157 · 31/10/2026

- **Desfazer o que o agente criou.** O agente pode desfazer de uma vez as travas, as rotinas e as perguntas guardadas que ele mesmo criou na conversa. O que é seu não é tocado.

## 0.1.156 · 31/10/2026

- **Detecção de disco travado.** O TZC confere a cada 2 minutos se cada disco responde. Quando um trava (o caso mais comum é um disco de nuvem, como o Google Drive), você recebe um aviso com o que fazer, e o agente deixa de usar aquele disco até ele voltar, em vez de ficar preso esperando.

## 0.1.155 · 31/10/2026

- **Melhorias de estabilidade.** Cada versão nova passa por uma conferência automática das telas antes de chegar a você. Na Bancada de Provas, cada tipo de teste indica se está pronto ou em breve.

## 0.1.154 · 31/10/2026

- **Ditado com os seus nomes.** O ditado reconhece o seu nome, o apelido do Perfil e os nomes das pastas dos seus projetos.

## 0.1.153 · 31/10/2026

- **Prints do navegador mais rápidos.** Quando o agente tira um print do navegador com o painel escondido, o painel abre sozinho, em vez de o print esperar um minuto. Se não der para abrir, o agente avisa na hora e lê o texto da página.

## 0.1.152 · 31/10/2026

- **Privacidade da sua tela.** Quando o agente usa o computador, o print mostra nítido só o programa que você liberou e a barra de tarefas; o resto da tela (e-mail, banco, outras janelas) chega a ele borrado e ilegível, inclusive no zoom. Para ver outro programa, ele pede, e você aprova.

## 0.1.151 · 31/10/2026

- **Registro do que sai do seu PC.** Em Configurações → Privacidade e dados, o registro das últimas 24 horas mostra cada envio ao provedor do modelo (a sua mensagem e os arquivos que o agente leu, com o tamanho) e as chaves removidas antes do envio. Se um arquivo lido continha uma chave, ela fica marcada e a conversa avisa na hora, para você trocá-la.

## 0.1.150 · 31/10/2026

- **Aviso de e-mails em páginas publicadas.** Antes de publicar uma página, o TZC também aponta os endereços de e-mail que aparecem nela. Como numa página de contato isso pode ser de propósito, ele não bloqueia: só pergunta se é para manter.

## 0.1.149 · 31/10/2026

- **Filtro de chaves nas páginas na nuvem.** As páginas que o agente publica na sua conta, que podem ganhar um link público, também passam pelo filtro de chaves: com uma chave dentro, elas não saem do PC.

## 0.1.148 · 31/10/2026

- **Nenhuma chave vaza num artefato.** Antes de publicar uma página, o TZC procura chaves de API (de provedores de IA, do Google, do GitHub e outras): se encontrar, a página não sai, e o agente remove a chave. Caminhos do seu PC com o seu nome de usuário também são apontados, para não aparecerem sem querer.

## 0.1.147 · 31/10/2026

- **Permissão de escrita por pasta.** Com a escrita fora da pasta desligada, o agente pode pedir para escrever numa pasta específica, como a de um build ou de outro projeto. O pedido chega com o motivo; aprovado, vale na hora e só naquela conversa. Ligar o modo Liberado no meio não aprova esse pedido por você.

## 0.1.146 · 31/10/2026

- **Escolha certa do navegador.** O agente sabe quais navegadores estão disponíveis: o do TZC, sempre, e o seu Chrome com os seus logins, quando a extensão está conectada. O do TZC fica para pesquisar e testar; o seu Chrome, só quando a tarefa precisa da sua conta.

## 0.1.145 · 31/10/2026

- **Reconexão dos conectores.** Durante o trabalho, o agente vê o estado de cada conector (conectado, com falha, aguardando login) e reconecta na hora o que caiu, sem reiniciar a conversa.

## 0.1.144 · 31/10/2026

- **Conectores por conversa.** O agente pode desligar um conector só na conversa dele, para trabalhar com menos ferramentas e menos distração, e religá-lo depois. Um conector que você desligou nas Configurações continua desligado: religar é decisão sua.

## 0.1.143 · 31/10/2026

- **Troca de projeto no meio da conversa.** O agente pode mudar a pasta de trabalho da sessão para outro projeto, e a conversa continua com toda a memória. A troca segue o modo de aprovação; com a escrita fora da pasta desligada, ela depende de você.

## 0.1.142 · 31/10/2026

- **Corrigido: ordem das chaves no JavaScript.** Quando o agente roda JavaScript numa página, o objeto retornado mantém a ordem original das chaves, em vez da ordem alfabética, e a leitura da página sai correta.

## 0.1.141 · 31/10/2026

- **Paleta Nebulosa.** A paleta de vidro escuro com violeta dos artefatos agora se chama Nebulosa (quem já a usava continua com ela), e a Papel ganhou a descrição: creme e tinta.

## 0.1.140 · 31/10/2026

- **Aba Prazos mais clara.** A aba Prazos mostra onde fica o caderno com as medidas de tempo das suas tarefas.

## 0.1.139 · 31/10/2026

- **Previsão do gasto do mês.** Em Uso e custos, um cartão mostra quanto o mês deve fechar no ritmo atual e a média por dia. O calendário do ano abre no mês atual, mesmo em telas estreitas.

## 0.1.138 · 31/10/2026

- **Acessos e Conectores mais precisos.** A aba Acessos mostra corretamente a conta do Google Cloud. A aba Conectores conta todos os servidores e ferramentas do TZC e leva à lista completa em O motor.

## 0.1.137 · 31/10/2026

- **Gerenciar o Sempre neste projeto.** Em Configurações → Permissões e modos, cada projeto lista os tipos de pedido que você liberou com Sempre neste projeto (como git ou npm), e o × volta a exigir aprovação.

## 0.1.136 · 31/10/2026

- **Textos mais limpos.** Textos da interface revisados, e a vista Artefatos passa a mostrar só os artefatos publicados pelo seu agente.
- **Temas alinhados.** Em Aparência, os cartões dos temas ficam alinhados e cabem lado a lado em telas largas, e o tema HUD ganhou descrição.

## 0.1.135 · 31/10/2026

- **Loja de plugins com filtros.** Em Configurações → Plugins: os totais no topo (instalados, disponíveis e exibidos), as categorias como filtros com a contagem de cada uma e o aviso de quantos itens a lista mostra. A loja abre na hora, mesmo na primeira vez; as descrições são traduzidas em segundo plano.

## 0.1.134 · 31/10/2026

- **Aba O motor reformulada.** Em Configurações → O motor: os totais no topo (ferramentas, conectores, skills e comandos), uma busca e as ferramentas agrupadas por função (navegador, computador, Gmail…), cada grupo recolhível.
- **Sobre e atualizações.** O estado da atualização em tempo real, os botões de procurar agora e de reiniciar quando a nova versão já baixou, e o histórico completo das versões.

## 0.1.133 · 31/10/2026

- **Corrigido: cópia isolada do projeto.** A cópia isolada do projeto (worktree), que permite ao agente trabalhar num branch próprio sem mexer no seu, funciona mesmo quando o projeto vira um repositório git no meio da conversa. A cópia fica na pasta dos arquivos grandes.

## 0.1.132 · 31/10/2026

- **Juntar PDFs sem perder o formulário.** Ao juntar PDFs, o primeiro arquivo é a base: os campos de formulário, o título e o autor dele são mantidos. Se outro arquivo também tinha campos, o agente avisa quantos ficaram de fora e como mantê-los.
- **Gmail e loja mais úteis.** Os rótulos do Gmail mostram a contagem de não lidas, e os rascunhos trazem o destinatário e o assunto. A busca na loja de plugins prioriza o que tem o termo no nome, mostra qual termo bateu e avisa quando há mais resultados.
- **Abas novas já carregadas.** Ao abrir uma aba nova com um endereço, o agente espera a página carregar e já recebe o título e o endereço.

## 0.1.131 · 31/10/2026

- **Leitura completa de formulários.** Ao ler uma página, o agente vê o rótulo e o estado de cada campo: o texto digitado, as caixas marcadas, a opção escolhida e os arquivos anexados. O console mostra o conteúdo dos objetos, como no DevTools.
- **Leitura da máquina unificada.** O estado do PC e a medida dos recursos usam o mesmo cálculo de folga (2 GB e 2 threads reservados ao sistema), sempre coerentes entre si. O agente também consegue devolver a janela à tela anterior depois de abrir uma sessão para você ver.

## 0.1.130 · 31/10/2026

- **O agente desfaz o que criou.** Travas e rotinas que o agente criou por engano ou num teste, ele mesmo remove; as suas continuam intocadas. Quando um comando esbarra numa trava sua do tipo só avisar, o agente também é informado.
- **Mensagens de erro mais claras.** Mensagens de erro mais precisas no Chrome, no GitHub e nos artefatos na nuvem. Os e-mails chegam ao agente sem os caracteres invisíveis de marketing, o que reduz o consumo de tokens.
- **Skills e equipes.** A busca de skills sugere plugins da loja sobre o assunto quando você ainda não tem nenhuma, e as descrições longas aparecem inteiras. Corrigido: um dev criado por outra sessão recebia orientações do Dev Chefe que contradiziam as de quem o criou.

## 0.1.129 · 31/10/2026

- **Sua tela só com a sua aprovação.** O agente só tira print da sua tela depois de pedir acesso ao computador, e o pedido sempre abre um cartão para você aprovar, com o motivo, em qualquer modo, inclusive no Liberado.
- **Contagem correta das ferramentas.** O uso de uma sessão, os eventos e a conversa exportada contam cada ferramenta uma única vez, e a exportação inclui o que cada ferramenta recebeu e respondeu. Os pedidos da Cascata e a base de conhecimento mostram o horário do seu PC.
- **Navegador, terminal e servidores mais estáveis.** O terminal do agente não digita por cima de um comando em execução, o lote do navegador para na primeira falha e os GIFs guardam o nome e a hora certos. O filtro de erros dos servidores ignora os acessos bem-sucedidos, e a busca na web funciona com os outros cérebros (ou explica por que não deu).

## 0.1.128 · 31/10/2026

- **Discos lentos não travam mais o TZC.** Quando um disco de rede ou de nuvem para de responder, a sessão nova começa na hora, em vez de esperar minutos antes de chamar o modelo. O TZC lê os discos em paralelo, com tempo limite para cada um, e funciona mesmo sem o PowerShell.
- **Aviso de servidor esquecido.** Se o agente terminar com um servidor de desenvolvimento ainda ligado, a conversa avisa uma vez, com a porta, e você decide se ele para.

## 0.1.127 · 31/10/2026

- **Prévia real no painel Artefato.** Quando o agente escreve uma página num projeto, o painel Artefato mostra a página como ela é, com o CSS, os botões e os scripts funcionando, e guarda os dados dela. Antes, aparecia só o HTML cru.
- **Ferramentas carregadas na hora em todos os cérebros.** Quando um modelo do OpenRouter, do Gemini ou local carrega uma ferramenta no meio da conversa, ele recebe também os campos dela, sem precisar adivinhar. O resultado da busca de ferramentas chega em texto.
- **Medidor de contexto em todos os cérebros.** Nos cérebros que só informam os tokens no fim da resposta, o medidor de contexto mostra uma estimativa até o número exato chegar.
- **Nomes automáticos para as sessões.** Depois da primeira mensagem, a sessão ganha um nome curto, com o assunto. Nas sessões grátis, o nome é gerado sem chamar modelo. Um nome dado por você nunca é trocado.
- **Prova, Cascata e Configurações.** A prova aceita comandos que começam com cd. A Cascata registra os seus pedidos em qualquer cérebro. Em telas largas, as abas das Configurações se organizam em colunas.

## 0.1.126 · 31/10/2026

- **Cérebros e chaves reorganizado.** No topo, o cérebro das sessões novas (com o Trocar), quantos cérebros estão prontos, o gasto do mês e do dia e os modelos grátis disponíveis. Filtros separam os prontos, os sem chave e os com modelos grátis, e cada cartão sem chave ensina, passo a passo, como obtê-la. Na lista de modelos, um clique define o cérebro das sessões novas ou o adiciona às reservas; os cérebros locais vêm logo depois dos da nuvem, com o Testar.
- **Cérebro padrão das sessões novas.** As sessões novas começam com o cérebro que você escolher em Cérebros e chaves, marcado com uma estrela.
- **Página inicial do navegador.** A página inicial do navegador interno traz atalhos para o site do TZC, o GitHub, o MDN, o Stack Overflow, o npm e o PyPI, e os sites que você usa aparecem nos visitados recentemente.

## 0.1.125 · 31/10/2026

- **Conversa mais limpa.** Os ajustes internos entre o TZC e o modelo não aparecem mais na conversa: você vê só o cartão final, já correto. Tudo continua guardado na sessão.
- **Painel Artefato.** As páginas que o agente publica abrem num painel próprio, ao lado da conversa. Enquanto ele escreve, você vê a página nascendo; quando ele publica, ela aparece completa. O botão Abrir no navegador continua disponível.
- **Cérebros e chaves em cartões.** Cada cérebro ganha um cartão com o estado, o último teste e o saldo. Ali você cola a chave num campo protegido, testa, cria a chave no site do provedor, apaga a chave e vê os modelos com o preço; o Testar todos confere tudo de uma vez.
- **Configurações do tamanho da sua tela.** A janela das Configurações abre proporcional à tela: em monitores largos, fica mais larga e alta, com os cartões em colunas.
- **Corrigido: saldo -0,00.** Saldos menores que meio centavo aparecem como zero.

## 0.1.124 · 31/10/2026

- **Borda verde quando o agente usa o seu PC.** Enquanto o agente usa o mouse e o teclado, uma borda verde pulsa em volta do monitor em uso, com a plaquinha "Thalzeron Code" e o botão Parar, que devolve o computador na hora sem interromper o trabalho. A borda não captura cliques nem aparece nos prints do agente, e uma faixa na janela mostra qual sessão está no controle. O acesso termina quando o agente conclui ou depois de 1 minuto sem uso.
- **Lista de tarefas no fim da conversa.** A lista do agente fica sempre no fim da conversa: as mensagens novas entram acima dela, e a linha de atividade (o que ele faz e há quanto tempo) logo embaixo.
- **Aviso de que o agente precisa de você.** Se você rolou a conversa para cima e o agente fez uma pergunta ou pediu uma aprovação, uma plaquinha aparece acima da caixa de texto; um clique leva até o cartão.
- **Prints guardados.** O agente pode salvar prints e zooms na pasta da sessão (.tzc/prints), com a hora no nome, para consultá-los depois.
- **Instalador mais seguro.** O TZC instalado bloqueia depuradores e código injetado por variáveis de ambiente ao abrir, e cada instalador é auditado para garantir que nenhuma chave vá junto.

## 0.1.123 · 31/10/2026

- **Troca de modo imediata.** Trocar o modo com o agente trabalhando vale no mesmo instante, e o pedido de aprovação pendente sai sozinho. No modo Edita e lê livre, comandos só de leitura passam mesmo com |, || e 2>/dev/null, sem pedir aprovação.
- **Dev Chefe mais preciso.** Pedidos já respondidos não chegam mais ao Dev Chefe, e ele responde cada aprovação numa linha. Desligar o Dev Chefe desliga também a ronda, e o dev em andamento é avisado na hora de que agora se reporta a você; religar restabelece o chefe.
- **Mensagens entre sessões recolhidas.** Mensagens do Dev Chefe, pedidos de aprovação encaminhados e rondas aparecem numa linha recolhida, com o remetente, a primeira frase e a hora do envio. Elas não se misturam mais às suas mensagens nem à lista dos seus pedidos.
- **Menos idas e voltas no fim da tarefa.** As regras do seu jeito (marcar os pedidos, explicar os termos, registrar a prova) chegam ao agente no começo de cada volta, e o que faltar no fim vira uma linha discreta, sem retrabalho. Só uma resposta no idioma errado volta para ser reescrita.
- **Ditado de clicar e falar.** Clique para falar e clique de novo para parar: o ditado não corta mais no silêncio (até 10 minutos). O microfone em uso aparece ao lado do botão, o aviso de erro some quando o fone conecta e a transcrição ficou mais precisa.
- **O cérebro que você escolheu, sempre.** Se o cérebro escolhido falhar (chave recusada, provedor fora do ar), a sessão para e avisa, em vez de seguir com outro sem você saber. A troca automática só acontece com a opção Trocar de cérebro sozinho (Configurações → Jeito). Uma sessão com modelo grátis nunca passa a gastar: a reserva é só grátis, e os ajudantes pagos não rodam nela.
- **Saldos dos provedores.** Um cartão Saldos no Início, o detalhe em Configurações → Uso e o menor saldo na barra inferior, em amarelo abaixo de 20%. OpenRouter, DeepSeek e Kimi funcionam só com a chave; os demais provedores pedem um login único numa janela do próprio TZC, e o saldo é atualizado a cada 5 minutos.
- **Custo estimado e chaves grátis.** O custo calculado pelo TZC (tokens × preço de tabela) aparece com ≈, para não ser confundido com o valor oficial dos Saldos. Em Cérebros e chaves, a opção plano grátis marca uma chave sem cobrança: o custo dela fica zero e ela serve de reserva grátis (o OpenRouter é marcado sozinho).
- **Ditado para todos, mesmo sem chave.** Na sessão com o Gemini, o próprio modelo transcreve; nas outras, o Gemini Flash, com a chave do Google. Sem essa chave, o ditado roda no seu PC, sem conta e sem custo: na primeira vez, o TZC baixa o motor de transcrição no tamanho certo para a sua máquina, confere o arquivo e mostra o progresso.
- **Aprovações que lembram e rolagem estável.** O Sempre neste projeto vale para o mesmo tipo de pedido (o mesmo programa), e não só para o comando exato. A conversa só acompanha o fim quando você já está no fim: se rolou para cima para ler, ela não pula.
- **Conversa e terminal mais limpos.** Avisos de nova tentativa e de troca de cérebro ficam nos blocos recolhidos, uma prova registrada de novo substitui a anterior e mensagens longas ganham o mostrar mais. Um só aviso sonoro por sessão, acentos corretos no Python e mensagens do motor em português no terminal.

## 0.1.122 · 30/10/2026

- **Ditado na resposta livre.** Nas perguntas do agente, o campo da resposta livre ganhou o microfone: clique, fale e o texto entra ali mesmo. O campo cresce com o texto, e o ditado se junta ao que já estava escrito.
- **Sessões em máquinas Windows remotas.** Uma sessão pode rodar o motor num PC Windows da sua rede, por SSH, como já rodava no Linux, e o TZC detecta o sistema sozinho. As suas chaves continuam só neste PC, e os acentos chegam corretos.

## 0.1.121 · 30/10/2026

- **Histórico de custos permanente.** Todo gasto com a API fica registrado fora da pasta do programa: atualizar ou reinstalar o TZC não zera mais o uso. A cada versão nova, o banco das conversas ganha uma cópia de segurança (as 5 últimas ficam guardadas). Corrigido: conversas que ficavam presas numa pasta oculta do Windows voltam a aparecer.
- **Registro oficial de conectores.** Em Configurações → Conectores, procure qualquer conector do registro oficial do MCP (GitHub, Notion, bancos de dados…), com a descrição em português, e ligue num clique. O agente também sugere conectores na conversa, com o botão Ligar; o clique é seu.

## 0.1.120 · 30/10/2026

- **Tudo em português.** As descrições que vêm em inglês (plugins da loja, estilos, sugestões de plugins, categorias e estados dos conectores) aparecem em português do Brasil. Cada texto é traduzido uma vez e guardado, então da segunda vez aparece na hora.
- **Formatação caprichada.** As listas mostram a descrição inteira em até 3 linhas, com o "mais" para o resto e as categorias em etiquetas. As respostas no chat quebram corretamente palavras e caminhos longos, e as listas aninhadas ficam alinhadas. Arquivos Markdown abrem formatados, com o botão Editar.

## 0.1.119 · 30/10/2026

- **Passos do agente recolhidos.** O raciocínio e as ferramentas usadas entre duas falas viram uma linha recolhida, com o resumo em português ("Leu 1 arquivo e executou 1 comando ▸"); um clique mostra cada passo. Durante o trabalho, só o passo atual aparece, e falhas ficam visíveis. Aprovações e perguntas nunca ficam escondidas.

## 0.1.118 · 30/10/2026

- **Base de conhecimento do projeto.** O agente guarda o conhecimento duradouro do projeto (como uma API se comporta, como o build funciona, o porquê de uma arquitetura), com as referências. Os títulos entram em toda conversa nova, e o agente consulta a base antes de pesquisar do zero.
- **Gatilho de e-mail.** Peça ao agente um gatilho com uma busca do Gmail (ex.: from:banco subject:boleto): quando chegar um e-mail que corresponda, a tarefa chega à sessão com o remetente, o assunto e o trecho. A verificação roda a cada 5 minutos, mesmo com a janela fechada.
- **Disjuntor do modo Automático.** Se o modo Automático negar 3 pedidos seguidos do agente (ou 10 em 50), a sessão volta ao modo Perguntar e avisa: o agente não insiste em algo fora do pedido, e a decisão volta para você.

## 0.1.117 · 30/10/2026

- **Fila dos trabalhos pesados.** Antes de um build, um teste grande, uma renderização ou um modelo local, o agente entra na fila: até 2 trabalhos pesados ao mesmo tempo na máquina e 1 por projeto, para não esgotar a memória. Com a fila cheia, cada um espera a sua vez, e uma vez abandonada é liberada sozinha.
- **Limite de agentes simultâneos.** Defina quantas sessões trabalham ao mesmo tempo (6 por padrão) em Configurações → Jeito Thalzeron. A sessão que passa do limite espera e começa sozinha quando outra termina.
- **Corrigido: barra lateral na abertura.** Mudanças feitas enquanto o TZC abria (fixar, renomear, concluir uma sessão) agora aparecem na barra lateral na hora.

## 0.1.116 · 30/10/2026

- **Conferência automática da resposta.** Antes de o agente terminar, o TZC confere a resposta sem gastar outro modelo: um trecho em inglês volta para ser reescrito em português, e uma sigla nova sem explicação volta para ganhar uma frase simples. A opção fica em Configurações → Jeito Thalzeron.
- **Glossário e "O que eu já sei".** Cada termo novo que o agente explica entra no glossário do projeto, numa aba nova do caderno. Em Configurações → Jeito Thalzeron, "O que eu já sei" guarda os termos que você já conhece, e o agente deixa de explicá-los.
- **O TZC aprende o seu jeito.** Quando você corrige ou elogia um jeito de trabalhar ("eu prefiro…", "de agora em diante…"), o agente propõe gravar como preferência. Toda segunda-feira, o relatório da manhã traz uma faxina da memória: o que venceu e o que se contradiz.

## 0.1.115 · 30/10/2026

- **Tema TZC nos artefatos.** Todo artefato do agente nasce do mesmo modelo visual: tipografia, cores para claro e escuro, selos (PROVISÓRIO, DEFINITIVO, AO VIVO, PENDENTE e problema), abas, cartões, tabelas e linha do tempo. Escolha a paleta em Configurações → Jeito Thalzeron: TZC, Nebulosa ou Papel.
- **Projeto em foco.** No menu de uma sessão, "Pôr o projeto em foco" leva as sessões daquele projeto ao grupo ★ Em foco, no topo da barra, e recolhe o resto; o Início também o mostra primeiro. "Tirar o projeto do foco" desfaz.

## 0.1.114 · 30/10/2026

- **Galeria antes × depois.** O caderno do projeto ganhou a aba Galeria: o agente guarda o print de antes e o de depois de cada mudança visual, e você arrasta uma régua sobre a imagem para comparar. Cada foto abre em tamanho grande e pode ser baixada.
- **Decisões no Fiz sem perguntar.** O cartão do fim da volta, nos modos Fora e Dormindo, mostra o texto de cada decisão registrada.

## 0.1.113 · 30/10/2026

- **Calibragem dos prazos em gráfico.** A aba Prazos do caderno abre com um gráfico por categoria: quanto o tempo real ficou do estimado (a mediana). Verde à esquerda da linha de 1× significa mais rápido que o previsto; âmbar à direita, mais lento. Passe o mouse para ver o número e quantas medidas ele reúne.
- **Corrigido: conexão do tzc no terminal.** O comando tzc no terminal conecta corretamente mesmo quando o TZC foi aberto de dentro de outro aplicativo do Windows.

## 0.1.112 · 30/10/2026

- **Ronda do Dev Chefe.** A cada 20 minutos, o Dev Chefe recebe o que mudou nas sessões (quem terminou, quem parou com erro, quem espera resposta, os pedidos novos) e dá a próxima ordem. Se nada mudou, nada é enviado, e a ronda não gasta.
- **Maratona guiada pela lista.** A cada volta, a maratona puxa o próximo item da lista do projeto (a Cascata). Um "pare", "chega" ou "pode parar" na conversa encerra o ciclo: o agente termina o passo em andamento e escreve o relatório.
- **Maratonas que retomam sozinhas.** As maratonas ficam salvas e voltam quando o TZC reinicia. Uma maratona parada há mais de 10 minutos é retomada sozinha e, se o prazo passou, pede o relatório.

## 0.1.111 · 30/10/2026

- **Isso já existe.** Antes de uma pergunta chegar a você, o TZC procura os termos dela na memória, no livro das decisões e nos Acessos. O que encontrar volta ao agente, que segue com o que já foi decidido em vez de perguntar de novo. Ligado por padrão, em Configurações → Jeito Thalzeron → As perguntas.
- **Fiz sem perguntar.** Nos modos Fora e Dormindo, o fim de cada volta traz um cartão com o que o agente fez sozinho: arquivos alterados, comandos, decisões e as perguntas que viraram decisão ou ficaram guardadas para você. O caderno do projeto reúne esses cartões numa aba própria.
- **Conexão mais estável do tzc no terminal.** O comando tzc no terminal continua conectando mesmo quando o acesso ao núcleo é renovado.

## 0.1.110 · 30/10/2026

- **Backup diário com nome fixo.** O backup de cada projeto mantém sempre o mesmo nome e é sobrescrito a cada dia, sem acumular arquivos no disco ou no Drive. O histórico completo continua dentro dele.

## 0.1.109 · 30/10/2026

- **Pequenos ajustes.** Respostas da busca na web com citações saem num parágrafo só, e o Contexto aparece ao abrir uma sessão antiga. Os discos mostram o espaço livre e o total, e peças iguais do PC aparecem agrupadas. Numa conversa sem projeto, a coluna mostra "Conversa sem projeto" em vez de uma pasta.

## 0.1.108 · 30/10/2026

- **Espelhos da memória.** Escolha até 2 pastas extras (um disco e uma pasta de nuvem, por exemplo) em Configurações → Jeito Thalzeron: cada fato que o agente grava é copiado para elas e conferido. O /dormir confere de novo e aponta qualquer divergência.
- **Backup do dia.** No /dormir, cada projeto do dia ganha um backup completo do git (bundle), verificado pelo próprio git, em cada destino escolhido, além do push; projetos sem git são sinalizados. O agente também faz o backup quando você pede.

## 0.1.107 · 30/10/2026

- **Conectores prontos para ligar.** Em Configurações → Conectores, a linha Prontos para ligar adiciona num clique conectores já testados: Meta Ads (anúncios do Facebook e do Instagram), Linear, Atlassian (Jira e Confluence) e DeepWiki. Depois, o Entrar abre a tela do serviço para você autorizar.

## 0.1.106 · 30/10/2026

- **Fixar, não lida e concluída.** Na barra lateral, fixe sessões no topo (a seção Fixadas também aceita arrastar), marque como não lida ou como concluída pelo menu da sessão. Uma sessão que termina enquanto você olha outra fica marcada como não lida até ser aberta.
- **O agente organiza a barra lateral.** O agente fixa e marca sessões, lista os grupos, move sessões entre grupos, renomeia e desfaz grupos, sem apagar nada.

## 0.1.105 · 30/10/2026

- **Sugestões de plugins e skills.** Quando uma tarefa ficaria repetível com um plugin ou uma skill, o agente procura na loja e nas skills que você já tem e sugere num cartão, com o motivo e o botão Instalar. O clique é sempre seu.
- **Coluna da sessão adaptável.** A coluna começa aberta em telas largas e recolhida nas comuns, para não espremer a conversa; o botão da barra superior a abre em qualquer tela.
- **Corrigido: clique logo após abrir o TZC.** Abrir uma sessão antes de o TZC terminar de iniciar fazia a tela voltar ao Início. Agora a sua escolha é mantida.

## 0.1.104 · 30/10/2026

- **Pull requests que se consertam sozinhos.** Peça ao agente para vigiar um pull request com o conserto ligado: quando o CI falha, surge um conflito ou chega uma revisão, ele lê o log, corrige, testa e envia no mesmo branch, em até 5 tentativas, e depois relata o que tentou. A vigia termina sozinha quando o PR é mesclado ou fechado. O agente também consulta o estado do PR e liga o merge automático, quando você pede.

## 0.1.103 · 30/10/2026

- **Monitor do PC em tempo real.** Na coluna da sessão, o cartão Recursos mostra CPU, GPU (com temperatura), RAM, VRAM e discos. Um clique abre o painel completo: cada thread da CPU, a memória, o gráfico do último minuto, cada disco com a pasta do projeto destacada, as peças do PC e o aviso de hardware novo. "Manter fixo como coluna" o deixa de cima a baixo, num painel que você arrasta ou destaca em outro monitor.
- **Coluna da sessão.** Os cartões Ambiente, Contexto, Recursos, Alterações e Tarefas em segundo plano, cada um recolhível; o botão na barra superior mostra e esconde a coluna.
- **Layout redimensionável.** Arraste a borda da barra lateral, da coluna da sessão e de cada painel até o tamanho que quiser, e cada um guarda a sua largura. Duplo clique na borda restaura o padrão, e as setas do teclado também ajustam. Ideal para monitores largos.

## 0.1.102 · 30/10/2026

- **O agente conhece o seu PC.** O TZC identifica as peças do PC direto pelo Windows (CPU, cada GPU, cada pente de RAM, cada disco) e percebe na hora quando uma é trocada. Em cada conversa, o agente sabe o uso da CPU, da RAM, da GPU e dos discos e a folga para um build pesado, e pode consultar o histórico dos últimos minutos. A temperatura da GPU sai sem programa extra; a da CPU, pelo HWiNFO.
- **PDF: preencher, juntar, separar e girar.** O agente lê e preenche formulários em PDF (com acentos e, se você pedir, travando o resultado), junta vários PDFs, separa e gira páginas. O original nunca é sobrescrito.

## 0.1.101 · 30/10/2026

- **O agente controla a janela e a máquina.** O agente vê o layout da janela, abre e fecha painéis (terminal, diff, navegador, arquivos), abre sessões e recolhe a barra lateral. Na máquina, abre um arquivo no VS Code na linha certa, mostra arquivos na pasta, informa o espaço dos discos, impede o PC de dormir numa tarefa longa e traz as mudanças da base para o branch, avisando os conflitos.
- **Gráficos na conversa.** O agente desenha gráficos, diagramas e tabelas direto na conversa, numa moldura isolada.

## 0.1.100 · 30/10/2026

- **Páginas com dados compartilhados.** Uma página publicada pelo agente pode guardar dados compartilhados entre os visitantes: uma lista de inscrição, um placar, um formulário de pedidos. Quem vê lê, quem entrou com o Google escreve, e o agente lê e organiza os dados. A página continua isolada e só acessa os dados com as regras de quem está vendo.

## 0.1.99 · 30/10/2026

- **Páginas publicadas com link.** O agente publica páginas (relatórios, painéis, prévias) com link na sua conta, privadas por padrão; você libera para quem tiver o link ou para e-mails específicos. Republicar cria uma nova versão no mesmo link e mantém as anteriores. Os visitantes podem comentar, e o agente lê os comentários.

## 0.1.98 · 30/10/2026

- **Gmail completo.** O agente lê conversas inteiras, organiza rótulos (aplicar, remover, criar, renomear, apagar), arquiva, envia para a lixeira (sem apagar definitivamente), marca spam e cuida dos rascunhos. Enviar, responder e encaminhar, só quando você pedir expressamente. Para organizar e enviar, reconecte o Google uma vez em Configurações → Conectores.
- **Conectores com login.** Conectores que exigem login, como o Linear e o Atlassian, agora entram de verdade: o botão Entrar abre a tela do serviço no navegador, e o TZC guarda o acesso no cofre e o renova sozinho.

## 0.1.97 · 30/10/2026

- **O agente gerencia as sessões.** O agente vê o uso e o custo de uma sessão (com as ferramentas usadas), os eventos em ordem, exporta a conversa em Markdown ou JSON e arquiva sessões concluídas. Quando percebe uma tarefa à parte, ele propõe uma sessão nova num cartão: Abrir sessão (já com o pedido) ou Fazer aqui. A escolha é sua.

## 0.1.96 · 30/10/2026

- **Resumo de fim de tarefa, capítulos e arquivos.** Ao terminar um trabalho, o agente fecha com um cartão: o que ficou pronto, o que falta e, quando a decisão é sua, uma pergunta com até dois botões (o primeiro é a recomendação dele). Ele marca capítulos quando o trabalho muda de fase e entrega os arquivos relevantes com Abrir e Mostrar na pasta; programas só aparecem na pasta, nunca abrem sozinhos.

## 0.1.95 · 30/10/2026

- **Despertador do agente.** O agente agenda lembretes para ele mesmo na conversa: uma vez, repetidos ou daqui a alguns minutos, para voltar a uma espera longa sem ficar conferindo. Os lembretes sobrevivem ao fim da volta e a reinícios do TZC e chegam com o ⏰; os repetidos expiram em 7 dias.

## 0.1.94 · 30/10/2026

- **Modo de ensinar.** Peça ao agente para ensinar algo num programa: ele mostra uma dica na tela, ao lado do ponto certo, e espera você clicar em Próximo para executar aquele passo e seguir. Sair encerra tudo. O cartão aparece sem tirar o foco do que você está digitando.

## 0.1.93 · 30/10/2026

- **O agente usa o seu PC.** Em qualquer conversa, o agente pode usar os programas do Windows: prints de qualquer monitor, zoom, cliques, arrastar, rolar, digitar, atalhos, abrir programas pelo nome, a área de transferência e várias ações numa ida só. Ele pede acesso a cada programa, e você aprova. Navegadores ficam só para leitura (para navegar, ele usa o navegador do TZC ou o seu Chrome), e terminais e editores de código só para ver e clicar.

## 0.1.92 · 30/10/2026

- **Servidor de desenvolvimento pelo agente.** O agente sobe o servidor do projeto (npm run dev e afins), espera a porta responder e abre a página no navegador do TZC; lê os logs (ou só os erros) e para o servidor ao terminar. Quando o TZC fecha, nenhum servidor fica para trás.
- **Gravação em GIF.** O agente grava o que faz no navegador num GIF, para você rever ou compartilhar. O arquivo fica na pasta dos arquivos grandes.

## 0.1.91 · 30/10/2026

- **Seu Chrome com o navegador completo.** A extensão do TZC para o Chrome ganha tudo o que o navegador do agente tem: JavaScript, busca por texto, formulários, teclado, mouse, rolagem, zoom, console e rede, tamanho de celular, tema, envio de arquivos e ações em lote. Com o painel da extensão aberto, o agente usa o seu Chrome respeitando os sites que você bloqueou ou deixou só para leitura.

## 0.1.90 · 30/10/2026

- **Navegador do agente completo.** O agente faz tudo no navegador do TZC: roda JavaScript, encontra elementos pelo texto, preenche formulários, usa o teclado e o mouse, rola, amplia prints, lê o console e a rede (com o corpo das respostas), simula celular e tema escuro, gerencia abas e envia arquivos. Várias ações vão numa ida só. Com a janela do TZC atrás de outra, as teclas vão direto à página, sem tirar o seu foco.

## 0.1.89 · 30/10/2026

- **Passo a passo do que só você faz.** Quando o próximo passo é seu e fora do TZC (um site, um painel, o celular), a conversa mostra um cartão com os passos numerados, o que vai aparecer em cada um, o que é irreversível e o porquê. Terminou? Clique em Fiz, e o agente segue.
- **Unificar sem perder.** Depois de resumir, juntar ou reescrever um documento, o agente confere item a item com o original, com atenção obrigatória a números, datas, horas e nomes. Um mapa mostra o que ficou, o que ficou pela metade e o que se perdeu, e ele corrige antes de concluir.
- **Botões nos cartões.** Retomar de onde parou e Fiz agora aparecem como botões.

## 0.1.88 · 30/10/2026

- **Chave colada no chat vai ao cofre.** Colou a chave de um cérebro (Anthropic, OpenRouter, Google ou Groq) na conversa? O TZC remove do pedido, confere com o provedor e guarda no Cofre do Windows; uma chave recusada nunca substitui a válida. O aviso mostra só o final da chave (•••3c2).
- **Chaves sincronizadas com o TZC Web.** A chave guardada no site desce para o cofre do PC quando é a mais recente, conferida com o provedor. E a chave nova colada no PC sobe para a conta, se aquele cérebro já usa a conta.
- **Estilo Thalzeron.** Em Configurações → Jeito, o estilo de saída "Thalzeron": direto e sincero, ensina o porquê, decide com tabela e marca o que é provisório. Ele fica num arquivo de texto que você pode ler e editar.
- **Sessão protegida contra limpeza.** Com a opção ligada (padrão), o /clear vira compactação: a conversa é resumida e continua, nunca apagada. Para começar do zero, use Nova sessão.
- **Pasta dos arquivos grandes.** Em Configurações → O TZC no Windows, escolha onde ficam os modelos, as conversas sem projeto, os artefatos e os builds. Vale ao reiniciar o TZC, e o que já está na pasta antiga permanece lá.

## 0.1.87 · 30/10/2026

- **Portfólio de todos os projetos.** No Início, o botão "Portfólio ↗" abre uma página com todos os seus projetos: há quanto tempo cada um está parado, as sessões esperando você, os pedidos abertos, as decisões provisórias, as peças do Contrato pendentes, o git e o próximo passo do RETOMAR. O que depende de você vem primeiro, e o Dev Chefe recebe a mesma visão.

## 0.1.86 · 30/10/2026

- **Comparação lado a lado com a prévia.** Com o Contrato ligado, quando o agente termina uma peça, o TZC abre a página lado a lado: a prévia que você aprovou e a tela construída, no mesmo tamanho. "Está igual" fecha a peça; "Não está" abre um campo para você dizer o que mudar, e o agente ajusta. O veredito é sempre seu, e o agente é lembrado se tentar terminar com peças pendentes.

## 0.1.85 · 30/10/2026

- **Contrato do projeto.** Na lista viva, a opção "Contrato" (por projeto, desligada por padrão): cada prévia que você escolhe com /previa vira uma peça do contrato (C1, C2…), com a opção aprovada como gabarito. O agente constrói a peça igual à prévia e a marca como feita; quem confirma que ficou igual é você. O caderno do projeto ganhou a aba Contrato.

## 0.1.84 · 30/10/2026

- **Jeito Thalzeron por assunto.** Em Configurações → Jeito Thalzeron, as opções agora se dividem em quatro assuntos (resumos e revisões, perguntas, projetos e Dev Chefe), mais fáceis de encontrar.

## 0.1.83 · 30/10/2026

- **Reativar um projeto parado.** Ao abrir uma sessão num projeto sem commit há 14 dias ou mais, o aviso 💤 mostra há quanto tempo ele está parado. Com /reativar (ou "Reativar o projeto" no + da caixa), antes de mexer no código, o agente levanta o estado real (git, build, testes), revisa o backlog, pesquisa o que mudou no mercado e atualiza o RETOMAR com o resumo e o próximo passo.
- **Jeito Thalzeron num clique.** Em Configurações → Jeito Thalzeron, "Ligar o Jeito inteiro" ativa todas as práticas de uma vez (boletins, revisões, relatório, Cascata, freio, kit do projeto e guarda do rumo), e "Voltar ao de fábrica" restaura os padrões.
- **Corrigido: relatório da manhã.** O relatório da manhã vai só às sessões em que o agente trabalhou durante a noite, e não mais às conversas abertas de manhã.

## 0.1.82 · 30/10/2026

- **Kit do projeto.** Uma sessão numa pasta de projeto sem RETOMAR.md ganha o kit Thalzeron: um índice do projeto (o que ler primeiro e onde fica cada informação) e o RETOMAR (onde paramos e o próximo passo); numa pasta vazia, também o git com o primeiro commit. Numa pasta com arquivos, o TZC só cria o que falta e nunca sobrescreve nada. Ligado por padrão, em Configurações → Jeito.

## 0.1.81 · 30/10/2026

- **Retomada depois de uma queda.** Se a luz cair, o PC desligar ou o TZC fechar no meio de um trabalho, a sessão interrompida mostra um cartão com a hora da parada e o que ficou sem commit. "Retomar de onde parou" faz o agente conferir onde estava e terminar o que faltava, sem refazer o que já está pronto. Nos modos Dormindo trabalhando e Fora trabalhando, a retomada é automática.
- **Prazo que sobrevive à queda.** Uma estimativa de prazo aberta antes de uma queda continua aberta depois dela, e o agente mede o tempo real mesmo após retomar.

## 0.1.80 · 30/10/2026

- **/dormir com "Pode desligar" conferido.** Escreva /dormir (ou diga que vai dormir): o agente leva o trabalho a um ponto estável, salva tudo e anota o próximo passo no RETOMAR. Em seguida, o TZC confere item por item (nenhuma sessão nem tarefa rodando, cada projeto do dia com tudo no git e o RETOMAR atualizado) e só então mostra o cartão verde "Pode desligar". Se faltar algo, o cartão âmbar diz o quê.

## 0.1.79 · 30/10/2026

- **Guarda do rumo e Ideias.** Ative em Configurações → Jeito Thalzeron: quando um pedido abrir um rumo novo no meio de outro trabalho, o agente mostra o custo da troca (o que para, quanto atrasa, que decisão contradiz) e recomenda anotar em Ideias e seguir o plano. As ideias ficam na aba Ideias do caderno e voltam quando o plano terminar.

## 0.1.78 · 30/10/2026

- **Caderno de cada projeto.** Na lista viva, o botão "Caderno ↗" abre a página do projeto no navegador do TZC: Agora (onde paramos e as sessões), Pedidos, Decisões, Boletins, Provas e Prazos. Enquanto o projeto trabalha, o caderno se atualiza sozinho a cada minuto.
- **Conferência das páginas locais.** O navegador do TZC abre endereços http locais, como as prévias e os artefatos do próprio TZC, e o agente confere o que publicou.

## 0.1.77 · 30/10/2026

- **Prévia com opções antes do código.** Escreva /previa e o que você quer (ou ative "Prévia" no + da caixa): o agente cria 2 ou 3 versões diferentes da tela, e o TZC mostra todas lado a lado, cada uma com o porquê e o botão "Escolher esta". A sua escolha entra no livro das decisões, e só então o agente escreve o código.

## 0.1.76 · 30/10/2026

- **Retro: cada correção vira trava.** Escreva /retro (ou ative "Retro" no + da caixa): o agente relê o dia, identifica o que você corrigiu e propõe, para cada correção, uma trava que impede o erro de voltar. Você escolhe num lote de botões, e ele cria as travas, que ficam visíveis em Configurações → Permissões e modos.
- **Travas que não se contornam.** Quando uma trava sua recusa um comando, o agente não busca outro caminho nem oferece ignorá-la: se for mesmo preciso, ele pede que você mude a trava.

## 0.1.75 · 30/10/2026

- **Suas travas.** Em Configurações → Permissões e modos, "As suas travas": quando o agente for rodar um comando com um texto que você definiu (ou uma expressão regular, para casos mais finos), o TZC nega, pergunta ou só avisa, e explica o porquê. Um erro corrigido uma vez vira trava, sem código, e não se repete.
- **Modo noturno preparado.** No modo Dormindo, trabalhando, o agente já começa sabendo que ninguém vai responder e guarda direto o que depende de você, sem tentar perguntar antes.

## 0.1.74 · 30/10/2026

- **Modos Em casa, Dormindo e Fora.** No menu do seu nome, escolha o modo: Em casa, Dormindo, Dormindo trabalhando ou Fora trabalhando. O modo aparece ao lado do seu nome, e nos modos noturnos só o urgente avisa.
- **Dormindo, trabalhando: perguntas para a manhã.** Neste modo, o agente não para esperando você: o que é reversível ele decide pela recomendação (e registra no livro das decisões), e o que depende de você vira uma pergunta guardada, com o aviso 🌙. No horário do relatório da manhã, as perguntas chegam num lote de botões, e o modo volta a Em casa.
- **Prova também para edições pelo terminal.** Arquivos de código criados ou alterados pelo terminal (com >, tee, sed -i, Set-Content…) também exigem a prova antes de o agente terminar, como já acontecia com a edição direta.

## 0.1.73 · 30/10/2026

- **O que é só seu.** Em Configurações → Jeito Thalzeron, a lista do que depende só de você (por padrão: gastar dinheiro, senhas e contas, ações irreversíveis, publicar em seu nome, chaves e o sistema). O agente pergunta antes de qualquer item da lista; o resto ele decide, faz e avisa depois.
- **Freio das perguntas.** Antes de incomodar você, a primeira pergunta de cada volta volta ao agente para ele conferir o livro das decisões e a lista do que é só seu; se a resposta já existe ou não depende de você, ele decide. Quando pergunta, a primeira opção é a recomendação dele, com o porquê de cada uma. Ative ou desative em Configurações → Jeito Thalzeron.

## 0.1.72 · 30/10/2026

- **Livro das decisões.** Quando você decide algo do projeto (um rumo, uma escolha de produto ou técnica), o agente registra no livro das decisões, com as suas palavras e o porquê (D1, D2…). Toda sessão do projeto consulta o livro antes de propor, para não rediscutir o que já foi decidido. Na lista viva, veja a aba "Decisões".
- **PROVISÓRIO e DEFINITIVO.** Cada decisão nasce PROVISÓRIA. Um clique no selo a promove a DEFINITIVO: daí em diante, o agente não a muda nem revoga sem perguntar a você. O ✕ revoga.

## 0.1.71 · 30/10/2026

- **O agente sabe a data e a hora.** Cada mensagem leva ao agente a data e a hora do seu PC, para que registros, prazos e relatórios saiam sempre com o horário certo. A conversa mostra só o que você escreveu.
- **Contexto preservado na compactação.** Quando a conversa fica longa e é resumida, o TZC devolve ao agente o RETOMAR do projeto e os seus pedidos ainda abertos, com o aviso 📌 na conversa.

## 0.1.70 · 30/10/2026

- **Privacidade e dados.** Nova seção nas Configurações: onde fica cada dado (no seu PC, na sua conta ou em lugar nenhum), exportação completa num arquivo (conversas, memória e preferências, sem as chaves) e exclusão das conversas, da memória ou de tudo, com confirmação. Também mostra o que nunca sai do seu PC.

## 0.1.69 · 30/10/2026

- **Notificações e sons.** Nova seção nas Configurações: escolha quais avisos do Windows aparecem (concluído, aguardando aprovação, parado), ative o não perturbe no horário que quiser (pedidos de aprovação passam sempre) e defina a hora do relatório da manhã.
- **Sons da Orbe.** Três sinais curtos e suaves: tarefa concluída, pergunta esperando você e erro. Vêm desligados; ative em Notificações e sons, ajuste o volume e ouça cada um antes.

## 0.1.68 · 30/10/2026

- **A Bancada vigia os seus sites.** Na Bancada de Provas, "＋ Vigiar o endereço atual" faz o TZC conferir aquele endereço a cada hora, numa janela invisível, sem ocupar o seu navegador. Se algo quebrar, o Windows avisa, e o clique abre o relatório. A vigia nunca clica em botões de sites reais, e cada uma mostra o último resultado, "Rodar agora" e o relatório.

## 0.1.67 · 30/10/2026

- **Relatório de cada bateria.** Cada bateria da Bancada de Provas gera uma página independente: o endereço, a hora, o resumo, os passos de cada receita com o porquê de cada falha e o console da página. "Abrir o relatório" abre no seu navegador, para guardar, imprimir em PDF ou compartilhar.

## 0.1.66 · 30/10/2026

- **Boletins de trabalhos longos.** Em trabalhos longos, o agente deixa um boletim na conversa a cada 15 minutos (o intervalo é ajustável): o que foi feito, o que faz agora, o próximo passo, os bloqueios e o prazo, em até 5 linhas. O último boletim também aparece no pé da lista. Ative em Configurações → Jeito Thalzeron.
- **Lembretes de ritmo.** Escreva um lembrete, como "rode os testes e meça o prazo", e o intervalo: ele chega ao agente durante o trabalho, sem interromper nada. Até 10 lembretes, em Configurações → Jeito Thalzeron.
- **Conversa mais limpa.** Mensagens automáticas do TZC durante o trabalho (revisões, pedidos de boletim, lembretes) aparecem como uma linha discreta, e não como mensagens suas; o texto completo abre no clique.

## 0.1.65 · 30/10/2026

- **Bancada de Provas: 5 receitas novas.** Rede (cada pedido que falha: imagens ausentes, APIs com erro), Acessibilidade (título, idioma, imagens sem descrição, botões sem nome, campos sem rótulo e título principal, cada um com o porquê), Desempenho (tempo de carregamento, exibição do conteúdo principal e peso da página), Explorar (abre as outras páginas do site e encontra as quebradas) e Bateria completa, que roda tudo de uma vez.
- **Bateria mais fácil de ler.** Na bateria completa, cada receita tem o seu título, e o porquê de cada falha aparece embaixo do passo, sem precisar passar o mouse. Tempos e pesos pequenos aparecem em milissegundos e kB.

## 0.1.64 · 29/10/2026

- **Nenhum pedido fica sem resposta.** Se o agente tentar terminar sem marcar os pedidos que você fez nesta volta, o TZC pede que ele os marque: feito, com a prova, ou aguardando, quando depende de você. O aviso 📋 aparece na conversa, uma vez por volta, e o trabalho não é refeito.
- **Consertar com o agente, provado de ponta a ponta.** Na Bancada de Provas, "Consertar com o agente" abre uma sessão na pasta do seu app com o defeito e o erro do console. O agente encontra a causa, corrige, abre a página e clica para provar, e a Regressão confere de novo.

## 0.1.63 · 29/10/2026

- **Bancada de Provas: o TZC testa os seus apps.** Na barra lateral, a Bancada de Provas: informe o endereço do seu app web e rode a bateria. O TZC abre a página, clica em cada botão como um usuário real e mostra o que respondeu, o que deu erro e o que não fez nada, pulando botões perigosos como "Excluir conta". Cada defeito vem explicado em português simples, com o erro do console; "Virar trava" guarda o teste, e a Regressão confere de novo depois do conserto.
- **Conserto com o cérebro que você escolher.** As receitas da Bancada não usam modelo algum; o modelo só entra no conserto, numa sessão na pasta do seu código, com o problema e o console já explicados. Escolha só local (sem custo), só pago ou uma combinação.

## 0.1.62 · 29/10/2026

- **Configurações reorganizadas.** Quatro grupos (Você, Trabalho, Conexões e Sistema), com ícones e uma busca que encontra o conteúdo de cada seção. A antiga aba Geral virou Jeito Thalzeron e O TZC no Windows; tema e modo ficam em Aparência.
- **Perfil e 12 avatares.** Em Configurações → Perfil: a sua foto (recortada automaticamente) ou um dos 12 avatares de dev (terminal, chaves, branch, lambda, foguete…), o nome e como o TZC deve chamar você. O avatar e o nome aparecem no rodapé, e o agente passa a usar o nome escolhido.
- **Fundo vivo.** Manchas de luz na cor do tema se movem devagar atrás da janela e ficam mais vivas enquanto o agente trabalha. Intensidade sutil, média ou viva, e densidade compacta, em Configurações → Aparência.

## 0.1.61 · 29/10/2026

- **Relatório com perguntas em lote.** A opção "Relatório" no + da caixa: o que foi feito com a prova, uma avaliação honesta, o que mudar e as decisões difíceis, com as perguntas para você num cartão de botões no fim. No horário do relatório da manhã, as sessões que trabalharam à noite fazem o relatório sozinhas.
- **Corrigido: painel Navegador destacado.** Fechar a janela própria do painel Navegador não deixa mais a página por cima da conversa nem abre uma aba repetida.

## 0.1.60 · 29/10/2026

- **Revisão até não sobrar nada.** Quando o agente revisa o próprio trabalho, cada rodada deixa uma marca no pé da lista ("Revisão nº 2 · 1 tarefa nova") até a rodada limpa ("limpa: nada novo"). Assim você vê que ele não parou antes da hora.

## 0.1.59 · 29/10/2026

- **Revisão automática a cada 30 minutos.** Em trabalhos longos, a cada 30 minutos o agente relê os seus pedidos e confere a Cascata sem parar o que está fazendo; o que tinha ficado esquecido entra na lista, e o selo "Revisão das HHhMM · N esquecidos" aparece no pé dela. O intervalo e a opção ficam em Configurações → O seu jeito.

## 0.1.58 · 29/10/2026

- **Cascata: nenhum pedido fica para trás.** Cada pedido que você manda vira um item, com as suas palavras, na aba "Seus pedidos" da lista, reunindo todas as conversas do projeto. O agente marca o que está em andamento e o que terminou, com a prova; só você pausa ou cancela. Ative ou desative em Configurações → O seu jeito.

## 0.1.57 · 29/10/2026

- **Prazos que aprendem.** Na lista de tarefas, o passo em andamento mostra a estimativa ("≈ 3 min") e o concluído mostra quanto levou: verde no prazo, âmbar quando atrasou. O TZC mede cada passo sozinho, e as estimativas ficam mais precisas a cada tarefa.

## 0.1.56 · 29/10/2026

- **A janela abre como você deixou.** O TZC guarda o tamanho, o monitor, o estado maximizado e a tela cheia, e reabre igual, inclusive depois de uma atualização. Se o monitor não estiver mais ligado, abre no principal.
- **tzc no terminal com a lista viva.** O comando tzc mostra a lista de tarefas (concluídas, em andamento e próximas) e o que o agente faz agora, com o tempo. Com a saída redirecionada para um arquivo ("tzc ... > saida.txt"), sai só o texto, sem cores.

## 0.1.55 · 29/10/2026

- **Lista viva.** As tarefas do agente fixadas embaixo da conversa: o ✓ ao concluir um passo, o indicador girando no passo em andamento, o círculo tracejado nos próximos e o progresso ("3 de 7"). Clique no título para recolher.
- **Atividade do agente em tempo real.** A linha de atividade mostra a ação e o alvo ("Executando · Rodando os testes", "Pesquisando · preço do dólar", "Esperando você") com o tempo do turno, e a Orbe muda a animação conforme o tipo: ler, buscar, pesquisar na web, criar, editar, executar, subagente ou esperando você.

## 0.1.54 · 29/10/2026

- **Modelos locais no site e na extensão.** No TZC Web (o site e a extensão do Chrome), o menu do cérebro ganhou o grupo "No seu PC", com os modelos do Ollama, do llama.cpp e do LM Studio do seu computador. A conversa fica na sua conta, e o TZC do PC leva a mensagem ao modelo local, sem internet e sem custo. Basta o TZC estar aberto e conectado à conta.

## 0.1.53 · 29/10/2026

- **Dev Chefe sempre à mão.** O botão do Dev Chefe fica fixo no topo da barra lateral, logo abaixo dos atalhos. Se ele ainda não existe, o clique o cria e abre.
- **Corrigido: versão nos Apps instalados.** A lista de Apps instalados do Windows passa a mostrar a versão correta do TZC depois das atualizações.

## 0.1.52 · 29/10/2026

- **Nova sessão sem janela na frente.** Criar uma sessão abre a tela inicial, como num chat: a caixa no centro e, embaixo, a pasta (ou só conversa), o cérebro com o esforço e o modo, cada um num menu. Escreva e aperte Enter: a sessão nasce com essas escolhas e ganha o título da sua mensagem. Embaixo, os artefatos recentes.
- **Opções no lugar dos comandos com barra.** No + da caixa, ative uma opção para a próxima mensagem: Maratona (trabalha sozinho até terminar), Objetivo (só para quando cumprir), Evoluir (melhora o código com o guardião) e Pergunta de lado. A rotina de dormir também está ali, sem precisar digitar comandos com barra.

## 0.1.51 · 29/10/2026

- **Central de ajuda.** A conversa "Pergunte ao TZC" abre a central de ajuda: perguntas prontas por assunto (um clique pergunta), a apresentação guiada, as novidades e os tópicos da Ajuda.
- **Corrigido: erro ao abrir o terminal.** O erro em vermelho que aparecia ao abrir o terminal não aparece mais.

## 0.1.50 · 29/10/2026

- **Corrigido: conversa de ajuda na abertura.** Ao abrir o TZC, a conversa "Pergunte ao TZC" não fica mais carregada por baixo do Início: o seu pedido vai para o seu trabalho, e o Voltar só acende quando há para onde voltar.

## 0.1.49 · 29/10/2026

- **O orbe reconhece o TZC.** Sobre a janela do TZC, o orbe mostra o logo e o nome do TZC, em vez de um ícone genérico.
- **Pergunte ao TZC.** Uma conversa sempre disponível, no grupo "Ajuda do TZC", para tirar dúvidas sobre o próprio TZC. Ponha o orbe sobre o TZC e pergunte, ou abra a conversa pela barra lateral.

## 0.1.48 · 29/10/2026

- **Aba Conta mostra o que está na nuvem.** Em Configurações → Conta, a linha "Usar fora do PC" mostra quais chaves já estão na sua conta e quando foram enviadas, com o sinal verde, e o botão vira "Atualizar as chaves". O resultado de cada ação aparece na própria linha.

## 0.1.47 · 29/10/2026

- **Conta Google no TZC.** Em Configurações → Conta, entre com o Google. É ela que conecta este TZC ao TZC Web: o site e a extensão do Chrome.
- **Usar fora do PC.** Na mesma aba, "Subir as chaves" envia as chaves dos cérebros para a sua conta: o site e a extensão funcionam sem este PC ligado, e só a sua conta tem acesso.
- **TZC Web.** thalzeron-code-tzc.web.app/app: o TZC no navegador, de qualquer computador, com busca na web, leitura de sites e execução de código. As conversas de lá aparecem aqui, no grupo "TZC Web".

## 0.1.46 · 29/10/2026

- **Corrigido: versão nos Apps instalados.** A lista de programas do Windows mostra a versão correta do TZC depois de uma atualização automática.

## 0.1.45 · 29/10/2026

- **Apresentação guiada.** Na primeira vez, depois das boas-vindas, um holofote apresenta cada parte do TZC. Você pode revê-la quando quiser, pelo menu do seu nome.
- **Novidades de cada versão.** Esta tela: a cada atualização, o que mudou, e o botão Mostrar onde fica leva o holofote até cada novidade. Também no menu do seu nome → Novidades do TZC.

## 0.1.44 · 29/10/2026

- **Atualizações mais rápidas.** O TZC procura atualizações a cada 10 minutos, em vez de a cada hora.

## 0.1.43 · 29/10/2026

- **Aviso de atualização acima do seu nome.** Quando há versão nova, aparece a barra de download e, quando pronta, o Reiniciar para atualizar (cerca de 1 minuto, e o TZC reabre sozinho).
- **Atualização automática quando você não está usando.** Sem nada em andamento, nada escrito na caixa e após 5 minutos sem uso, o TZC instala a atualização e reabre como estava, inclusive escondido na bandeja.
- **Ícone próprio e atalho permanente.** O ícone do TZC aparece na barra de tarefas. Você pode fixar o atalho: toda atualização instala no mesmo lugar, e o atalho continua valendo.
