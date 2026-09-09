# O que é o código ASCII? Confira a tabela completa e para que serve

> **Fonte:** Por André Sugai.

O código **ASCII** é amplamente utilizado para a conversão de código binário para letras do alfabeto (maiúsculas e minúsculas), números e símbolos. Descubra para que o código foi criado, sua história e o que é possível criar com ele.

---

## 📌 Introdução e Origem

O ASCII foi proposto por **Robert W. Bemer** como uma solução para unificar a representação de caracteres alfanuméricos em computadores. Antes da década de 1960, cada fabricante de computador utilizava uma regra diferente para representar caracteres, e o código ASCII nasceu para estabelecer um padrão comum entre todas as máquinas.

O nome **ASCII** é a sigla para ***American Standard Code for Information Interchange*** (Código Padrão Americano para o Intercâmbio de Informação). Baseado no alfabeto romano, sua função primária é padronizar a forma como os sistemas operacionais e dispositivos representam letras, números, acentos, sinais de pontuação e comandos de controle.

---

## ⚙️ O que é ASCII e para que serve?

No padrão ASCII tradicional, existem **95 caracteres imprimíveis**, numerados de **32 a 126**. Os caracteres numerados de **0 a 31** (além do 127) são reservados para **funções de controle** do sistema.

Muitos desses códigos de controle eram direcionados a equipamentos da época, como máquinas de escrever eletromecânicas (*Teletype*), leitoras de fita de papel perfurado e impressoras de cilindro. Embora alguns tenham caído em desuso, outros permanecem essenciais até hoje:

* **LINE FEED (LF - 10 / 0xA):** Avançava o papel na impressora; hoje representa a quebra de linha (`\n`) em sistemas Unix/Linux.
* **CARRIAGE RETURN (CR - 13 / 0xD):** Retornava o cabeçote de impressão; hoje usado em quebras de linha Windows (`\r\n`).
* **ESCAPE (ESC - 27 / 0x1B):** Representado até hoje pela tecla `ESC`.

---

## 📊 Tabela ASCII Completa

### 1. Sinais de Controle (Não-Imprimíveis)

