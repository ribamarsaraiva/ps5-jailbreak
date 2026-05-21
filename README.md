# Guia de desbloqueio do PS5 para iniciantes

## 1 - Como sei que o meu PS5 pode ser desbloqueado?
### 1.1 Para desbloquear o PS5 a versão do firmware dele deve estar na tabela abaixo com o indicativo ✅ nas colunas [Kernel exploit] e [Usermode exploit]
| Firmwares            | Kernel exploit                                 | Features                                                                    | Usermode exploit                                                             | External storage                                                                    |
|----------------|------------------------------------------------|-----------------------------------------------------------------------------|------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|
| 1.00 to 1.14   | UMTX ✅<br>Lapse<br>NetControlImpl          | Debug settings✅<br>Etahen❌<br>Kstuff ❌<br>Hypervisor ✅<br>Linux :<b>SOON</b> | WebKit ✅<br>BD-JB ❌<br>mast1c0re ❌<br>Lua ❌<br>Y2JB❌<br>Netflix 'n' hack ❌      | USB drive ✅<br>M.2 ❌<br>USB Extended Storage ❌                                       |
| 2.00 to 2.70   | UMTX ✅<br>Lapse ✅<br>NetControlImpl        | Debug settings✅<br>Etahen✅<br>Kstuff ❌<br>Hypervisor ✅<br>Linux :<b>SOON</b> | WebKit ✅<br>BD-JB ❌<br>mast1c0re ✅<br>Lua ✅<br>Yarpe✅<br>Y2Jb❌<br> Netflix 'n' hack❌ | USB drive ✅<br> M.2 ❌<br>USB Extended Storage :-<br>(PKGs ✅, move to internal ❌) |
| 3.00 to 3.20   | IPV6 ✅<br>UMTX ✅<br>Lapse<br>NetControlImpl    | Debug settings✅<br>Etahen✅<br>Kstuff ✅<br>Hypervisor :✅<br>Linux ✅              | Webkit ✅<br>BD-JB ✅<br>mast1c0re ✅<br>Lua ✅<br>Yarpe✅<br>Y2JB❌<br> Netflix 'n' hack❌ | USB drive ✅<br>M.2 ❌ <br>USB Extended Storage ✅                                      |
| 4.00 to 4.51   | IPV6 ✅<br>UMTX ✅<br>Lapse ✅<br>NetControlImpl✅ | Debug settings✅<br>Etahen✅<br>Kstuff ✅<br>Hypervisor :✅<br>Linux ✅              | Webkit ✅<br>BD-JB ✅<br>mast1c0re ✅<br>Lua ✅<br>Yarpe✅<br>Y2JB✅<br>Netflix 'n' hack✅  | USB drive ✅<br>M.2 up to 4 TB ✅<br>USB Extended Storage ✅                             |
| 5.00 to 5.50   | UMTX ✅<br>Lapse✅<br>NetControlImpl✅                | Debug settings✅<br>Etahen✅<br>Kstuff ✅<br>Hypervisor✅<br>Linux✅                 | Webkit ✅<br>BD-JB ✅<br>mast1c0re ✅<br>Lua ✅<br>Yarpe✅<br>Y2JB✅<br>Netflix 'n' hack✅  | USB drive ✅<br>M.2 up to 4 TB ✅<br>USB Extended Storage ✅                             |
| 6.00 to 7.61   | UMTX ✅<br>Lapse✅<br>NetControlImpl✅                | Debug settings✅<br>Etahen✅<br>Kstuff ✅<br>Hypervisor ❌<br>Linux:❌         | Webkit ❌<br>BD-JB ✅<br>mast1c0re ✅<br>Lua ✅<br>Yarpe✅<br>Y2JB✅<br>Netflix 'n' hack✅  | USB drive ✅<br>M.2 up to 4 TB ✅<br>USB Extended Storage ✅                             |
| 8.00 to 10.01  | Lapse✅<br>NetControlImpl✅                      | Debug settings ✅<br>Etahen✅<br>Kstuff ✅<br>Hypervisor ❌<br>Linux:❌        | Webkit ❌<br>BD-JB ❌<br>mast1c0re✅<br>Lua ✅<br>Yarpe✅<br>Y2JB✅<br>Netflix 'n' hack✅       | USB drive ✅<br>M.2 up to 8 TB ✅<br>USB Extended Storage ✅                             |
| 10.20 to 12.00 | NetControlImpl✅<br>Kqueueex ✅                  | Debug settings ✅<br>Etahen✅<br>Kstuff ✅<br>Hypervisor ❌<br>Linux:❌        | Webkit ❌<br>BD-JB ❌<br>mast1c0re✅<br>Lua ✅<br>Yarpe✅<br>Y2JB✅<br>Netflix 'n' hack✅       | USB drive ✅<br>M.2 up to 8 TB ✅<br>USB Extended Storage ✅                             |
| 12.02 to 12.40 | Kqueueex ✅                                     | Debug settings✅<br>Etahen ❌<br>Kstuff ❌                                     | Webkit ❌<br>BD-JB ❌<br>mast1c0re✅<br>Lua ✅<br>Yarpe✅<br>Y2JB✅<br>Netflix 'n' hack✅       | USB drive ✅<br>M.2 up to 8 TB ✅<br>USB Extended Storage ✅                             |
| 12.60 to 12.70 | Kqueueex ✅                                     | Debug settings✅<br>Etahen ❌<br>Kstuff ❌                                     | Webkit ❌<br>BD-JB ❌<br>mast1c0re✅<br>Lua ✅<br>Yarpe✅<br>Y2JB❌<br>Netflix 'n' hack❌       | USB drive ✅<br>M.2 up to 8 TB ✅<br>USB Extended Storage ✅                             |
| 13.00 to 13.20 | N/A                                            | Debug settings ❌<br>Etahen ❌<br>Kstuff ❌                                    | Webkit ❌<br>BD-JB ❌<br>mast1c0re✅<br>Lua ✅<br>Y2JB❌<br>Netflix 'n' hack❌             | USB drive ✅<br>M.2 up to 8 TB ✅<br>USB Extended Storage ✅                             |
## 2 - Como faço para saber em qual firmware o PS5 pode estar mesmo sem ligar o videogame?
Basta acessar o endereço https://www.controlserial.com/ e colocar o número de serie que está na caixa lacrada do videogame (ex. S01-G2121W9D1234)

