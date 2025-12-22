# 📮 Buscador de CEP

Uma aplicação web simples e elegante para consultar endereços brasileiros através do CEP (Código de Endereçamento Postal).

## ✨ Funcionalidades

- Busca de endereços por CEP
- Interface intuitiva e responsiva
- Validação de entrada
- Exibição organizada dos dados do endereço
- Design moderno com Tailwind CSS

## 🚀 Tecnologias Utilizadas

- HTML5
- JavaScript (ES6+)
- Tailwind CSS
- API ViaCEP

## 📋 Pré-requisitos

Apenas um navegador web moderno. Não há necessidade de instalação de dependências.

## 🎯 Como Usar

1. Clone ou baixe o arquivo HTML
2. Abra o arquivo `index.html` em seu navegador
3. Digite um CEP válido no formato `12345-678` ou `12345678`
4. Clique em "Buscar"
5. Veja os dados do endereço exibidos na tela

## 🔍 Exemplos de CEP

- **São Paulo/SP:** 01310-100
- **Rio de Janeiro/RJ:** 20040-020
- **Brasília/DF:** 70040-020
- **Natal/RN:** 59020-100

## 📡 API Utilizada

O projeto utiliza a [ViaCEP](https://viacep.com.br/), uma API pública e gratuita para consulta de CEPs brasileiros.

**Endpoint:** `https://viacep.com.br/ws/{CEP}/json/`

## 🎨 Características da Interface

- Gradiente de fundo azul suave
- Card centralizado com sombra
- Campos de resultado organizados
- Indicador de carregamento (preparado para uso)
- Mensagens de erro (preparadas para uso)
- Totalmente responsivo

## 🛠️ Possíveis Melhorias

- Implementar formatação automática do CEP (adicionar hífen)
- Adicionar tratamento de erros completo
- Mostrar indicador de carregamento durante a busca
- Adicionar histórico de buscas
- Implementar busca por endereço (reversa)
- Adicionar botão para copiar endereço
- Salvar buscas recentes no localStorage

## 📝 Estrutura dos Dados Retornados

```json
{
  "cep": "01310-100",
  "logradouro": "Avenida Paulista",
  "bairro": "Bela Vista",
  "localidade": "São Paulo",
  "uf": "SP",
  "estado": "São Paulo"
}
```

## ⚠️ Observações

- A API ViaCEP requer conexão com a internet
- Alguns CEPs podem não retornar todos os campos
- CEPs inexistentes retornarão erro da API

## 📄 Licença

Este projeto é livre para uso pessoal e educacional.

## 🤝 Contribuições

Sugestões e melhorias são bem-vindas!

---

Desenvolvido usando HTML, CSS e JavaScript