| Binário | Octal | Decimal | Hex | Abrev. | Notação Circunflexa | Código Escape | Nome / Descrição |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :--- |
| `0000 0000` | `0` | `0` | `00` | NULL | `^@` | `\0` | Nulo (*Null*) |
| `0000 0001` | `1` | `1` | `01` | SOH | `^A` | | Início de cabeçalho (*Start of Header*) |
| `0000 0010` | `2` | `2` | `02` | STX | `^B` | | Início de texto (*Start of Text*) |
| `0000 0011` | `3` | `3` | `03` | ETX | `^C` | | Fim de texto (*End of Text*) |
| `0000 0100` | `4` | `4` | `04` | EOT | `^D` | | Fim de transmissão (*End of Transmission*) |
| `0000 0101` | `5` | `5` | `05` | ENQ | `^E` | | Consulta; inquirição (*Enquiry*) |
| `0000 0110` | `6` | `6` | `06` | ACK | `^F` | | Confirmação (*Acknowledge*) |
| `0000 0111` | `7` | `7` | `07` | BEL | `^G` | `\a` | Campainha; sinal sonoro (*Bell*) |
| `0000 1000` | `10` | `8` | `08` | BS | `^H` | `\b` | Espaço atrás; retorno de 1 caractere (*Back-space*) |
| `0000 1001` | `11` | `9` | `09` | HT | `^I` | `\t` | Tabulação horizontal (*Horizontal Tabulation*) |
| `0000 1010` | `12` | `10` | `0A` | LF | `^J` | `\n` | Alimentação de linha; nova linha (*Line Feed*) |
| `0000 1011` | `13` | `11` | `0B` | VT | `^K` | `\v` | Tabulação vertical (*Vertical Tabulation*) |
| `0000 1100` | `14` | `12` | `0C` | FF | `^L` | `\f` | Alimentação de formulário (*Form Feed*) |
| `0000 1101` | `15` | `13` | `0D` | CR | `^M` | `\r` | Retorno do carro (*Carriage Return*) |
| `0000 1110` | `16` | `14` | `0E` | SO | `^N` | | Deslocamento para fora (*Shift Out*) |
| `0000 1111` | `17` | `15` | `0F` | SI | `^O` | | Deslocamento para dentro (*Shift In*) |
| `0001 0000` | `20` | `16` | `10` | DLE | `^P` | | Escape de conexão (*Data-Link Escape*) |
| `0001 0001` | `21` | `17` | `11` | DC1 | `^Q` | | Controle de dispositivo 1 (*Device Control 1*) |
| `0001 0010` | `22` | `18` | `12` | DC2 | `^R` | | Controle de dispositivo 2 (*Device Control 2*) |
| `0001 0011` | `23` | `19` | `13` | DC3 | `^S` | | Controle de dispositivo 3 (*Device Control 3*) |
| `0001 0100` | `24` | `20` | `14` | DC4 | `^T` | | Controle de dispositivo 4 (*Device Control 4*) |
| `0001 0101` | `25` | `21` | `15` | NAK | `^U` | | Confirmação negativa (*Negative-Acknowledge*) |
| `0001 0110` | `26` | `22` | `16` | SYN | `^V` | | Espera síncrona (*Synchronous Idle*) |
| `0001 0111` | `27` | `23` | `17` | ETB | `^W` | | Bloco de fim de transmissão (*End of Transmission Block*) |
| `0001 1000` | `30` | `24` | `18` | CAN | `^X` | | Cancelar (*Cancel*) |
| `0001 1001` | `31` | `25` | `19` | EM | `^Y` | | Fim de mídia (*End of Medium*) |
| `0001 1010` | `32` | `26` | `1A` | SUB | `^Z` | | Substituir (*Substitute*) |
| `0001 1011` | `33` | `27` | `1B` | ESC | `^[` | | Escapar (*Escape*) |
| `0001 1100` | `34` | `28` | `1C` | FS | `^\` | | Separador de arquivos (*File Separator*) |
| `0001 1101` | `35` | `29` | `1D` | GS | `^]` | `\e` | Separador de grupos (*Group Separator*) |
| `0001 1110` | `36` | `30` | `1E` | RS | `^^` | | Separador de registros (*Record Separator*) |
| `0001 1111` | `37` | `31` | `1F` | US | `^_` | | Separador de unidades (*Unit Separator*) |
| `0111 1111` | `177` | `127` | `7F` | DEL | `^?` | | Deletar (*Delete*) |

---

### 2. Sinais Gráficos e Pontuação (Dec 32 a 63)

| Binário | Octal | Decimal | Hex | Caractere | Descrição / Caractere |
| :---: | :---: | :---: | :---: | :---: | :--- |
| `0010 0000` | `40` | `32` | `20` | ` ` | Espaço (*Space*) |
| `0010 0001` | `41` | `33` | `21` | `!` | Ponto de Exclamação |
| `0010 0010` | `42` | `34` | `22` | `"` | Aspas Duplas |
| `0010 0011` | `43` | `35` | `23` | `#` | Jogo da Velha / Cerquilha |
| `0010 0100` | `44` | `36` | `24` | `$` | Cifrão |
| `0010 0101` | `45` | `37` | `25` | `%` | Porcentagem |
| `0010 0110` | `46` | `38` | `26` | `&` | E comercial (*Ampersand*) |
| `0010 0111` | `47` | `39` | `27` | `'` | Aspa Simples / Apóstrofo |
| `0010 1000` | `50` | `40` | `28` | `(` | Abre Parênteses |
| `0010 1001` | `51` | `41` | `29` | `)` | Fecha Parênteses |
| `0010 1010` | `52` | `42` | `2A` | `*` | Asterisco |
| `0010 1011` | `53` | `43` | `2B` | `+` | Sinal de Adição |
| `0010 1100` | `54` | `44` | `2C` | `,` | Vírgula |
| `0010 1101` | `55` | `45` | `2D` | `-` | Hífen / Sinal de Subtração |
| `0010 1110` | `56` | `46` | `2E` | `.` | Ponto Final |
| `0010 1111` | `57` | `47` | `2F` | `/` | Barra Normal |
| `0011 0000` | `60` | `48` | `30` | `0` | Número 0 |
| `0011 0001` | `61` | `49` | `31` | `1` | Número 1 |
| `0011 0010` | `62` | `50` | `32` | `2` | Número 2 |
| `0011 0011` | `63` | `51` | `33` | `3` | Número 3 |
| `0011 0100` | `64` | `52` | `34` | `4` | Número 4 |
| `0011 0101` | `65` | `53` | `35` | `5` | Número 5 |
| `0011 0110` | `66` | `54` | `36` | `6` | Número 6 |
| `0011 0111` | `67` | `55` | `37` | `7` | Número 7 |
| `0011 1000` | `70` | `56` | `38` | `8` | Número 8 |
| `0011 1001` | `71` | `57` | `39` | `9` | Número 9 |
| `0011 1010` | `72` | `58` | `3A` | `:` | Dois Pontos |
| `0011 1011` | `73` | `59` | `3B` | `;` | Ponto e Vírgula |
| `0011 1100` | `74` | `60` | `3C` | `<` | Menor Que |
| `0011 1101` | `75` | `61` | `3D` | `=` | Sinal de Igual |
| `0011 1110` | `76` | `62` | `3E` | `>` | Maior Que |
| `0011 1111` | `77` | `63` | `3F` | `?` | Ponto de Interrogação |

