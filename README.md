# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href="https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Administração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# FASE 6 / Cap 1 - Despertar da Rede Neural

## 👨‍🎓 Integrantes: 
- <a href="https://www.linkedin.com/in/a1exlima/">RM559784@fiap.com.br - Alex da Silva Lima </a>
- <a href="https://www.linkedin.com/in/johnatanloriano/">RM559546@fiap.com.br - Johnatan Sousa Macedo Loriano</a>
- <a href="https://www.linkedin.com/in/matheus-maia-655bb1250/">RM560683@fiap.com.br - Matheus Augusto Rodrigues Maia</a>
- <a href="https://www.linkedin.com/in/brunoconter/">RM560518@fiap.com.br - Bruno Henrique Nielsen Conter</a>
- <a href="https://www.linkedin.com/in/fabiosantoscardoso/">RM560479@fiap.com.br - Fabio Santos Cardoso</a>

## 👩‍🏫 Professores:
### Tutor(a) 
- <a href="https://www.linkedin.com/in/leonardoorabona/?originalSubdomain=br">Leonardo Ruiz Orabona</a>
### Coordenador(a)
- <a href="https://www.linkedin.com/in/profandregodoi/">André Godoi</a>

## 📜 Descrição

Este projeto, desenvolvido como parte da Fase 6 do curso da FIAP, foca na implementação e avaliação de um sistema de visão computacional utilizando a biblioteca **YOLO** para reconhecimento de objetos, além de uma comparação com outras abordagens de redes neurais. O objetivo é demonstrar as capacidades de visão computacional da **FarmTech Solutions**, uma empresa fictícia que expandiu seus serviços de IA para áreas como saúde animal, segurança patrimonial e análise de documentos.

Neste repositório estão os entregáveis dos dois desafios complementares

## 📂 Estrutura do Repositório

```plaintext
1TIAOR_FIAP_fase6_cap1/
├── .github/               # Configurações do GitHub (workflows, etc.)
├── images/                # Diretorio de imagens para treino, teste e validação
├── labels/                # diretorio de labels das imagens
├── runs-desafio_1/        # diretorios de treino e testes do desafio 1
├── runs-desafio_2/        # diretorios de testes do desafio 2
├── FabioCardoso_rm560479_pbl_fase6-Desafio-1.ipynb  # Notebook da Entrega 1
├── FabioCardoso_rm560479_pbl_fase6-Desafio-2.ipynb  # Notebook da Entrega 2
├── .gitattributes         # Configurações de atributos do Git
├── .gitignore             # Arquivos e pastas ignorados pelo Git
└── README.md              # Este arquivo
```

## 📦 Entregáveis

### Entrega 1: Sistema de Visão Computacional com YOLO Customizado
  - Contém a implementação do sistema de visão computacional com YOLO customizado, incluindo treinamento, validação e teste.
  - Inclui comparações de desempenho com diferentes números de épocas (35 e 55), resultados de acurácia e prints das imagens de teste processadas.
- **Notebook Jupyter**: `FabioCardoso_rm560479_pbl_fase6-Desafio-1.ipynb`
- **Vídeo Demonstrativo**: [Link para o vídeo no YouTube](https://www.youtube.com/watch?v=OHgUcXGzqKg) (não listado, até 5 minutos)
  - Demonstra o funcionamento do sistema, destacando os resultados práticos do modelo.

### Entrega 2: Comparação de Abordagens
- **Notebook Jupyter**: `FabioCardoso_rm560479_pbl_fase6-Desafio-2.ipynb`
  - Apresenta a implementação e comparação de três abordagens: YOLO customizado, YOLO tradicional e uma CNN treinada do zero.
  - Inclui avaliações em termos de facilidade de uso, precisão, tempo de treinamento e tempo de inferência, com análises detalhadas em Markdown.

## 🔧 Como Utilizar

### Pré-requisitos
- **Python** versão 3.10 ou superior.
- Jupyter notebook para executar os notebooks.

### Passo a Passo
1. **Clone o repositório** para sua máquina local:
   ```bash
   git clone https://github.com/brunocorisco86/1TIAOR_FIAP_fase6_cap1.git
   ```

2. **Navegue até a pasta principal**:
   ```bash
   cd 1TIAOR_FIAP_fase6_cap1
   ```

3. **Dependências**:
   ```bash
   Não é necessario, os notebooks instalam automaticamente
   ```

4. **Assista ao vídeo demonstrativo**:
   - Acesse o link do YouTube fornecido acima para visualizar a demonstração prática do sistema.

## 🗃 Histórico de Lançamentos

* 0.1.0 - 29/04/2025
    * Versão inicial com os notebooks e vídeo demonstrativo das entregas.

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/brunocorisco86/1TIAOR_FIAP_fase6_cap1">FarmTech Vision AI</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">FIAP</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>