<img width="300" height="400" alt="image" src="https://github.com/user-attachments/assets/80ba9687-e75d-4ba1-b2ae-70a7f4378237" />

## X - Referências

### x.1 - Usermod exploit (Ponto de entrada - onde tudo começa)

| # | Exploit | Descrição | Como funciona |
|-|-|-|-|
| x.1.1 | WebKit | Vulnerabilidade no motor do navegador nativo do console | A partir do momento em que o navegador do PS5 acessa uma pagina específica (host) scripts são executados para ativar a falha |
| x.1.2 | BD-JB | Vulnerabilidade de software descoberta no leitor de discos do console | O exploit utiliza uma falha no interpretador de Java nativo do leitor de Blu-ray do PS5 para escapar do sistema de segurança |
| x.1.3 | mast1c0re | O exploit atua através da exploração do emulador de PS2 embutido em jogos de PS2 portados para o PS4/PS5 | Ao modificar o arquivo de salvamento (save) do jogo, é possível corromper o fluxo interno do emulador e injetar instruções para obter controle de execução. |
| x.1.4 | Lua | Um script Lua, inserido através de arquivos de save permite a injeção de códigos no console | Ao carregar um save de jogos com essa falha um script em linguagem lua é executado de forma a induzir a falha e ativar desbloqueio |
| x.1.5 | LUAC0RE | Derivado do método mast1c0re, utiliza o interpretador de linguagem Lua 5.3 para executar comandos no console | O LUAC0RE explora uma vulnerabilidade no compilador Just-In-Time (JIT) dentro do emulador nativo de PlayStation 2 que existe tanto no PS4 quanto no PS5 |
| x.1.6 | Y2JB | Versões antigas do youtube contem versões defasadas do webkit dentro delas | Ao substituir o cache interno desse aplicativo é possivel fazer com que o webkit interno execute scripts de desbloqueio |
| x.1.7 | Netflix 'n' hack | Versões antigas do netflix contem versões defasadas do webkit dentro delas | A técnica funciona injetando código JavaScript através de um ataque Man-in-the-Middle (MITM) ao interceptar solicitações da rede enquanto o aplicativo da Netflix é executado|
| x.1.8 | Yarpe | da mesma forma que jogos lua só que com script python | Ao carregar um save de jogos com essa falha um script em linguagem pyhthon é executado de forma a induzir a falha e ativar desbloqueio |

### x.2 - Principais Payloads

