# 📈 Oracle Performance Tuning Scripts

Este repositório contém um conjunto de scripts SQL para análise e ajuste de performance em bancos de dados Oracle. São consultas e utilitários que facilitam a identificação de gargalos, estatísticas e configurações importantes para o tuning do ambiente.  

> ⚡ **Objetivo**: Auxiliar DBAs e desenvolvedores a monitorar e otimizar a performance de instâncias Oracle de forma prática e eficiente.

---

## 📊 Performance

Scripts voltados para análise e diagnóstico de performance:  

| 📄 Script                                           | 📝 Descrição                                                                                     |
|-----------------------------------------------------|---------------------------------------------------------------------------------------------------|
| `alterar_configuracoes_awr.sql`                     | Altera as configurações do AWR (*Automatic Workload Repository*).                                 |
| `consultar_awr_parametro.sql`                       | Consulta os parâmetros atualmente configurados no AWR.                                            |
| `consultar_buffer_busy_waits.sql`                   | Verifica ocorrências de *buffer busy waits*.                                                      |
| `consultar_carga_bd_horas_uso_e_IO_diaria.sql`      | Analisa a carga do banco por hora e o uso de I/O diário.                                          |
| `consultar_estatisticas_services_waits.sql`         | Consulta estatísticas de espera agrupadas por serviços.                                           |
| `consultar_estatisticas_servicos.sql`               | Lista estatísticas gerais de performance por serviço.                                             |
| `consultar_historico_leituras_full_X_index.sql`     | Verifica histórico de leituras full table e uso de índices.                                       |
| `consultar_leituras_full_X_index.sql`               | Analisa leituras full table versus leituras por índice.                                           |
| `consultar_linhas_encadeadas.sql`                   | Identifica linhas encadeadas (*chained rows*) no banco.                                           |
| `consultar_tamanho_shared_pool_reserved.sql`        | Consulta o tamanho da área reservada no *shared pool*.                                            |
| `consultar_total_waits.sql`                         | Lista os eventos de espera totais no banco.                                                       |
| `consultar_wait_events_awr.sql`                     | Consulta eventos de espera registrados no AWR.                                                    |
| `verificar_IO_estatisticas_servicos_background.sql` | Analisa estatísticas de I/O e serviços de background.                                             |
| `verificar_cache_hit_ratio.sql`                     | Verifica o *cache hit ratio* da instância.                                                        |
| `verificar_desempenho_sorts.sql`                    | Analisa o desempenho de operações de *sort*.                                                      |
| `verificar_library_cache_hit_ratio.sql`             | Verifica o hit ratio do *library cache*.                                                          |
| `verificar_qtde_transacoes.sql`                     | Consulta a quantidade de transações executadas no banco.                                          |
| `verificar_tabelas_estatisticas_scan.sql`           | Identifica tabelas com estatísticas desatualizadas ou varreduras completas (*full scan*).         |

---