---

### 3. Letras Maiúsculas e Símbolos (Dec 64 a 95)

| Binário | Octal | Decimal | Hex | Caractere | Descrição / Caractere |
| :---: | :---: | :---: | :---: | :---: | :--- |
| `0100 0000` | `100` | `64` | `40` | `@` | Arroba |
| `0100 0001` | `101` | `65` | `41` | `A` | Letra A Maiúscula |
| `0100 0010` | `102` | `66` | `42` | `B` | Letra B Maiúscula |
| `0100 0011` | `103` | `67` | `43` | `C` | Letra C Maiúscula |
| `0100 0100` | `104` | `68` | `44` | `D` | Letra D Maiúscula |
| `0100 0101` | `105` | `69` | `45` | `E` | Letra E Maiúscula |
| `0100 0110` | `106` | `70` | `46` | `F` | Letra F Maiúscula |
| `0100 0111` | `107` | `71` | `47` | `G` | Letra G Maiúscula |
| `0100 1000` | `110` | `72` | `48` | `H` | Letra H Maiúscula |
| `0100 1001` | `111` | `73` | `49` | `I` | Letra I Maiúscula |
| `0100 1010` | `112` | `74` | `4A` | `J` | Letra J Maiúscula |
| `0100 1011` | `113` | `75` | `4B` | `K` | Letra K Maiúscula |
| `0100 1100` | `114` | `76` | `4C` | `L` | Letra L Maiúscula |
| `0100 1101` | `115` | `77` | `4D` | `M` | Letra M Maiúscula |
| `0100 1110` | `116` | `78` | `4E` | `N` | Letra N Maiúscula |
| `0101 0000` | `120` | `80` | `50` | `P` | Letra P Maiúscula |
| `0101 0001` | `121` | `81` | `51` | `Q` | Letra Q Maiúscula |
| `0101 0010` | `122` | `82` | `52` | `R` | Letra R Maiúscula |
| `0101 0011` | `123` | `83` | `53` | `S` | Letra S Maiúscula |
| `0101 0100` | `124` | `84` | `54` | `T` | Letra T Maiúscula |
| `0101 0101` | `125` | `85` | `55` | `U` | Letra U Maiúscula |
| `0101 0110` | `126` | `86` | `56` | `V` | Letra V Maiúscula |
| `0101 0111` | `127` | `87` | `57` | `W` | Letra W Maiúscula |
| `0101 1000` | `130` | `88` | `58` | `X` | Letra X Maiúscula |
| `0101 1001` | `131` | `89` | `59` | `Y` | Letra Y Maiúscula |
| `0101 1010` | `132` | `90` | `5A` | `Z` | Letra Z Maiúscula |
| `0101 1011` | `133` | `91` | `5B` | `[` | Abre Colchete |
| `0101 1100` | `134` | `92` | `5C` | `\` | Barra Invertida (*Backslash*) |
| `0101 1101` | `135` | `93` | `5D` | `]` | Fecha Colchete |
| `0101 1110` | `136` | `94` | `5E` | `^` | Acento Circunflexo / Caret |
| `0101 1111` | `137` | `95` | `5F` | `_` | Traço Inferior (*Underscore*) |

---

### 4. Letras Minúsculas e Símbolos (Dec 96 a 126)

| Binário | Octal | Decimal | Hex | Caractere | Descrição / Caractere |
| :---: | :---: | :---: | :---: | :---: | :--- |
| `0110 0000` | `140` | `96` | `60` | `` ` `` | Acento Grave / *Grave Accent* |
| `0110 0001` | `141` | `97` | `61` | `a` | Letra a Minúscula |
| `0110 0010` | `142` | `98` | `62` | `b` | Letra b Minúscula |
| `0110 0011` | `143` | `99` | `63` | `c` | Letra c Minúscula |
| `0110 0100` | `144` | `100` | `64` | `d` | Letra d Minúscula |
| `0110 0101` | `145` | `101` | `65` | `e` | Letra e Minúscula |
| `0110 0110` | `146` | `102` | `66` | `f` | Letra f Minúscula |
| `0110 0111` | `147` | `103` | `67` | `g` | Letra g Minúscula |
| `0110 1000` | `150` | `104` | `68` | `h` | Letra h Minúscula |
| `0110 1001` | `151` | `105` | `69` | `i` | Letra i Minúscula |
| `0110 1010` | `152` | `106` | `6A` | `j` | Letra j Minúscula |
| `0110 1011` | `153` | `107` | `6B` | `k` | Letra k Minúscula |
| `0110 1100` | `154` | `108` | `6C` | `l` | Letra l Minúscula |
| `0110 1101` | `155` | `109` | `6D` | `m` | Letra m Minúscula |
| `0110 1110` | `156` | `110` | `6E` | `n` | Letra n Minúscula |
| `0110 1111` | `157` | `111` | `6F` | `o` | Letra o Minúscula |
| `0111 0000` | `160` | `112` | `70` | `p` | Letra p Minúscula |
| `0111 0001` | `161` | `113` | `71` | `q` | Letra q Minúscula |
| `0111 0010` | `162` | `114` | `72` | `r` | Letra r Minúscula |
| `0111 0011` | `163` | `115` | `73` | `s` | Letra s Minúscula |
| `0111 0100` | `164` | `116` | `74` | `t` | Letra t Minúscula |
| `0111 0101` | `165` | `117` | `75` | `u` | Letra u Minúscula |
| `0111 0110` | `166` | `118` | `76` | `v` | Letra v Minúscula |
| `0111 0111` | `167` | `119` | `77` | `w` | Letra w Minúscula |
| `0111 1000` | `170` | `120` | `78` | `x` | Letra x Minúscula |
| `0111 1001` | `171` | `121` | `79` | `y` | Letra y Minúscula |
| `0111 1010` | `172` | `122` | `7A` | `z` | Letra z Minúscula |
| `0111 1011` | `173` | `123` | `7B` | `{` | Abre Chave |
| `0111 1100` | `174` | `124` | `7C` | `\|` | Barra Vertical (*Pipe*) |
| `0111 1101` | `175` | `125` | `7D` | `}` | Fecha Chave |
| `0111 1110` | `176` | `126` | `7E` | `~` | Til / Tilde |

