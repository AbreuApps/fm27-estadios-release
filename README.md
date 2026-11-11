# Estádios do Brasil 3D — Football Manager 27 🏟️🇧🇷

**136 estádios brasileiros** das séries A a D em 3D, com a torcida nos degraus, mais a **tradução Português (Brasil)** e um **save pronto**. Tudo no mesmo pacote: baixe, descompacte e copie.
Tutorial válido da **v0.1.0** em diante. Baixe tudo em **[Releases](../../releases/latest)**.

<!-- ULTIMA-VERSAO:INICIO -->
[![Última versão](https://img.shields.io/github/v/release/AbreuApps/fm27-estadios-release?label=vers%C3%A3o&color=2ea44f)](https://github.com/AbreuApps/fm27-estadios-release/releases/latest) [![Downloads](https://img.shields.io/github/downloads/AbreuApps/fm27-estadios-release/total?label=downloads&color=blue)](https://github.com/AbreuApps/fm27-estadios-release/releases) [![Issues](https://img.shields.io/github/issues/AbreuApps/fm27-estadios-release?label=issues)](https://github.com/AbreuApps/fm27-estadios-release/issues)

### 🆕 Última versão: [v0.1.3](https://github.com/AbreuApps/fm27-estadios-release/releases/tag/v0.1.3) (11/11/2026)

- 🛠️ **Correção do jogo fechando ao abrir a partida no Windows** (`TaoStadiumMod 0.1.3`): a troca de peça por tribuna, onde os logs paravam, vem desligada. Se ainda fechar, mande o log: precisamos saber se resolveu.
- 🏟️ **Estádios novos:** Arruda (Santa Cruz) e Vila Capanema (Paraná). Agora são **136**.
- 🏠 **Telhados mais altos e sobre pilares**, que não tapam mais a câmera: Arena Sicredi, Primeiro de Maio, Rei Pelé, 19 de Outubro, Aluizão, Annibal Batista de Toledo, Arena da Floresta, Zerão, Amigão, Francisco Vasques, Frasqueirão e Canindé. O Estádio Santa Cruz (Botafogo-SP) ficou maior.
- 🔁 A Arena de Pernambuco agora é do **Retrô**; o Santa Cruz joga no Arruda.
- 🤝 **Convive, por enquanto, com o pacote de estádios do BassyBoy:** onde ele tem estádio, ele manda e o nosso se desliga sozinho; nos outros, aparece o nosso.
- 📦 **Para atualizar:** apague a pasta `TaoMods` antiga em `BepInEx/plugins` e cole a nova. O zip `FM27-Estadios-BR-0.1.3.zip` traz só a pasta `TaoMods`.

### 🔙 v0.1.2 (11/11/2026)

- 🧪 **Versão de teste para o FM26** (zip separado, `FM26-Estadios-BR-teste-0.1.2.zip`): o plugin agora também roda no FM26. A torcida do jogo pode aparecer fora das arquibancadas.
- 🔍 `TaoStadiumMod 0.7.5`, com os logs de diagnóstico da 0.1.1.

O que veio na 0.1.1:

### 🔙 v0.1.1 (11/11/2026)

- 🔍 **A 0.1.1 só muda os logs**, para facilitar achar e resolver os crashes ao iniciar a partida. Nada muda no que se vê no jogo. Se o jogo fechar, mande o `BepInEx/LogOutput.log` (copie antes de abrir o jogo de novo). Detalhes em [INSTALAR.md](INSTALAR.md).
- 🔌 O **pacote completo** agora traz o BepInEx `be.791` e o `winhttp.dll` (no Linux: `WINEDLLOVERRIDES="winhttp=n,b"`).
- 🎥 A **câmera livre saiu do pacote**: ficam só os estádios e a tradução.

O que veio na 0.1.0:


- 🏟️ **134 estádios em 3D:** Série A, B, C e D, cada um ligado ao clube pelo ID do jogo. A lista completa está em **[ESTADIOS.md](ESTADIOS.md)**.
- 👥 **Torcida nos degraus:** a torcida senta nas cadeiras do estádio 3D, não em blocos soltos.
- 🇧🇷 **Tradução Português (Brasil) 1.2.6** junto no pacote, já ligada.
- 💾 **Save desempregado** (Brasil, séries A a H) para escolher qualquer clube. Database das séries A a H criada pelo **[D-Manager](https://www.youtube.com/@D-Manager)**; veja os [créditos](INSTALAR.md#créditos).
- ⚠️ **É a primeira versão:** alguns estádios têm defeitos conhecidos (telhado na frente da câmera, arquibancada vazia). Veja em **[Problemas conhecidos](INSTALAR.md#️-problemas-conhecidos)**.

🔌 O **BepInEx 6 (IL2CPP)** é obrigatório: é ele que carrega o mod. Não tem? O pacote completo da [tradução](https://github.com/AbreuApps/fm27-ptbr-release/releases/latest) já traz ele pronto.
<!-- ULTIMA-VERSAO:FIM -->

> 💾 Faça backup do save antes (`Documentos/Sports Interactive/Football Manager 27/games`).

## 1. Baixe

Baixe **`FM27-Estadios-BR-<versão>.zip`** em [Releases](../../releases/latest) e **descompacte**.

## 2. Instale

Feche o jogo e **extraia a pasta `TaoMods` dentro de `BepInEx/plugins/`** (na pasta do jogo). Pronto: estádios e plugin da tradução já estão instalados.

```
BepInEx/plugins/TaoMods/TaoStadiumMod/TaoStadiumMod.dll   ← deve existir
```

Para o jogo mostrar o idioma, copie também o arquivo **`TaoMods/languages/portuguese_br.ltc`** para a pasta **`languages`** (tabela abaixo). O jogo só lê idioma de lá.
O save (pasta `save`) é opcional: copie para a pasta `games`.

## 3. Pastas

| | Windows | Linux (Steam/Proton) |
|---|---|---|
| **Pasta do jogo** | `C:\Program Files (x86)\Steam\steamapps\common\Football Manager 27\` | `~/.local/share/Steam/steamapps/common/Football Manager 27/` |
| **`languages`** | `Documentos\Sports Interactive\Football Manager 27\languages\` | `~/.local/share/Steam/steamapps/compatdata/4530370/pfx/drive_c/users/steamuser/Documents/Sports Interactive/Football Manager 27/languages/` |
| **`games`** | `Documentos\Sports Interactive\Football Manager 27\games\` | mesma de `languages`, trocando `languages` por `games` |

Dica: Steam → botão direito no jogo → *Gerenciar* → *Explorar arquivos locais*.

## 4. Só no Linux

Steam → FM27 → Propriedades → *Opções de inicialização*:

```
WINEDLLOVERRIDES="winhttp=n,b" %command%
```

## 5. Abra o jogo

A 1ª abertura com o BepInEx demora vários minutos: não feche.
Depois: **Preferências → Idioma → Português (Brasil)** e carregue o save ou comece carreira. O estádio aparece quando o clube joga em casa. 🏟️

---

📋 Quer ver quais estádios vieram e de qual time é cada um? Está em **[ESTADIOS.md](ESTADIOS.md)** e no fim desta página.

📸 Quer ver como é cada estádio? Veja as fotos em **[FOTOS.md](FOTOS.md)**.

🛠️ Dúvida na instalação, como tirar o mod ou algo deu errado? Veja o **[INSTALAR.md](INSTALAR.md)**.

🐞 Viu um estádio com defeito? Abra uma [Issue](../../issues/new/choose) («Defeito em estádio») com o nome do estádio, o que você viu e o `LogOutput.log`.

🏟️ Seu estádio não está na lista? Peça numa [Issue](../../issues/new/choose) («Pedir estádio»).

✂️ Não quer os 136? Dá para instalar só alguns: veja o [INSTALAR.md](INSTALAR.md#instalar-só-alguns-estádios).

---

## 🏟️ Estádios incluídos (136)

✅ aprovado em jogo · 🔧 corrigido, falta testar em jogo · ⚠️ funciona, com um defeito (descrito) · ❌ não aprovado (vai no pacote, mas tapa o gramado) · 🔗 clube ligado · ➖ sem clube nesta versão (o jogo usa o estádio padrão). **Versão:** v1 é o estádio como saiu; cada mudança sobe a versão (entre parênteses, a release em que mudou).

### 🔄 Atualizados na v0.1.3 (13)

| Estádio | Clube | Versão | O que mudou |
|---|---|---|---|
| 19 de Outubro | Esporte Clube São Luiz | v2 (0.1.3) | telhado alto sobre pilares |
| Aluízio Ferreira (Aluizão) | Gazin Porto Velho / mandantes rondonienses | v2 (0.1.3) | telhado alto, não tapa mais a câmera |
| Arena da Floresta | Independência Futebol Clube (e demais mandantes estaduais) | v2 (0.1.3) | telhado alto com pilares (não flutua mais) e fora da frente da câmera |
| Doutor Oswaldo Teixeira Duarte (Canindé) | Portuguesa | v2 (0.1.3) | telhado fora da frente da câmera |
| Francisco Vasques | Tuna Luso Brasileira | v2 (0.1.3) | telhado alto sobre pilares |
| Governador Ernani Sátyro (Amigão) | Treze Futebol Clube | v2 (0.1.3) | telhado alto com pilares, fora da frente da câmera |
| Joaquim Portugal (Arena Sicredi) | Athletic Club (Minas Gerais) | v2 (0.1.3) | telhado não tapa mais a câmera |
| Maria Lamas Farache (Frasqueirão) | ABC Futebol Clube | v2 (0.1.3) | telhado fora da frente da câmera |
| Milton de Souza Corrêa (Zerão) | Independente / Trem (Amapá) | v2 (0.1.3) | telhado alto sobre pilares, fora da frente da câmera |
| Municipal 1.º de Maio | São Bernardo | v2 (0.1.3) | telhado alto sobre pilares, não tapa mais a câmera |
| Municipal Annibal Batista de Toledo | Associação Atlética Aparecidense | v2 (0.1.3) | telhado alto sobre pilares |
| Rei Pelé | CSA / CRB | v2 (0.1.3) | telhados altos sobre pilares, não tapam mais a câmera |
| Santa Cruz | Botafogo-SP | v2 (0.1.3) | estádio maior, coberturas altas |

### 🆕 Novos na v0.1.3 (2)

| Estádio | Clube |
|---|---|
| Durival Britto e Silva (Vila Capanema) | Paraná |
| José do Rego Maciel (Arruda) | Santa Cruz |

### Série A (19)

| Estádio | Clube | Versão | Situação |
|---|---|---|---|
| Arena Condá | Associação Chapecoense de Futebol 🔗 | v1 | ✅ |
| Arena da Baixada | Club Athletico Paranaense 🔗 | v1 | ✅ |
| Arena do Grêmio | Grêmio Foot-Ball Porto Alegrense 🔗 | v1 | ✅ |
| Arena MRV | Clube Atlético Mineiro 🔗 | v1 | ✅ |
| Beira-Rio | Sport Club Internacional 🔗 | v1 | ✅ |
| Casa de Apostas Arena Fonte Nova | Esporte Clube Bahia 🔗 | v1 | ✅ |
| Cícero Pompeu de Toledo (Morumbi) | São Paulo Futebol Clube 🔗 | v1 | ✅ |
| Governador Magalhães Pinto (Mineirão) | Cruzeiro 🔗 | v1 | ✅ |
| Jornalista Mário Filho (Maracanã) | Flamengo / Fluminense 🔗 | v1 | ✅ |
| Major Antônio Couto Pereira | Coritiba Foot Ball Club 🔗 | v1 | ✅ |
| Manoel Barradas (Barradão) | Esporte Clube Vitória 🔗 | v1 | ✅ |
| Municipal Cícero de Souza Marques | Red Bull Bragantino 🔗 | v1 | ⚠️ v4, a melhorar depois |
| Municipal José Maria de Campos Maia (Maião) | Mirassol FC 🔗 | v1 | ✅ |
| Neo Química Arena | Sport Club Corinthians Paulista 🔗 | v1 | ✅ |
| Nubank Parque | Sociedade Esportiva Palmeiras 🔗 | v1 | ✅ |
| Olímpico do Pará (Mangueirão) | Paysandu / Clube do Remo 🔗 | v1 | ✅ |
| Olímpico Nilton Santos | Botafogo de Futebol e Regatas 🔗 | v1 | ✅ |
| São Januário | Club de Regatas Vasco da Gama 🔗 | v1 | ✅ |
| Urbano Caldeira (Vila Belmiro) | Santos Futebol Clube 🔗 | v1 | ✅ |

### Série B (20)

| Estádio | Clube | Versão | Situação |
|---|---|---|---|
| Adelmar da Costa Carvalho (Ilha do Retiro) | Sport Club do Recife 🔗 | v1 | ✅ |
| Aderbal Ramos da Silva (Ressacada) | Avaí 🔗 | v1 | ✅ |
| Alfredo Jaconi | Esporte Clube Juventude 🔗 | v1 | ⚠️ câmera ruim, telhado na frente |
| Antônio Accioly | Atlético Goianiense 🔗 | v1 | ✅ |
| Arena Pantanal | Cuiabá 🔗 | v1 | ✅ |
| Doutor Jorge Ismael de Biasi (Jorjão) | Grêmio Novorizontino 🔗 | v1 | ⚠️ duas arquibancadas vazias |
| Eládio de Barros Carvalho (Aflitos) | Clube Náutico Capibaribe 🔗 | v1 | ✅ |
| Germano Krüger | Operário Ferroviário 🔗 | v1 | ✅ |
| Governador Plácido Castelo (Arena Castelão) | Fortaleza / Ceará 🔗 | v1 | ✅ |
| Hailé Pinheiro (Serrinha) | Goiás 🔗 | v1 | ✅ |
| Heriberto Hülse | Criciúma 🔗 | v1 | ✅ |
| Joaquim Portugal (Arena Sicredi) | Athletic Club (Minas Gerais) 🔗 | v2 (0.1.3) | 🔧 corrigido na 0.1.3, falta reteste |
| Moisés Lucarelli (Majestoso) | Ponte Preta 🔗 | v1 | ✅ |
| Municipal 1.º de Maio | São Bernardo 🔗 | v2 (0.1.3) | 🔧 corrigido na 0.1.3, falta reteste |
| Municipal Jacy Scaff (Estádio do Café) | Londrina Esporte Clube 🔗 | v1 | ✅ |
| Onésio Brasileiro Alvarenga (OBA) | Vila Nova 🔗 | v1 | ✅ |
| Raimundo Sampaio (Arena Independência) | América Mineiro 🔗 | v1 | ⚠️ uma arquibancada aparece vazia |
| Rei Pelé | CSA / CRB 🔗 | v2 (0.1.3) | 🔧 corrigido na 0.1.3, falta reteste |
| Santa Cruz | Botafogo-SP 🔗 | v2 (0.1.3) | 🔧 corrigido na 0.1.3, falta reteste |
| Vitorino Gonçalves Dias (VGD) | Londrina ➖ | v1 | ✅ |

### Série C (21)

| Estádio | Clube | Versão | Situação |
|---|---|---|---|
| Arena Barra FC | Barra-SC 🔗 | v1 | ✅ |
| Arena de Pernambuco | Retrô 🔗 | v1 | ✅ |
| Augusto Bauer | Brusque 🔗 | v1 | ✅ |
| Brinco de Ouro da Princesa | Guarani FC 🔗 | v1 | ✅ |
| Estadual Lourival Baptista (Batistão) | Confiança 🔗 | v1 | ✅ |
| Etelvino Mendonça | Associação Olímpica de Itabaiana 🔗 | v1 | ✅ |
| Francisco Stédile (Centenário) | SER Caxias do Sul 🔗 | v1 | ✅ |
| General Sylvio Raulino de Oliveira | Volta Redonda Futebol Clube 🔗 | v1 | ✅ |
| Governador João Castelo | Maranhão AC 🔗 | v1 | ✅ |
| José Américo de Almeida Filho (Almeidão) | Botafogo-PB 🔗 | v1 | ✅ |
| José do Rego Maciel (Arruda) | Santa Cruz 🔗 | v1 (0.1.3) | ✅ |
| Leônidas Sodré de Castro (Curuzu) | Paysandu Sport Club 🔗 | v1 | ✅ |
| Major José Levy Sobrinho (Limeirão) | Associação Atlética Internacional (Inter de Limeira) 🔗 | v1 | ✅ |
| Municipal Doutor Novelli Júnior | Ituano Futebol Clube 🔗 | v1 | ✅ |
| Municipal Jonas Ferreira Alves Duarte | Anápolis Futebol Clube 🔗 | v1 | ✅ |
| Municipal Jornalista Carlos Zamith | Amazonas FC ➖ | v1 | ✅ |
| Municipal Olivério Bazzani Filho (Fonte Luminosa) | Associação Ferroviária de Esportes 🔗 | v1 | ✅ |
| Olímpico Colosso da Lagoa | Ypiranga Futebol Clube 🔗 | v1 | ✅ |
| Olímpico Horácio Domingos de Sousa (Domingão) | Floresta Esporte Clube 🔗 | v1 | ✅ |
| Orlando Scarpelli | Figueirense Futebol Clube 🔗 | v1 | ✅ |
| Regional Willie Davids | Maringá Futebol Clube 🔗 | v1 | ✅ |

### Série D (76)

| Estádio | Clube | Versão | Situação |
|---|---|---|---|
| 19 de Outubro | Esporte Clube São Luiz 🔗 | v2 (0.1.3) | 🔧 corrigido na 0.1.3, falta reteste |
| Adauto Moraes | Sociedade Desportiva Juazeirense 🔗 | v1 | ✅ |
| Aluízio Ferreira (Aluizão) | Gazin Porto Velho / mandantes rondonienses 🔗 | v2 (0.1.3) | 🔧 corrigido na 0.1.3, falta reteste |
| Aniceto Moscoso (Conselheiro Galvão) | Madureira Esporte Clube 🔗 | v1 | ✅ |
| Arena da Amazônia | Amazonas FC 🔗 | v1 | ✅ |
| Arena da Floresta | Independência Futebol Clube (e demais mandantes estaduais) 🔗 | v2 (0.1.3) | 🔧 corrigido na 0.1.3, falta reteste |
| Arena das Dunas | ABC / América de Natal 🔗 | v1 | ⚠️ telhados flutuantes; melhorar estilo do telhado pra ficar idêntico ao real |
| Arena Inamar (José Batista Pereira Fernandes) | Esporte Clube Água Santa 🔗 | v1 | ✅ |
| Arena Joinville | Joinville Esporte Clube (JEC) 🔗 | v1 | ✅ |
| Bento Mendes de Freitas | Grêmio Esportivo Brasil (Brasil de Pelotas) 🔗 | v1 | ✅ |
| Centro Esportivo Dirceu Mendes Arcoverde | Parnahyba Sport Club 🔗 | v1 | ✅ |
| Complexo Esportivo da Família | Blumenau Esporte Clube (BEC) / SESI Bernardo Wolfgang Werner 🔗 | v1 | ✅ |
| Domingos Silveira Gonzales | a conferir 🔗 | v1 | ✅ |
| Doutor Alfredo de Castilho (Alfredão) | Esporte Clube Noroeste 🔗 | v1 | ✅ |
| Doutor Hercílio Luz | Clube Náutico Marcílio Dias (também Barra em alguns jogos) 🔗 | v1 | ✅ |
| Doutor Oswaldo Teixeira Duarte (Canindé) | Portuguesa 🔗 | v2 (0.1.3) | ✅ |
| Durival Britto e Silva (Vila Capanema) | Paraná 🔗 | v1 (0.1.3) | ✅ |
| Elmo Serejo Farias (Serejão) | Brasiliense 🔗 | v1 | ✅ |
| Estadual Kleber José de Andrade | Rio Branco Atlético Clube (ES) 🔗 | v1 | ✅ |
| Estrela D'Alva | Guarany Futebol Clube 🔗 | v1 | ✅ |
| Feliciano Belmont; oficialmente Municipal Felipe Raulino (CBF) | Associação Atlética de Altos 🔗 | v1 | ✅ |
| Francisco Novelletto Neto (Passo D'Areia) | Esporte Clube São José 🔗 | v1 | ✅ |
| Francisco Vasques | Tuna Luso Brasileira 🔗 | v2 (0.1.3) | ⚠️ uma arquibancada vazia |
| Genervino Evangelista da Fonseca | CRAC 🔗 | v1 | ✅ |
| Giulite Coutinho | America Football Club (RJ) 🔗 | v1 | ✅ |
| Governador Alberto Tavares Silva (Albertão) | Piauí / Fluminense-PI (Teresina) 🔗 | v1 | ✅ |
| Governador Ernani Sátyro (Amigão) | Treze Futebol Clube 🔗 | v2 (0.1.3) | 🔧 corrigido na 0.1.3, falta reteste |
| Joaquim Henrique Nogueira | Democrata Futebol Clube (Democrata/SL) 🔗 | v1 | ✅ |
| José Mammoud Abbas | Esporte Clube Democrata 🔗 | v1 | ✅ |
| José Nazareno do Nascimento (Nazarenão) | a conferir ➖ | v1 | ✅ |
| José Olímpio da Rocha | Real Noroeste Capixaba Futebol Clube 🔗 | v1 | ✅ |
| João Ribeiro | Tocantinópolis Esporte Clube 🔗 | v1 | ✅ |
| Jânio Moraes | Nova Iguaçu Futebol Clube 🔗 | v1 | ✅ |
| Leôncio de Souza Miranda (Mirandão) | Araguaína Futebol e Regatas / Sparta 🔗 | v1 | ✅ |
| Lourival Gomes de Almeida (Lourivalzão) | Sampaio Corrêa Futebol e Esporte 🔗 | v1 | ✅ |
| Luiz José de Lacerda (Lacerdão) | Central Sport Club 🔗 | v1 | ✅ |
| Luso-Brasileiro | Associação Atlética Portuguesa (RJ) 🔗 | v1 | ✅ |
| Maria de Lourdes Abadia (Abadião) | Ceilândia Esporte Clube 🔗 | v1 | ✅ |
| Maria Lamas Farache (Frasqueirão) | ABC Futebol Clube 🔗 | v2 (0.1.3) | 🔧 corrigido na 0.1.3, falta reteste |
| Milton de Souza Corrêa (Zerão) | Independente / Trem (Amapá) 🔗 | v2 (0.1.3) | 🔧 corrigido na 0.1.3, falta reteste |
| Municipal Annibal Batista de Toledo | Associação Atlética Aparecidense 🔗 | v2 (0.1.3) | 🔧 corrigido na 0.1.3, falta reteste |
| Municipal Antônio Carlos Magalhães (Agnaldo Bento dos Santos) | Porto Sport Club 🔗 | v1 | ✅ |
| Municipal Antônio de Figueiredo Carneiro (Carneirão) | Atlético de Alagoinhas 🔗 | v1 | ✅ |
| Municipal Antônio Moreno de Mello (Morenão / Morony Furtado) | Associação Desportiva Iguatu 🔗 | v1 | ✅ |
| Municipal Antônio Santo Renosto (Cerradão) | Primavera Atlético Clube 🔗 | v1 | ✅ |
| Municipal Barão da Serra Negra | XV de Piracicaba 🔗 | v1 | ✅ |
| Municipal Benito Agnelo Castellano | AE Velo Clube Rioclarense 🔗 | v1 | ✅ |
| Municipal Coaracy da Mata Fonseca (Fumeirão) | Agremiação Sportiva Arapiraquense 🔗 | v1 | ✅ |
| Municipal Divino Garcia Rosa (Divinão) | Goiatuba Esporte Clube 🔗 | v1 | ✅ |
| Municipal Eliel Martins (Valfredão) | Esporte Clube Jacuipense 🔗 | v1 | ✅ |
| Municipal Engenheiro Luthero Lopes | União Esporte Clube (Rondonópolis) 🔗 | v1 | ✅ |
| Municipal Frei Epifânio D'Abadia | Sociedade Imperatriz de Desportos 🔗 | v1 | ✅ |
| Municipal Governador Antônio Mariz | Sousa Esporte Clube (administrador) 🔗 | v1 | ✅ |
| Municipal Irmão Gino Maria Rossi (Manduzão) | Pouso Alegre Futebol Clube 🔗 | v1 | ✅ |
| Municipal João Saldanha | Maricá Futebol Clube 🔗 | v1 | ✅ |
| Municipal João Saldanha | a conferir (série D — Guaporé manda no Cassolão) ➖ | v1 | ✅ |
| Municipal Juca Sampaio | Clube Sociedade Esportiva (CSE) 🔗 | v1 | ✅ |
| Municipal Luiz Benedito (ABECAT Ouvidor) | ABECAT Ouvidorense 🔗 | v1 | ✅ |
| Municipal Luiz Saraiva Vieira (Saraivão) | Ivinhema Futebol Clube 🔗 | v1 | ✅ |
| Municipal Nhozinho Santos | Sampaio Corrêa, Maranhão, Moto Club 🔗 | v1 | ✅ |
| Municipal Olímpico Albino Turbay | Cianorte Futebol Clube 🔗 | v1 | ✅ |
| Municipal Passo das Emas | Luverdense 🔗 | v1 | ✅ |
| Municipal Vereador Benedito Laurindo de Souza (Dito Souza) | Clube Esportivo Operário Várzea-Grandense 🔗 | v1 | ✅ |
| Municipal Zinho de Oliveira | Águia de Marabá Futebol Clube 🔗 | v1 | ⚠️ um pouco de telhado na frente da câmera |
| Nacional Mané Garrincha (Arena BRB) | Brasília FC / Capital-DF 🔗 | v1 | ✅ |
| Olímpico Regional Jacy Miguel Scanagatta | Futebol Clube Cascavel 🔗 | v1 | ✅ |
| Os Pioneiros (nome CBF; casa do São Joseense: Pinhão) | a conferir 🔗 | v1 | ✅ |
| Parque do Sabiá | Uberlândia 🔗 | v1 | ✅ |
| Paulo Barreto de Menezes | Lagarto Futebol Clube 🔗 | v1 | ✅ |
| Presidente Vargas | Ferroviário Atlético Clube (CE) 🔗 | v1 | ✅ |
| Raimundo Ribeiro de Souza (Ribeirão) | Monte Roraima Futebol Clube 🔗 | v1 | ✅ |
| Salvador Venâncio da Costa | Vitória (ES) 🔗 | v1 | ✅ |
| Soares de Azevedo | Nacional Atlético Clube; Tombense Futebol Clube (uso) 🔗 | v1 | ✅ |
| Universitário Pedro Pedrossian (Morenão) | Operário-MS / Comercial (Campo Grande) 🔗 | v1 | ✅ |
| Valmir Campelo Bezerra (Bezerrão) | Sociedade Esportiva do Gama 🔗 | v1 | ✅ |
| Zico Brandão (Zeca Melo) | Inhumas Esporte Clube 🔗 | v1 | ✅ |
