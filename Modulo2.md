# Modulo 2 - Explorando o Poder da Plataforma ServiceNow

## Conteúdo do Módulo

![alt text](<assets/image02.png>)

## Objetivos de Aprendizagem

- Explicar o valor de uma implementação base (baseline).

- Definir uma instância ServiceNow.

- Aumentar a plataforma configurando uma instância para refletir a imagem da empresa e rotulando as abas da instância.

- Instalar aplicações e plugins.

|   Detalhamento dos Objetivos  |   ObjetivoDescrição Detalhada |
|-------------------------------|-------------------------------|
|   Explicar o valor de uma implementação base (baseline).  |   Compreender a importância de manter uma instância ServiceNow próxima ao estado padrão (baseline) para facilitar atualizações futuras, garantir a estabilidade do sistema e minimizar conflitos de personalização.   |
|   Definir uma instância ServiceNow.   |   Entender os diferentes tipos de instâncias (desenvolvimento, teste, produção) e seus propósitos dentro do ciclo de vida do desenvolvimento de software.   |
|   Aumentar a plataforma configurando uma instância...   |   Aprender a personalizar a aparência e o comportamento da instância para refletir a identidade corporativa, incluindo a modificação de logotipos, cores e rótulos de abas.   |
|   Instalar aplicações e plugins.   |   Saber como localizar, instalar e gerenciar aplicações e plugins adicionais para estender as funcionalidades da plataforma ServiceNow.   |


## Laboratórios e Atividades

2.1.1: Configurar uma instância.

### Passo a Passo do Laboratório 2.1.1: Configurar uma Instância
Este laboratório foca nas atividades de Branding (Marca) e personalização inicial de uma instância do ServiceNow. O objetivo é fazer com que a instância reflita a identidade visual da empresa, tornando-a mais familiar e profissional para os usuários.

#### Roteiro do Laboratório: Configurar uma Instância

- Parte 1: Aplicar a Marca da Empresa (Branding)
    * Acessar a Configuração de Temas:
        - Caminho (Navegador de Aplicativos): Digite System Properties $\rightarrow$ Clique em Configuração básica UI16.
    * Configurar núcleos e logotipo:
        - Definir o Tema: Na seção Color (Cor), altere o tema principal para uma cor que represente a marca da sua empresa (Ex: Azul corporativo, Verde).
            - Elemento de Texto: Defina o código hexadecimal da cor principal (Ex: #004F71 para azul escuro).
        - Upload do Logotipo (Banner Image): Na seção Banner Image, faça o upload do arquivo de imagem do logotipo da sua empresa.
            - Elemento de Texto/Ação: Localize e selecione o arquivo do logotipo (geralmente um PNG/JPEG pequeno).
    * Configurar ou banner de texto:
        - Banner Text: No campo Banner Text, insira o nome da empresa ou da instância. Isso aparecerá no topo, ao lado do logotipo.
            - Elemento de Texto: Ex: [Nome da Empresa] - Produção ou [Nome da Empresa] - DEV.Salvar Alterações: Clique em Save (Salvar) para aplicar as configurações e observar as mudanças na interface.
- Parte 2: Rotular e personalizar Abbas (título Favicon e Navigator)
    * Acessar as Propriedades do Sistema (Favicon):Caminho (Navegador de Aplicativos): Digite System Properties $\rightarrow$ Clique em System (ou sys_properties.do na caixa do navegador).Configurar o Favicon;Buscar Propriedade: Pesquise pela propriedade chamada glide.product.icon.Valor: Altere o valor para refletir o ícone da sua empresa. O ideal é fazer o upload de um arquivo de ícone (.ico ou .png) e referenciá-lo aqui.Elemento de Ação: O laboratório pode exigir que você suba um ícone através do Images $\rightarrow$ System UIe use o nome do arquivo aqui.Configurar o Título do Navegador:Buscar Propriedade: Pesquise pela propriedade chamada glide.product.name.Valor: Altere este valor para o nome que você deseja que apareça na aba do seu navegador.Elemento de Texto: Ex: Serviços de TI da [Nome da Empresa].Salvar e Verificar: Salve as propriedades e recarregue a página do navegador (F5 ou Ctrl+R) para ver o novo Favicon e o novo título da aba.
- Parte 3: Instalar uma Aplicação (Plugin)
    * Esta parte prepara a instância para funcionalidades futuras, instalando componentes não incluídos na implementação base.Acessar o Gerenciamento de Plugins:Caminho (Navegador de Aplicativos): Digite Plugins (ou System Definition $\rightarrow$ Plugins).Identificar e Instalar um Plugin:Buscar Plugin: Use a barra de pesquisa para encontrar um plugin específico relevante para a próxima etapa do curso (Ex: Um plugin de exemplo de integração ou um componente de teste).Elemento de Texto de Busca (Exemplo): ServiceNow IntegrationHub Starter Pack ou Customer Service Management.Instalação: Clique no nome do plugin e, em seguida, clique no botão Install (Instalar) ou Activate (Ativar).Confirmar a Instalação:Leia o aviso sobre a ativação (que pode levar alguns minutos).Clique em Activate (Ativar) novamente para confirmar.Aguarde a conclusão do processo. O sistema irá notificar quando o plugin estiver instalado e a instância estiver pronta para uso.