---

## 🎨 E os desenhos? (ASCII Art)

Outro uso bastante popular do padrão ASCII é na criação de desenhos e ilustrações baseadas inteiramente em caracteres de texto, arte conhecida como **ASCII Art**.

```text
       _    ____   ____ ___ ___
      / \  / ___| / ___|_ _|_ _|
     / _ \ \___ \| |    | | | |
    / ___ \ ___) | |___ | | | |
   /_/   \_\____/ \____|___|___|
```

Os caracteres podem ser arranjados para formar imagens completas, monocromáticas ou coloridas. Essa prática ganhou enorme popularidade em fóruns legados, salas de bate-papo como o **mIRC** e em assinaturas de e-mail.

### Ferramentas e Recursos Relacionados:
* **Conversores de Texto para ASCII Art:** Geradores online como *Text to ASCII Art Generator*.
* **Conversores de Imagem para ASCII:** Ferramentas como o *Picascii*.
* **Galerias Gratuitas:** O site [Asciiart.eu](https://www.asciiart.eu) possui uma vasta coleção de imagens produzidas por artistas da comunidade.

Mesmo sendo um padrão criado na década de 1960, o código ASCII permanece sendo a fundação para tabelas de caracteres mais modernas (como UTF-8) e continua extremamente útil e divertido para estudantes de programação e profissionais de TI.
