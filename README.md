# Documentação do Modulo de conexão

## Descrição
Este projeto implenta um padrão de conexão segura com o banco de dados, ultilizando **Design Patterns** para evitar *hardcoding*

## O que foi feito
- [x] Criação de repositorio
- [x] Implementação da conexão
- [x] Rresolução de conflito da Merge
- [x] Separação de configuração

## Exemplo de uso
Abaixo, o codigo padrão ultilizado pelo arquiteto:

'''python
# constante de configuração
DB_HOST = "192.168.0.1"

def conectar_banco():
  """Conecta usando constante definida"""
  return f"Conectando ao {BD_HOST}"
