# Política de Privacidade — AILocalDLP Enterprise

**Última atualização:** 24 de agosto de 2026

A AILocalDLP Enterprise é uma solução de prevenção contra perda de dados (Data Loss Prevention — DLP) destinada a ambientes corporativos. Esta Política de Privacidade descreve como a extensão de navegador AILocalDLP Enterprise e seus componentes associados processam informações durante sua utilização.

A solução foi projetada com foco em **processamento local, minimização de dados e controle corporativo**. O tratamento efetivamente realizado pode variar de acordo com a configuração definida pela organização responsável pela implantação da solução.

## 1. Responsável pelo tratamento

A AILocalDLP Enterprise pode ser implantada e administrada por uma organização para proteger informações corporativas.

Em ambientes corporativos, a organização que instala, configura e administra a solução é responsável por determinar quais dados podem ser processados, quais políticas de segurança serão aplicadas e quais mecanismos de armazenamento ou monitoramento serão utilizados.

Quando aplicável, informações adicionais sobre o controlador/responsável pelo tratamento devem ser fornecidas pela organização administradora.

## 2. Dados que podem ser processados

Dependendo da configuração e das políticas habilitadas, a AILocalDLP Enterprise pode processar as seguintes categorias de informações:

### 2.1 Conteúdo fornecido pelo usuário

A extensão pode analisar localmente conteúdos inseridos ou disponibilizados em aplicações web, incluindo:

* texto inserido em páginas web;
* conteúdo copiado e colado;
* arquivos selecionados para upload;
* metadados necessários para realizar a análise de segurança;
* conteúdo de documentos compatíveis com as políticas configuradas.

O conteúdo analisado é utilizado para determinar se uma operação atende às políticas de prevenção contra perda de dados da organização.

### 2.2 Informações de identificação e contexto corporativo

Quando configurado pelo administrador, o componente corporativo da solução pode processar informações necessárias para identificar o dispositivo ou usuário e registrar eventos de segurança, tais como:

* nome de usuário;
* identificador corporativo;
* endereço de e-mail corporativo;
* departamento ou setor;
* nome do computador;
* domínio corporativo;
* endereço IP;
* identificadores técnicos do dispositivo;
* data e hora do evento;
* resultado da avaliação da política.

Essas informações são utilizadas exclusivamente para fins de segurança, auditoria, investigação e aplicação das políticas corporativas configuradas.

### 2.3 Dados classificados pela política DLP

A solução pode identificar padrões ou categorias configuradas pela organização, incluindo informações potencialmente confidenciais ou pessoais.

A classificação pode incluir, por exemplo:

* Público;
* Interno;
* Confidencial;
* Restrito.

A presença de uma determinada categoria não significa que o dado seja necessariamente transmitido ou armazenado externamente. O comportamento depende da configuração da implantação corporativa.

## 3. Como os dados são processados

A AILocalDLP Enterprise prioriza o **processamento local no dispositivo do usuário**.

A extensão pode analisar conteúdo no navegador para determinar se uma ação, como copiar, colar ou realizar upload de um arquivo, está de acordo com as políticas de segurança configuradas.

Quando o processamento local é suficiente para tomar uma decisão de segurança, o conteúdo analisado não precisa ser enviado para servidores externos.

A extensão não utiliza o conteúdo analisado para publicidade, criação de perfis comerciais ou rastreamento comportamental.

## 4. Transmissão de dados

A AILocalDLP Enterprise não transmite automaticamente todo o conteúdo analisado para um servidor externo.

Quando uma implantação corporativa possui um agente local, servidor de gerenciamento, webhook, SIEM ou outro mecanismo de integração configurado pelo administrador, determinados **eventos de segurança e metadados** podem ser transmitidos para esses sistemas.

Dependendo da configuração, um evento pode conter informações como:

* tipo de evento;
* data e hora;
* usuário ou identificador corporativo;
* dispositivo;
* aplicação ou domínio relacionado ao evento;
* classificação atribuída;
* ação aplicada pela política;
* motivo da violação;
* informações técnicas necessárias para auditoria.

O conteúdo completo de documentos ou páginas não é transmitido por padrão apenas pelo fato de ter sido analisado localmente.

Se a organização configurar explicitamente uma funcionalidade que envie conteúdo para outro sistema, esse tratamento estará sujeito às políticas e configurações dessa organização.

## 5. Armazenamento

A extensão pode armazenar localmente informações técnicas necessárias ao seu funcionamento, incluindo:

* configurações da extensão;
* estado operacional;
* identificadores técnicos;
* resultados temporários de análise;
* informações necessárias para aplicar as políticas configuradas.

Os dados armazenados localmente permanecem no dispositivo enquanto forem necessários para a operação da solução ou até que sejam removidos pelo navegador, administrador ou mecanismo de gerenciamento utilizado pela organização.

Quando eventos de segurança são encaminhados para sistemas corporativos externos, o período de retenção desses dados é determinado pela organização responsável pelo respectivo sistema.

## 6. Compartilhamento de dados

A AILocalDLP Enterprise **não vende dados pessoais ou confidenciais** e não compartilha dados para fins de publicidade.

Os dados podem ser disponibilizados somente aos componentes necessários para a operação da solução e, quando aplicável, aos sistemas corporativos configurados pelo administrador, como:

* servidores de gerenciamento;
* sistemas de monitoramento;
* SIEM;
* sistemas de auditoria;
* mecanismos corporativos de resposta a incidentes;
* serviços de integração configurados pela organização.

A extensão não compartilha deliberadamente informações com terceiros independentes para fins comerciais ou de publicidade.

## 7. Serviços de terceiros

A AILocalDLP Enterprise pode ser integrada a serviços corporativos de terceiros quando essa integração for habilitada pelo administrador da organização.

Esses serviços podem incluir plataformas de monitoramento, registro de eventos, automação ou resposta a incidentes.

Quando uma integração de terceiros estiver habilitada, os dados enviados estarão sujeitos também às políticas de privacidade e segurança do respectivo provedor.

A extensão não utiliza serviços de terceiros para publicidade comportamental.

## 8. Dados pessoais e informações confidenciais

A finalidade da AILocalDLP Enterprise é justamente detectar e proteger informações que podem ser pessoais, confidenciais ou corporativamente sensíveis.

Por esse motivo, a extensão pode necessariamente **processar informações que contenham dados pessoais ou confidenciais**, dependendo do conteúdo apresentado ao navegador e das políticas configuradas pela organização.

O processamento desses dados ocorre exclusivamente para finalidades relacionadas à segurança da informação, prevenção contra perda de dados, aplicação de políticas, auditoria e resposta a incidentes.

A solução não utiliza esses dados para publicidade, venda de informações ou criação de perfis comerciais.

## 9. Finalidade do tratamento

Os dados processados pela solução podem ser utilizados para:

1. aplicar políticas corporativas de DLP;
2. detectar possíveis violações de segurança;
3. impedir ou permitir determinadas operações;
4. classificar informações;
5. registrar eventos de segurança;
6. auxiliar auditorias;
7. investigar incidentes;
8. proteger informações corporativas;
9. manter e diagnosticar o funcionamento da solução.

Nenhum dado é utilizado para finalidade incompatível com essas funções de segurança.

## 10. Retenção

A retenção depende do tipo de informação e da configuração da implantação.

Dados temporários utilizados durante uma análise local podem ser descartados após a conclusão do processamento ou quando deixarem de ser necessários.

Eventos enviados para sistemas corporativos podem permanecer armazenados de acordo com as políticas de retenção, auditoria e segurança estabelecidas pela organização.

A AILocalDLP Enterprise não estabelece um período universal de retenção para dados armazenados em infraestrutura administrada por terceiros ou pela organização cliente.

## 11. Segurança

A AILocalDLP Enterprise adota medidas técnicas destinadas a reduzir a exposição de informações sensíveis, incluindo:

* processamento local sempre que tecnicamente possível;
* minimização da transmissão de conteúdo;
* separação entre análise local e eventos de auditoria;
* aplicação de políticas de segurança configuráveis;
* comunicação com componentes corporativos por mecanismos configurados pela organização;
* controle administrativo da configuração da solução.

Nenhum sistema pode garantir segurança absoluta. A organização responsável pela implantação também deve aplicar controles adequados de acesso, armazenamento, autenticação, monitoramento e retenção.

## 12. Permissões do navegador

A extensão pode solicitar permissões necessárias para executar suas funções de segurança.

Essas permissões podem permitir que a extensão:

* analise conteúdo de páginas quando necessário para aplicar políticas DLP;
* detecte operações relacionadas a entrada, cópia ou upload de dados;
* avalie arquivos selecionados para análise;
* comunique-se com componentes locais da solução;
* armazene configurações e informações técnicas necessárias ao funcionamento.

As permissões são utilizadas para as finalidades descritas nesta política e não para publicidade ou rastreamento comercial.

## 13. Dados não coletados para fins comerciais

A AILocalDLP Enterprise não:

* vende informações pessoais;
* utiliza dados para publicidade;
* utiliza dados para publicidade comportamental;
* cria perfis comerciais dos usuários;
* utiliza o conteúdo analisado para treinamento de modelos de publicidade;
* coleta informações com a finalidade de rastrear usuários entre diferentes serviços.

## 14. Responsabilidade da organização administradora

Em uma implantação Enterprise, a organização que administra a solução pode definir:

* quais políticas DLP serão aplicadas;
* quais categorias de dados serão identificadas;
* quais eventos serão registrados;
* quais informações serão enviadas para sistemas corporativos;
* períodos de retenção;
* integrações externas;
* permissões administrativas.

Consequentemente, o tratamento de dados em uma implantação corporativa pode variar de acordo com essas configurações.

Os usuários devem consultar também as políticas internas de privacidade, segurança da informação e proteção de dados da organização responsável pela implantação.

## 15. Alterações nesta Política de Privacidade

Esta Política de Privacidade pode ser atualizada para refletir alterações na solução, em suas funcionalidades ou nos requisitos legais e regulatórios aplicáveis.

A versão mais recente será disponibilizada neste documento.

## 16. Contato

Para dúvidas relacionadas ao tratamento de dados pela AILocalDLP Enterprise, entre em contato com o responsável pela administração da solução em sua organização.

**Projeto:** AILocalDLP Enterprise
**Documento:** Política de Privacidade
**Última atualização:** 24/08/2026
