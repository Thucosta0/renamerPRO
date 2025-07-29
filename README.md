# 🏥 renamerPRO©

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-Proprietary-red.svg)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)
![Status](https://img.shields.io/badge/status-Production-green.svg)
---

## 📋 **Índice**

- [Visão Geral](#-visão-geral)
- [Características Principais](#-características-principais)
- [Requisitos do Sistema](#-requisitos-do-sistema)
- [Instalação](#-instalação)
- [Guia de Uso](#-guia-de-uso)
- [Arquitetura Técnica](#-arquitetura-técnica)
- [Build e Distribuição](#-build-e-distribuição)
- [Suporte e Manutenção](#-suporte-e-manutenção)
- [Licença e Copyright](#-licença-e-copyright)

---

## 🎯 **Visão Geral**

O **renamerPRO©** é uma solução corporativa desenvolvida para atender às necessidades no processamento de documentos fiscais eletrônicos. O sistema automatiza a conversão de arquivos XML em documentos DANFE padronizados, garantindo conformidade com as normas da Receita Federal e otimização dos processos internos.

### **Objetivos Estratégicos**
- Automatizar o processamento de documentos fiscais
- Reduzir tempo de processamento manual em até 95%
- Garantir conformidade regulatória

---

## ✨ **Características Principais**

### **🚀 Processamento em Massa**
- Conversão simultânea de milhares de arquivos XML
- Processamento paralelo multithread para máxima performance
- Validação automática de integridade dos documentos
- Relatórios detalhados de processamento

### **🎯 Renomeação Inteligente**
- Sistema de renomeação baseado em chaves NFe
- Validação automática de chaves fiscais
- Prevenção de duplicatas e conflitos
- Nomenclatura padronizada para integração

### **🏥 Interface Profissional**
- Interface intuitiva e responsiva
- Feedback visual em tempo real

### **⚡ Alta Performance**
- Processamento paralelo otimizado
- Gestão inteligente de memória
- Logs detalhados para auditoria
- Recuperação automática de erros

---

## 🏗️ **Arquitetura Técnica**

### **Componentes Principais**
- **Frontend**: CustomTkinter (Interface Gráfica)
- **Backend**: Python 3.8+ (Lógica de Negócio)
- **Processamento**: PHP 8.4.8 + NFePHP (Geração DANFE)
- **Dados**: XML/PDF (Entrada/Saída)

### **Fluxo de Processamento**
1. **Entrada**: Validação e sanitização de arquivos XML
2. **Processamento**: Conversão paralela via PHP/NFePHP
3. **Validação**: Verificação de integridade dos PDFs gerados
4. **Saída**: Documentos DANFE padronizados e relatórios

---

### **Copyright e Propriedade Intelectual**

**© 2025 ThTweaks - Todos os direitos reservados**  
**Desenvolvido por: Thucosta**

Este software é propriedade exclusiva da **ThTweaks**, podendo ser compatilhado a fins de uso institucional.

### **Garantia e Responsabilidade**
Este software é fornecido "como está", sem garantias expressas ou implícitas. A ThTweaks não se responsabiliza por danos decorrentes do uso deste software.

---

*Este documento é propriedade intelectual da ThTweaks e contém informações confidenciais.*

## 🚀 Funcionalidades Principais

### 1. 📦 Processamento em Massa
- Conversão de múltiplos XMLs para PDF simultaneamente
- Processamento paralelo (até 5 documentos simultâneos)
- Barras de progresso em tempo real
- Logs detalhados de cada operação

### 2. 📋 Renomeação Inteligente
- Sistema avançado de mapeamento por chave de acesso
- Validação automática de chaves NFe (44 dígitos)
- Importação em lote de dados
- Interface responsiva com tabela profissional

### 3. 🎨 Interface Moderna
- Componentes CustomTkinter modernos
- Layout responsivo e adaptativo
- Paleta de cores médica suavizada

## 📁 Estrutura do Projeto

```
conversor-danfe/
├── danfe_app.py          # Aplicação principal
├── gerador_danfe.php     # Engine PHP com rastro
├── build_exe.py          # Script de build
├── requirements.txt      # Dependências Python
├── composer.json         # Dependências PHP
├── php/                  # Runtime PHP portável
├── vendor/               # Bibliotecas PHP (NFePHP)
└── README.md             # Esta documentação
```

## 📊 Performance

- **Processamento**: 5 XMLs simultâneos
- **Velocidade**: ~1-2,5s por documento
- **Memória**: 512MB máximo
- **Formatos**: XML → PDF (A4 padrão Receita Federal)

## 🔒 Segurança

- Processamento 100% local (sem envio externo)
- Validação rigorosa de arquivos XML
- Logs auditáveis para compliance
- Backup automático opcional

## 📄 Licença

© 2025 ThTweaks 
Sistema desenvolvido internamente para uso Fiscal.
