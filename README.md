# Estádios do Brasil 3D — Football Manager 27 🏟️🇧🇷

**134 estádios brasileiros** das séries A a D em 3D, com a torcida nos degraus, mais a **tradução Português (Brasil)**, a **câmera livre** e um **save pronto**. Tudo no mesmo pacote: baixe, descompacte e copie.
Tutorial válido da **v0.1.0** em diante. Baixe tudo em **[Releases](../../releases/latest)**.

<!-- ULTIMA-VERSAO:INICIO -->
[![Última versão](https://img.shields.io/github/v/release/AbreuApps/fm27-estadios-release?label=vers%C3%A3o&color=2ea44f)](https://github.com/AbreuApps/fm27-estadios-release/releases/latest) [![Downloads](https://img.shields.io/github/downloads/AbreuApps/fm27-estadios-release/total?label=downloads&color=blue)](https://github.com/AbreuApps/fm27-estadios-release/releases) [![Issues](https://img.shields.io/github/issues/AbreuApps/fm27-estadios-release?label=issues)](https://github.com/AbreuApps/fm27-estadios-release/issues)

### 🆕 Última versão: [v0.1.0](https://github.com/AbreuApps/fm27-estadios-release/releases/tag/v0.1.0) (10/11/2026)

- 🏟️ **134 estádios em 3D:** Série A, B, C e D, cada um ligado ao clube pelo ID do jogo. A lista completa está em **[ESTADIOS.md](ESTADIOS.md)**.
- 👥 **Torcida nos degraus:** a torcida senta nas cadeiras do estádio 3D, não em blocos soltos.
- 🇧🇷 **Tradução Português (Brasil) 1.2.6** junto no pacote, já ligada.
- 🎥 **Câmera livre** (FreeCam) junto no pacote: ajuda nos estádios que ficaram ruins na câmera padrão, ou para quem quiser olhar o estádio de perto. Tutorial em português.
- 💾 **Save desempregado** (Brasil, séries A a H) para escolher qualquer clube. Database das séries A a H criada pelo **[D-Manager](https://www.youtube.com/@D-Manager)**; veja os [créditos](INSTALAR.md#créditos).
- ⚠️ **É a primeira versão:** alguns estádios têm defeitos conhecidos (telhado na frente da câmera, arquibancada vazia). Veja em **[Problemas conhecidos](INSTALAR.md#️-problemas-conhecidos)**.

🔌 O **BepInEx 6 (IL2CPP)** é obrigatório: é ele que carrega o mod. Não tem? O pacote completo da [tradução](https://github.com/AbreuApps/fm27-ptbr-release/releases/latest) já traz ele pronto.
<!-- ULTIMA-VERSAO:FIM -->

> 💾 Faça backup do save antes (`Documentos/Sports Interactive/Football Manager 27/games`).

## 1. Baixe

Baixe **`FM27-Estadios-BR-<versão>.zip`** em [Releases](../../releases/latest) e **descompacte**.

## 2. Instale

Feche o jogo e **extraia a pasta `TaoMods` dentro de `BepInEx/plugins/`** (na pasta do jogo). Pronto: estádios, plugin da tradução e câmera livre já estão instalados.

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
WINEDLLOVERRIDES="version=n,b" %command%
```

## 5. Abra o jogo

A 1ª abertura com o BepInEx demora vários minutos: não feche.
Depois: **Preferências → Idioma → Português (Brasil)** e carregue o save ou comece carreira. O estádio aparece quando o clube joga em casa. 🏟️

---

📋 Quer ver quais estádios vieram e de qual time é cada um? Está em **[ESTADIOS.md](ESTADIOS.md)** e no fim desta página.

📸 Quer ver como é cada estádio? Veja as fotos em **[FOTOS.md](FOTOS.md)**.

🛠️ Dúvida na instalação, como tirar o mod ou algo deu errado? Veja o **[INSTALAR.md](INSTALAR.md)**.

🐞 Viu um estádio com defeito? Abra uma [Issue](../../issues) e escreva o nome do estádio e o que você viu.

---

## 🏟️ Estádios incluídos (134)

✅ aprovado em jogo · ⚠️ funciona, com um defeito (descrito) · ❌ não aprovado (vai no pacote, mas tapa o gramado) · 🔗 clube ligado · ➖ sem clube nesta versão (o jogo usa o estádio padrão).

### Série A (19)

| Estádio | Clube | Situação |
|---|---|---|
| Arena Condá | Associação Chapecoense de Futebol 🔗 | ✅ |
| Arena da Baixada | Club Athletico Paranaense 🔗 | ✅ |
| Arena do Grêmio | Grêmio Foot-Ball Porto Alegrense 🔗 | ✅ |
| Arena MRV | Clube Atlético Mineiro 🔗 | ✅ |
| Beira-Rio | Sport Club Internacional 🔗 | ✅ |
| Casa de Apostas Arena Fonte Nova | Esporte Clube Bahia 🔗 | ✅ |
| Cícero Pompeu de Toledo (Morumbi) | São Paulo Futebol Clube 🔗 | ✅ |
| Governador Magalhães Pinto (Mineirão) | Cruzeiro 🔗 | ✅ |
| Jornalista Mário Filho (Maracanã) | Flamengo / Fluminense 🔗 | ✅ |
| Major Antônio Couto Pereira | Coritiba Foot Ball Club 🔗 | ✅ |
| Manoel Barradas (Barradão) | Esporte Clube Vitória 🔗 | ✅ |
| Municipal Cícero de Souza Marques | Red Bull Bragantino 🔗 | ⚠️ v4, a melhorar depois |
| Municipal José Maria de Campos Maia (Maião) | Mirassol FC 🔗 | ✅ |
| Neo Química Arena | Sport Club Corinthians Paulista 🔗 | ✅ |
| Nubank Parque | Sociedade Esportiva Palmeiras 🔗 | ✅ |
| Olímpico do Pará (Mangueirão) | Paysandu / Clube do Remo 🔗 | ✅ |
| Olímpico Nilton Santos | Botafogo de Futebol e Regatas 🔗 | ✅ |
| São Januário | Club de Regatas Vasco da Gama 🔗 | ✅ |
| Urbano Caldeira (Vila Belmiro) | Santos Futebol Clube 🔗 | ✅ |

### Série B (20)

| Estádio | Clube | Situação |
|---|---|---|
| Adelmar da Costa Carvalho (Ilha do Retiro) | Sport Club do Recife 🔗 | ✅ |
| Aderbal Ramos da Silva (Ressacada) | Avaí 🔗 | ✅ |
| Alfredo Jaconi | Esporte Clube Juventude 🔗 | ⚠️ câmera ruim, telhado na frente |
| Antônio Accioly | Atlético Goianiense 🔗 | ✅ |
| Arena Pantanal | Cuiabá 🔗 | ✅ |
| Doutor Jorge Ismael de Biasi (Jorjão) | Grêmio Novorizontino 🔗 | ⚠️ duas arquibancadas vazias |
| Eládio de Barros Carvalho (Aflitos) | Clube Náutico Capibaribe 🔗 | ✅ |
| Germano Krüger | Operário Ferroviário 🔗 | ✅ |
| Governador Plácido Castelo (Arena Castelão) | Fortaleza / Ceará 🔗 | ✅ |
| Hailé Pinheiro (Serrinha) | Goiás 🔗 | ✅ |
| Heriberto Hülse | Criciúma 🔗 | ✅ |
| Joaquim Portugal (Arena Sicredi) | Athletic Club (Minas Gerais) 🔗 | ⚠️ telhado na frente da câmera |
| Moisés Lucarelli (Majestoso) | Ponte Preta 🔗 | ✅ |
| Municipal 1.º de Maio | São Bernardo 🔗 | ⚠️ telhado na frente da câmera tática |
| Municipal Jacy Scaff (Estádio do Café) | Londrina Esporte Clube 🔗 | ✅ |
| Onésio Brasileiro Alvarenga (OBA) | Vila Nova 🔗 | ✅ |
| Raimundo Sampaio (Arena Independência) | América Mineiro 🔗 | ⚠️ uma arquibancada aparece vazia |
| Rei Pelé | CSA / CRB 🔗 | ⚠️ telhado na frente da câmera |
| Santa Cruz | Botafogo-SP 🔗 | ⚠️ estadio podia ser maior em tamanho |
| Vitorino Gonçalves Dias (VGD) | Londrina ➖ | ✅ |

### Série C (20)

| Estádio | Clube | Situação |
|---|---|---|
| Arena Barra FC | Barra-SC 🔗 | ✅ |
| Arena de Pernambuco | Santa Cruz 🔗 | ✅ |
| Augusto Bauer | Brusque 🔗 | ✅ |
| Brinco de Ouro da Princesa | Guarani FC 🔗 | ✅ |
| Estadual Lourival Baptista (Batistão) | Confiança 🔗 | ✅ |
| Etelvino Mendonça | Associação Olímpica de Itabaiana 🔗 | ✅ |
| Francisco Stédile (Centenário) | SER Caxias do Sul 🔗 | ✅ |
| General Sylvio Raulino de Oliveira | Volta Redonda Futebol Clube 🔗 | ✅ |
| Governador João Castelo | Maranhão AC 🔗 | ✅ |
| José Américo de Almeida Filho (Almeidão) | Botafogo-PB 🔗 | ✅ |
| Leônidas Sodré de Castro (Curuzu) | Paysandu Sport Club 🔗 | ✅ |
| Major José Levy Sobrinho (Limeirão) | Associação Atlética Internacional (Inter de Limeira) 🔗 | ✅ |
| Municipal Doutor Novelli Júnior | Ituano Futebol Clube 🔗 | ✅ |
| Municipal Jonas Ferreira Alves Duarte | Anápolis Futebol Clube 🔗 | ✅ |
| Municipal Jornalista Carlos Zamith | Amazonas FC ➖ | ✅ |
| Municipal Olivério Bazzani Filho (Fonte Luminosa) | Associação Ferroviária de Esportes 🔗 | ✅ |
| Olímpico Colosso da Lagoa | Ypiranga Futebol Clube 🔗 | ✅ |
| Olímpico Horácio Domingos de Sousa (Domingão) | Floresta Esporte Clube 🔗 | ✅ |
| Orlando Scarpelli | Figueirense Futebol Clube 🔗 | ✅ |
| Regional Willie Davids | Maringá Futebol Clube 🔗 | ✅ |

### Série D (75)

| Estádio | Clube | Situação |
|---|---|---|
| 19 de Outubro | Esporte Clube São Luiz 🔗 | ⚠️ telhado na frente da câmera |
| Adauto Moraes | Sociedade Desportiva Juazeirense 🔗 | ✅ |
| Aluízio Ferreira (Aluizão) | Gazin Porto Velho / mandantes rondonienses 🔗 | ⚠️ telhado um pouco na frente da câmera |
| Aniceto Moscoso (Conselheiro Galvão) | Madureira Esporte Clube 🔗 | ✅ |
| Arena da Amazônia | Amazonas FC 🔗 | ✅ |
| Arena da Floresta | Independência Futebol Clube (e demais mandantes estaduais) 🔗 | ⚠️ telhado flutuante e na frente da câmera |
| Arena das Dunas | ABC / América de Natal 🔗 | ⚠️ telhados flutuantes; melhorar estilo do telhado pra ficar idêntico ao real |
| Arena Inamar (José Batista Pereira Fernandes) | Esporte Clube Água Santa 🔗 | ✅ |
| Arena Joinville | Joinville Esporte Clube (JEC) 🔗 | ✅ |
| Bento Mendes de Freitas | Grêmio Esportivo Brasil (Brasil de Pelotas) 🔗 | ✅ |
| Centro Esportivo Dirceu Mendes Arcoverde | Parnahyba Sport Club 🔗 | ✅ |
| Complexo Esportivo da Família | Blumenau Esporte Clube (BEC) / SESI Bernardo Wolfgang Werner 🔗 | ✅ |
| Domingos Silveira Gonzales | a conferir 🔗 | ✅ |
| Doutor Alfredo de Castilho (Alfredão) | Esporte Clube Noroeste 🔗 | ✅ |
| Doutor Hercílio Luz | Clube Náutico Marcílio Dias (também Barra em alguns jogos) 🔗 | ✅ |
| Doutor Oswaldo Teixeira Duarte (Canindé) | Portuguesa 🔗 | ✅ |
| Elmo Serejo Farias (Serejão) | Brasiliense 🔗 | ✅ |
| Estadual Kleber José de Andrade | Rio Branco Atlético Clube (ES) 🔗 | ✅ |
| Estrela D'Alva | Guarany Futebol Clube 🔗 | ✅ |
| Feliciano Belmont; oficialmente Municipal Felipe Raulino (CBF) | Associação Atlética de Altos 🔗 | ✅ |
| Francisco Novelletto Neto (Passo D'Areia) | Esporte Clube São José 🔗 | ✅ |
| Francisco Vasques | Tuna Luso Brasileira 🔗 | ⚠️ uma arquibancada vazia |
| Genervino Evangelista da Fonseca | CRAC 🔗 | ✅ |
| Giulite Coutinho | America Football Club (RJ) 🔗 | ✅ |
| Governador Alberto Tavares Silva (Albertão) | Piauí / Fluminense-PI (Teresina) 🔗 | ✅ |
| Governador Ernani Sátyro (Amigão) | Treze Futebol Clube 🔗 | ❌ tapa o gramado |
| Joaquim Henrique Nogueira | Democrata Futebol Clube (Democrata/SL) 🔗 | ✅ |
| José Mammoud Abbas | Esporte Clube Democrata 🔗 | ✅ |
| José Nazareno do Nascimento (Nazarenão) | a conferir ➖ | ✅ |
| José Olímpio da Rocha | Real Noroeste Capixaba Futebol Clube 🔗 | ✅ |
| João Ribeiro | Tocantinópolis Esporte Clube 🔗 | ✅ |
| Jânio Moraes | Nova Iguaçu Futebol Clube 🔗 | ✅ |
| Leôncio de Souza Miranda (Mirandão) | Araguaína Futebol e Regatas / Sparta 🔗 | ✅ |
| Lourival Gomes de Almeida (Lourivalzão) | Sampaio Corrêa Futebol e Esporte 🔗 | ✅ |
| Luiz José de Lacerda (Lacerdão) | Central Sport Club 🔗 | ✅ |
| Luso-Brasileiro | Associação Atlética Portuguesa (RJ) 🔗 | ✅ |
| Maria de Lourdes Abadia (Abadião) | Ceilândia Esporte Clube 🔗 | ✅ |
| Maria Lamas Farache (Frasqueirão) | ABC Futebol Clube 🔗 | ⚠️ arquibancada na frente da câmera |
| Milton de Souza Corrêa (Zerão) | Independente / Trem (Amapá) 🔗 | ❌ tapa o gramado |
| Municipal Annibal Batista de Toledo | Associação Atlética Aparecidense 🔗 | ⚠️ telhado um pouco na frente da câmera |
| Municipal Antônio Carlos Magalhães (Agnaldo Bento dos Santos) | Porto Sport Club 🔗 | ✅ |
| Municipal Antônio de Figueiredo Carneiro (Carneirão) | Atlético de Alagoinhas 🔗 | ✅ |
| Municipal Antônio Moreno de Mello (Morenão / Morony Furtado) | Associação Desportiva Iguatu 🔗 | ✅ |
| Municipal Antônio Santo Renosto (Cerradão) | Primavera Atlético Clube 🔗 | ✅ |
| Municipal Barão da Serra Negra | XV de Piracicaba 🔗 | ✅ |
| Municipal Benito Agnelo Castellano | AE Velo Clube Rioclarense 🔗 | ✅ |
| Municipal Coaracy da Mata Fonseca (Fumeirão) | Agremiação Sportiva Arapiraquense 🔗 | ✅ |
| Municipal Divino Garcia Rosa (Divinão) | Goiatuba Esporte Clube 🔗 | ✅ |
| Municipal Eliel Martins (Valfredão) | Esporte Clube Jacuipense 🔗 | ✅ |
| Municipal Engenheiro Luthero Lopes | União Esporte Clube (Rondonópolis) 🔗 | ✅ |
| Municipal Frei Epifânio D'Abadia | Sociedade Imperatriz de Desportos 🔗 | ✅ |
| Municipal Governador Antônio Mariz | Sousa Esporte Clube (administrador) 🔗 | ✅ |
| Municipal Irmão Gino Maria Rossi (Manduzão) | Pouso Alegre Futebol Clube 🔗 | ✅ |
| Municipal João Saldanha | Maricá Futebol Clube 🔗 | ✅ |
| Municipal João Saldanha | a conferir (série D — Guaporé manda no Cassolão) ➖ | ✅ |
| Municipal Juca Sampaio | Clube Sociedade Esportiva (CSE) 🔗 | ✅ |
| Municipal Luiz Benedito (ABECAT Ouvidor) | ABECAT Ouvidorense 🔗 | ✅ |
| Municipal Luiz Saraiva Vieira (Saraivão) | Ivinhema Futebol Clube 🔗 | ✅ |
| Municipal Nhozinho Santos | Sampaio Corrêa, Maranhão, Moto Club 🔗 | ✅ |
| Municipal Olímpico Albino Turbay | Cianorte Futebol Clube 🔗 | ✅ |
| Municipal Passo das Emas | Luverdense 🔗 | ✅ |
| Municipal Vereador Benedito Laurindo de Souza (Dito Souza) | Clube Esportivo Operário Várzea-Grandense 🔗 | ✅ |
| Municipal Zinho de Oliveira | Águia de Marabá Futebol Clube 🔗 | ⚠️ um pouco de telhado na frente da câmera |
| Nacional Mané Garrincha (Arena BRB) | Brasília FC / Capital-DF 🔗 | ✅ |
| Olímpico Regional Jacy Miguel Scanagatta | Futebol Clube Cascavel 🔗 | ✅ |
| Os Pioneiros (nome CBF; casa do São Joseense: Pinhão) | a conferir 🔗 | ✅ |
| Parque do Sabiá | Uberlândia 🔗 | ✅ |
| Paulo Barreto de Menezes | Lagarto Futebol Clube 🔗 | ✅ |
| Presidente Vargas | Ferroviário Atlético Clube (CE) 🔗 | ✅ |
| Raimundo Ribeiro de Souza (Ribeirão) | Monte Roraima Futebol Clube 🔗 | ✅ |
| Salvador Venâncio da Costa | Vitória (ES) 🔗 | ✅ |
| Soares de Azevedo | Nacional Atlético Clube; Tombense Futebol Clube (uso) 🔗 | ✅ |
| Universitário Pedro Pedrossian (Morenão) | Operário-MS / Comercial (Campo Grande) 🔗 | ✅ |
| Valmir Campelo Bezerra (Bezerrão) | Sociedade Esportiva do Gama 🔗 | ✅ |
| Zico Brandão (Zeca Melo) | Inhumas Esporte Clube 🔗 | ✅ |
