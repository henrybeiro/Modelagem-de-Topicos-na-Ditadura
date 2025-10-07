![protesto_censura_capa_nova](https://github.com/user-attachments/assets/680f3bca-cd19-4dd1-a766-2a38b0136ef7)
# 🎶 A Música Brasileira na Ditadura Militar  
### Dataset para análise de tópicos

Este repositório disponibiliza o **dataset** utilizado no artigo:  

📄 **A Música Brasileira na Ditadura Militar: uma análise de tópicos com BERTopic e GSDMM**  
**Autores:** Henry Ribeiro Piceni (henry.piceni@inf.ufrgs.br), Pedro Vitor Alexandre (pvalexandre@inf.ufrgs.br), Dennis Giovani Balreira (dgbalreira@inf.ufrgs.br)

### Instituto de Informática – Universidade Federal do Rio Grande do Sul (UFRGS)  

---

## 📌 Descrição
Durante a ditadura militar no Brasil (1964–1985), a música popular foi um dos principais meios de **expressão artística, crítica e resistência política**.  
Este dataset reúne **letras de músicas brasileiras** lançadas nesse período, coletadas a partir de playlists no Spotify e complementadas com letras obtidas via **Genius API**.  

Ele foi utilizado para treinar e avaliar modelos de **Processamento de Linguagem Natural (PLN)**, em especial:  
- **BERTopic** – modelagem de tópicos baseada em embeddings semânticos;  
- **GSDMM** – modelo probabilístico adequado para textos curtos.  

---

## 📂 Estrutura do Dataset
O arquivo principal é:  

- `musicas_ditadura.csv`  

Com as seguintes colunas:  

| Coluna              | Descrição |
|---------------------|-----------|
| `track_name`        | Nome da música |
| `track_id`          | ID da música no Spotify |
| `artist_name`       | Nome(s) do(s) artista(s) |
| `artist_id`         | ID do(a) artista no Spotify |
| `album_name`        | Nome do álbum |
| `album_id`          | ID do(a) álbum no Spotify |
| `release_date`      | Data de lançamento |
| `duration_ms`       | Duração da faixa em milissegundos |
| `popularity`        | Popularidade no Spotify |
| `lyrics`            | Letra completa da música (quando disponível) |
| `matched_url`       | URL da letra no Genius |

---

## 📊 Aplicações

O dataset pode ser utilizado em:
- Modelagem de tópicos (BERTopic, LDA, GSDMM, etc.)
- Análise de sentimentos em músicas
- Estudos interdisciplinares em ciência de dados + ciências humanas
- Exploração de expressões artísticas como formas de resistência cultural
- (sua imaginação é o limite :D)

## 📌 Licença

Este dataset é disponibilizado exclusivamente para fins acadêmicos e de pesquisa.
As letras das músicas pertencem aos seus respectivos detentores de direitos autorais.
