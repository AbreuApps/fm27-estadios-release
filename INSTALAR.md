# Como instalar os Estádios do Brasil 3D no FM27 🏟️

> 💾 **Antes:** copie seus saves (`Documentos/Sports Interactive/Football Manager 27/games`). O mod não mexe no save, mas o BepInEx altera como o jogo abre.

## O que você precisa saber (bem simples)

- O mod troca o estádio 3D da partida pelo estádio real do **time da casa**.
- Cada estádio está ligado a um **clube**. Se o seu time tem estádio no pacote, ele aparece; se não, o jogo usa o estádio padrão dele.
- Para o mod funcionar, o jogo precisa do **BepInEx 6**. Ele é um "carregador de mods": sem ele, nada daqui roda.
- O idioma português só é lido de uma pasta específica (`languages`). Por isso o arquivo da tradução precisa ser copiado para lá.

## Pastas que você vai usar

| | Windows | Linux (Steam/Proton) |
|---|---|---|
| **Pasta do jogo** (onde está o `fm.exe`) | `C:\Program Files (x86)\Steam\steamapps\common\Football Manager 27\` | `~/.local/share/Steam/steamapps/common/Football Manager 27/` |
| **Pasta `languages`** | `Documentos\Sports Interactive\Football Manager 27\languages\` | `~/.local/share/Steam/steamapps/compatdata/4530370/pfx/drive_c/users/steamuser/Documents/Sports Interactive/Football Manager 27/languages/` |
| **Pasta `games`** (saves) | `Documentos\Sports Interactive\Football Manager 27\games\` | mesma de `languages`, trocando `languages` por `games` |

Dica: Steam → botão direito no jogo → *Gerenciar* → *Explorar arquivos locais* abre a pasta do jogo.

---

## Passo 1 — Tenha o BepInEx

**Já usa mods no FM27?** Pule: você já tem.

**Nunca usou mods?** Instale o BepInEx 6 pelo pacote completo da tradução, que já vem pronto:

1. Abra <https://github.com/AbreuApps/fm27-ptbr-release/releases/latest>.
2. Baixe `TraducaoLog-completo-<versão>.zip` e descompacte.
3. Copie o **conteúdo** de `1_COPIAR_PARA_PASTA_DO_JOGO` para a pasta do jogo (ao lado do `fm.exe`).

> Não precisa copiar o `portuguese_br.ltc` desse pacote: o nosso já vem com a tradução 1.2.7.

**Manual:** BepInEx **6, build be.791, Unity IL2CPP, Windows x64** (`BepInEx-Unity.IL2CPP-win-x64-6.0.0-be.791…zip`, em <https://builds.bepinex.dev/projects/bepinex_be>), extraído na pasta do jogo. Cuidado: a página de Releases do GitHub mostra a série 5.x no topo, que **não funciona** no FM27.

**Só no Linux:** Steam → FM27 → Propriedades → *Opções de inicialização*:

```
WINEDLLOVERRIDES="winhttp=n,b" %command%
```

Isso vale se na pasta do jogo existe o arquivo `winhttp.dll`. Se o seu BepInEx veio com `version.dll`, use `version=n,b` no lugar de `winhttp=n,b`.

## Passo 2 — Baixe e descompacte

Baixe `FM27-Estadios-BR-<versão>.zip` em [Releases](https://github.com/AbreuApps/fm27-estadios-release/releases/latest) e descompacte.

## Passo 3 — Instale (feche o jogo antes)

**Extraia a pasta `TaoMods` dentro de `<pasta do jogo>/BepInEx/plugins/`.** É só isso para instalar os estádios e o plugin da tradução.

```
BepInEx/plugins/TaoMods/TaoStadiumMod/TaoStadiumMod.dll   ← deve existir
BepInEx/plugins/TaoMods/TraducaoLog/TraducaoLog.dll
```

Para aparecer o idioma, copie também `TaoMods/languages/portuguese_br.ltc` para a pasta **`languages`** (tabela acima). O jogo só lê idioma de lá.
O save é opcional e vem nas versões anteriores (`save/brazil-a-to-f-desempregado.fm`, para a pasta **`games`**); ele não mudou.

Não solte DLLs direto em `plugins/`: cada mod fica na sua pasta dentro de `TaoMods`.

## Passo 4 — Abra o jogo

A **primeira abertura com o BepInEx demora vários minutos**. Não feche. Depois:

1. **Preferências → Idioma → Português (Brasil)**.
2. Carregue o save ou comece uma carreira com um clube que tenha estádio na [lista](https://github.com/AbreuApps/fm27-estadios-release/blob/main/ESTADIOS.md).
3. Na partida, o estádio 3D do time da casa aparece. 🏟️

## Conferir se carregou

Abra `BepInEx/LogOutput.log` e procure:

- `TaoStadiumMod 0.1.5 (BepInEx 1.1.5)` ✅ o mod dos estádios carregou
- `ganchos de peça por tribuna desligados` ✅ é a correção do fechamento no Windows
- `Skipping [TaoStadiumMod ...]` ou `outra cópia do TaoStadiumMod` ❌ há uma versão antiga sobrando: apague a pasta que o log indicar
- `estádio ... receita '...'` e `malha '...'` ✅ o estádio da partida foi aplicado
- `TraducaoLog` e `DICIONARIO carregado` ✅ a tradução carregou

---

## ⚠️ Problemas conhecidos

É a v0.1.5. **Novidades desta versão:**

- 🆕 **2 estádios novos:** Emirates Stadium (Arsenal), o primeiro de fora do Brasil, e Parque do Bacurau (Cametá).
- 🏟️ **10 estádios atualizados:** Ressacada, Heriberto Hülse e Nubank Parque refeitos (teto alto sobre pilares, fachada em painéis); Vila Capanema com teto plano alto; Alfredão com a pista afinando nos cantos; Alfredo Jaconi, Arena Sicredi e Zinho de Oliveira sem teto na frente da câmera da TV; Arena das Dunas com as aletas do teto encorpadas; Amigão sem pilar no meio da torcida.
- 🎨 **Todos os estádios:** material fosco (o teto não brilha mais como metal) e concreto em tom sujo, mais perto do real.
- 🎥 **Câmera:** o estádio não some mais da tela (nem na câmera livre); o teto do lado da câmera some só na câmera da TV.
- 👥 **Torcida:** tribuna da malha que o jogo deixava com capacidade 0 agora recebe torcida (ex.: tobogã do Serrinha).
- 🤝 **Mods do BassyBoy (Stadium Injection):** onde ele tem estádio instalado em `plugins/CustomStadium`, o estádio dele vale e o nosso fica de fora; nos outros clubes, vale o nosso.
- 🇧🇷 **Tradução 1.2.7** junto.

Defeitos que ainda conhecemos:

- 👻 **Arquibancada vazia:** Independência, Jorjão (duas), Francisco Vasques.
- ➖ Sem clube ligado: João Saldanha, Nazarenão, VGD, Carlos Zamith e Parque do Bacurau.

## Instalar só alguns estádios

Não precisa ficar com os 138. Cada estádio é independente. Dentro de `BepInEx/plugins/TaoMods/TaoStadiumMod`:

- apague de `estadios/` o `<estádio>.json` dos que não quer;
- apague de `estadios3d/` a pasta com o mesmo nome (`<estádio>/`).

Apague sempre as duas coisas juntas. Mantenha `TaoStadiumMod.dll` e a pasta `atmosfera`: sem elas nada funciona. O clube de um estádio apagado volta a usar o estádio padrão do jogo. Para devolver, copie os arquivos de novo do zip.

## Atualizar de uma versão antiga

Apague a pasta `TaoMods` antiga em `BepInEx/plugins` e cole a nova. O save não é afetado. Se existir uma pasta
`TaoStadiumMod` solta direto em `BepInEx/plugins` (de versões bem antigas, fora de `TaoMods`), apague também.

## Remover ou desligar

- **Tirar os estádios e a tradução:** apague `BepInEx/plugins/TaoMods`.
- **Voltar o idioma:** escolha outro em Preferências; para apagar, remova `portuguese_br.ltc` da pasta `languages`.
- **Remover o BepInEx:** apague `BepInEx`, `dotnet`, `doorstop_config.ini`, `.doorstop_version` e `winhttp.dll` da pasta do jogo. Só se nenhum outro mod depender dele.

## Problemas comuns

- **Não aparece "Português (Brasil)":** confira o caminho da pasta `languages` e reinicie o jogo por completo.
- **Tela preta na 1ª abertura:** normal com BepInEx. Espere alguns minutos.
- **Depois de o FM atualizar, nenhum mod carrega** (no log: `Failed to download Unity base libraries` e `no plugins will be loaded`): o BepInEx precisa baixar um arquivo do site dele, que às vezes fica fora do ar. Coloque o `.zip` com o número da versão do Unity que o log mostra (ex.: `6000.3.18.zip`), **sem descompactar**, em `BepInEx/unity-libs/` e abra o jogo de novo. Se o site não abrir, peça o arquivo numa [Issue](https://github.com/AbreuApps/fm27-estadios-release/issues).
- **O estádio do meu time não mudou:** confira em [ESTADIOS.md](https://github.com/AbreuApps/fm27-estadios-release/blob/main/ESTADIOS.md) se o clube está ligado. Confira também se a pasta está em `BepInEx/plugins/TaoMods/TaoStadiumMod` (não solta, não em outro lugar) e se o `LogOutput.log` existe. Se não existe, o BepInEx não carregou: no Windows, confira se extraiu na pasta do `fm.exe`; no Linux, confira a opção de inicialização.
- **O jogo não abre:** apague `BepInEx/plugins/TaoMods`; se abrir, abra uma [Issue](https://github.com/AbreuApps/fm27-estadios-release/issues) com o `LogOutput.log`.
- **O jogo fecha sozinho ao iniciar a partida:** esta versão grava um diagnóstico. Abra uma [Issue](https://github.com/AbreuApps/fm27-estadios-release/issues) (ou mande por onde falou comigo) com estes arquivos, **antes de abrir o jogo de novo**:
  1. `BepInEx/LogOutput.log` (na pasta do jogo);
  2. o `diagnostico_...log` mais novo em `BepInEx/plugins/TaoMods/TaoStadiumMod/` (as linhas `[diag]` mostram em que passo o jogo parou);
  3. `Player.log`, em `C:\Users\<você>\AppData\LocalLow\Sports Interactive\Football Manager 27\` (cole `%USERPROFILE%\AppData\LocalLow` no Explorer);
  4. o nome do clube e do estádio da partida.
- **Meu save quebra se eu remover o mod?** Não. O mod só troca o estádio e o texto na tela.

---

## Créditos

- `TaoStadiumMod/atmosfera/TaoAtmosfera.dll`: cópia ajustada do RSE Stadium Studio Lite 1.0.0 (FM27StadiumMod), de ronnieoa.
- `save/brazil-a-to-f-desempregado.fm`: save desempregado montado por nós sobre a **database do FM26 do [D-Manager](https://www.youtube.com/@D-Manager)**, que vai da Série A até a Série H. O crédito da database é dele.
- O RSE e a database são de terceiros e seguem as licenças dos autores. O restante é deste projeto.

Feito pela comunidade. Reporte defeitos de estádio nas [Issues](https://github.com/AbreuApps/fm27-estadios-release/issues). Quer um estádio que não está na lista? Abra uma Issue com o modelo «Pedir estádio».
