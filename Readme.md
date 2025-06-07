# Bootloader

Este projeto é um bootloader customizado desenvolvido em C/C++ e Assembly para ambiente Windows. O objetivo principal é inicializar sistemas ou aplicações, fornecendo uma base para carregamento de software logo após a inicialização do computador.

## Funcionalidades

- Inicialização de sistemas ou aplicações personalizadas
- Manipulação de strings e exibição de informações na tela
- Estrutura modular com suporte a C++ e Assembly
- Compatível com ambientes de desenvolvimento modernos (CMake, Visual Studio) e antigos (VC152)

## Estrutura do Projeto

- `bootloader.cpp`, `BootMain.cpp`: Arquivos-fonte principais do bootloader
- `StartPoint.asm`: Ponto de entrada em Assembly
- `CDisplay.cpp`, `CString.cpp`: Utilitários para exibição e manipulação de strings
- `Types.h`, `bootloader.h`, `CDisplay.h`, `CString.h`: Arquivos de cabeçalho
- `build.bat`: Script para build rápido no Windows
- Arquivos de configuração para Visual Studio e CMake

## Como Compilar

### Usando o CMake

1. Instale o [CMake](https://cmake.org/) e um compilador compatível (Visual Studio recomendado).
2. No terminal, execute:

   ```sh
   mkdir build
   cd build
   cmake ..
   cmake --build .
   ```

### Usando o Visual Studio

1. Abra o arquivo de solução `.sln` no Visual Studio.
2. Compile o projeto usando o menu "Build".

### Usando o Script Batch

1. Execute o arquivo `build.bat` no prompt de comando do Windows.

## Como Usar

Após a compilação, o executável `BootLoader.exe` estará disponível na pasta de saída. Execute-o para iniciar o processo de boot customizado.

## Requisitos

- Windows 7 ou superior
- Visual Studio 2017+ ou compilador compatível
- CMake (opcional)

## Licença

Este projeto é distribuído sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.

---
