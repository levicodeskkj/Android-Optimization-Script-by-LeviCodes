# Android Optimization Script

**Autor**: [levicodeskkj](https://github.com/levicodeskkj)

---

## Descrição

Este **Android Optimization Script** foi desenvolvido para melhorar a performance geral de dispositivos Android. Com ajustes finos nas configurações de **memória**, **bateria**, **rede**, e **processos em segundo plano**, o script visa oferecer uma experiência mais fluída e responsiva, maximizando o desempenho sem comprometer a eficiência energética.

A principal finalidade é otimizar o uso de recursos do dispositivo, desabilitando serviços e ajustando configurações do sistema para melhorar o tempo de resposta e a autonomia da bateria.

---

## Funcionalidades

* **Gerenciamento de Brilho e Taxa de Atualização**:
  - Ajuste do brilho automático e das taxas de atualização de tela.
  - Desabilitação de modos de economia de energia relacionados à tela.
  
* **Otimização de Memória e Processos**:
  - Desabilitação do ZRAM e de processos de fundo desnecessários.
  - Limpeza de caches e controle da utilização de memória.
  
* **Gerenciamento de Rede e Conectividade**:
  - Desabilitação de recomendações de rede, tethering e otimizações de Wi-Fi e dados móveis.
  - Ajuste de preferências de rede e parâmetros para reduzir o consumo de dados e melhorar a estabilidade.
  
* **Desempenho e Economia de Bateria**:
  - Desabilitação de gerenciamento adaptativo de bateria e otimização de processos em segundo plano.
  
* **Desabilitação de Funções Não Necessárias**:
  - Desabilitação de funcionalidades como GPS assistido, feedback háptico, e outras funções que consomem recursos desnecessários.
  
* **Modo de Alto Desempenho**:
  - Habilitação de configurações para performance otimizada com foco em velocidade e resposta rápida.
  
* **Limpeza de Caches e Logs**:
  - Limpeza de caches do sistema e desativação de logs de atividades, para liberar espaço e reduzir o uso de recursos.

---

## Compatibilidade

Este script é compatível com **dispositivos Android** que tenham **acesso root**. Ele pode ser utilizado em dispositivos com diferentes chipsets e ROMs, desde que o dispositivo tenha as permissões necessárias para executar os comandos.

---

## Como Instalar e Executar

### Pré-requisitos

- **Root**: O dispositivo precisa estar rooteado.
- **Brevent**: Para um melhor gerenciamento de processos e execução do script sem interferências de outros aplicativos, recomenda-se usar o **Brevent**.

### Passos para Executar

1. **Clone ou Baixe o Repositório**:

   ```bash
   git clone https://github.com/levicodeskkj/android-optimization-script.git

2. **Dê Permissão de Execução ao Script**:

   Navegue até o diretório onde o script foi baixado e execute:

   ```bash
   chmod +x optimize-android.sh
   ```

3. **Alterar o Nome ou Caminho do Arquivo (se necessário)**:

   Dependendo de onde você baixou o script ou como ele foi renomeado, pode ser necessário alterar o nome do arquivo ou caminho para garantir que o script seja executado corretamente. Verifique se o arquivo é chamado **`optimize-android.sh`** ou altere o nome conforme necessário.

4. **Execute o Script**:

   A forma recomendada de executar o script é via **Brevent**. Caso não utilize o Brevent, execute o script diretamente no terminal com permissões de root:

   ```bash
   ./optimize-android.sh
   ```

   Caso não tenha o Brevent instalado, execute o script diretamente com o comando:

   ```bash
   sudo ./optimize-android.sh
   ```

5. **Verifique as Configurações**:

   Após a execução do script, verifique as alterações nas configurações de **Desenvolvedor** e **Gerenciador de Tarefas** para confirmar que o desempenho foi otimizado.

---

## Como Funciona

O **Android Optimization Script** funciona alterando várias configurações do sistema para otimizar o desempenho, reduzir o consumo de recursos e aumentar a estabilidade do dispositivo:

* **Ajustes de Taxas de Atualização e Brilho**: Melhora a fluidez da tela enquanto ajusta o consumo de energia.
* **Otimização de Rede**: Desabilita funções que consomem dados desnecessários, como recomendações de rede e otimizações de Wi-Fi.
* **Limpeza de Memória e Cache**: Reduz o uso de memória e melhora a resposta geral ao liberar recursos.
* **Modo de Desempenho**: Habilita uma performance aprimorada, focando em respostas rápidas sem comprometer a estabilidade.

Esses ajustes são feitos para garantir uma experiência mais rápida e eficiente em dispositivos Android, reduzindo o tempo de resposta e otimizando o uso da bateria.

---

## Changelog

**Última versão**:

* Ajustes finos em configurações de rede e Wi-Fi.
* Melhorias no gerenciamento de cache e memória.
* Desabilitação de funções desnecessárias para maior economia de bateria.

**Versão anterior**:

* Primeira versão do script com otimizações gerais para dispositivos Android.

---

## Notas Importantes

* **Root é necessário**: O script requer permissões de root para realizar alterações no sistema.
* **Backup**: Sempre faça um backup do seu dispositivo antes de executar o script, caso algo não funcione como esperado.
* **Compatibilidade**: O script foi testado em diversas versões do Android, mas pode haver pequenas variações dependendo da ROM ou modificações feitas no sistema.
* **Alteração de Nome ou Caminho**: Se você mover ou renomear o arquivo, será necessário atualizar o caminho no terminal ou o nome do arquivo para corresponder ao que foi alterado.

---

## Contribuições

Contribuições são bem-vindas! Se você encontrar algum bug ou tiver sugestões de melhorias, fique à vontade para abrir uma **issue** ou enviar um **pull request**. Juntos, podemos melhorar ainda mais a performance e estabilidade deste script!

---

## Agradecimentos

Agradeço à **comunidade de desenvolvedores** e **testers** que ajudaram a testar e melhorar o script. Seu feedback tem sido fundamental para aprimorar esse projeto.

---

## Licença

Este projeto está licenciado sob a **Licença MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## Links

* [GitHub - levicodeskkj](https://github.com/levicodeskkj)
* [Documentação do Brevent](https://github.com/Brevent/Brevent)
* [Brevent - Página Oficial](https://github.com/Brevent/Brevent)