| # | Payload | Descrição | Github/link |
|-|-|-|-|
| x.2.1 | kstuff | Payload responsável por permitir ao PS5 desbloqueado executar Homebrew (Apps), executar backups de jogos de PS4 (FPKG) e PS5 | https://github.com/EchoStretch/kstuff |
| x.2.2 | etaHEN | É um AIO HEN (All-In-One Homebrew Enabler) para PS5, possuindo diversas capacidades como integração com kstuff, executar dumps de PS5(fpkg), PS5, plugins, Direct PKG Installer, Itemzflow, FTP server, Cheats, etc... | https://github.com/etaHEN/etaHEN |
| x.2.3 | ShadowMountPlus | Montador de jogos de PS5 em segundo plano, responsável por pesquisar jogos em locais específicos e criar o ícone do jogo pronto pra jogar, suporta formato pasta, .exfat e .ffpkg, trabalha diretamente com o kstuff lite | https://github.com/drakmor/ShadowMountPlus |
| x.2.4 | np-fake-signin | Responsável por fazer com que o PS5 ache que a conta de usuário já fez login na PSN (fake PSN) | https://git.etawen.dev/earthonion/np-fake-signin/releases |
| x.2.5 | ftpsrv | Cria um servidor ftp no PS5 permitindo conectar por meio de outro dispositivo como por exemplo o PC para transferir arquivos para o PS5 | https://github.com/ps5-payload-|
| x.2.6 | Websrv | Servidor web para PS5, utilizado para iniciar jogos e apps | https://github.com/ps5-payload-dev/websrv |
| x.2.7 | dump_runner | Responsável por permitir a execução de jogos por meio do navegador do PS5, utilizado em conjunto com os payloads Websrv e Kstuff e o App Homebrew Launcher  | https://github.com/EchoStretch/dump_runner |
dev/ftpsrv |
| x.2.8 | BackPork | Responsável por fazer com que o PS5 reconheça que um jogo possui backport | https://github.com/BestPig/BackPork |
| x.2.9 | ps5-linux-loader | Responsável por executar o linux no PS5 | https://github.com/ps5-linux/ps5-linux-loader |
| x.2.10 | lapy_jb_daemon | Responsável por permitir executar o PS5-Xplorer sem precisar carregar o etaHRN | [lapy_jb_daemon](https://cdn.discordapp.com/attachments/1026659785556381786/1507106289350742277/lapy_jb_daemon.elf?ex=6a10b19c&is=6a0f601c&hm=7726496ef187f0e0ac416aa390b37ba7fa98408315c262a3a2b32e087678a3e6&)  |


### x.3 - Principais Homebrews (Aplicativos de PS5)

| # | App | Descrição | Github |
|-|-|-|-|
| x.3.1 | PS5-Xplorer | Explorador de arquivos e pasta do PS5 no estilo Windows Explorer, por ele é possivel  | https://pkg-zone.com/details/LAPY20011 |
| x.3.1 | Homebrew Launcher | Responsável por executar apps e jogos em uma interface de navegador  | https://github.com/ps5-payload-dev/websrv/raw/refs/heads/master/homebrew/IV9999-FAKE00000_00-HOMEBREWLOADER01.pkg |

### x.4 - Principais Ferramentas

| # | App | Descrição | Github |
|-|-|-|-|
| x.3.1 | PS5-Xplorer | Explorador de arquivos e pasta do PS5 no estilo Windows Explorer, por ele é possivel  | https://pkg-zone.com/details/LAPY20011 |


### x.4 - O que preciso saber sobre os backups (jogos) de PS5

| # | Conhecimento sobre backups |
|-|-|
| x.4.1 | Todo jogo tem um firmware mínimo, ou seja, se o firmware minimo de um jogo é 5.00 ele não vai executar em um PS5 cujo firmware é 4.03 a não ser que seja inserido no jogo o chamado <b>Backport</b> |
| x.4.2 | Os backups (dumps) de jogos de PS5 existem em três formatos: <b>Pasta</b>, arquivo <b>.exfat</b> e arquivo <b>.ffpkg</b> |
| x.4.3 | Existem ferramentas que convertem o dump em formato de pasta em .exfat ou .ffpkg |


### x.5 - O que preciso saber sobre backport de jogos de PS5

| # | Conhecimento sobre backports |
|-|-|
| x.5.1 | Para que um jogo funcione com backport o payload de backport deve estar em execução antes do jogo ser aberto |


fonte da tabela de firmwares: https://www.psdevwiki.com/ps5/submit/Serial_Number_guide


