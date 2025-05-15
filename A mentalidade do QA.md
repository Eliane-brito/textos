## A mentalidade do QA

É um analista de qualidade, ele tem na sua essência uma explosão de **curiosidade**, de **criticismo** (_é o_  _que o move a fazer perguntas)_ e **empatia pelo cliente** e seu principal _objetivo_ é **a antecipação de problemas** que só seriam identificados pelos clientes (_e essa antecipação de problemas se dá através da aplicação de práticas e recomendações de qualidade e testes de software_)

**As 3 características** que predominam na mentalidade de quem testa:

1 – Precisa validar que o produto atenda às expectativas do meu cliente. (_ele precisa ter uma experiência satisfatória com uso do software, por isso você primeiro precisa entender quais são as expectativas_  _do cliente_)

2 - Tenho de antecipar comportamentos inesperados e alertar os riscos ao meu time. (_não esperar a aplicação ficar pronta_)

3 – É minha missão disseminar essa mentalidade dentre meus colegas. (_treinar, passar para frente esse conhecimento_)

CLIENTES – Alguém que testa uma aplicação pode ter diferentes clientes, por exemplo: o **usuário**, o **desenvolvedor**, o **Product Owner (PO)**, **analista de suporte** e um **sistema terceiro** que utilizará sua API, **etc**.

A **comunicação** como fator chave – O dia a dia de quem testa é permeado por iterações com o time., seja para **entender o produto** que será criado ( _nesse momento que o PO estiver descrevendo sobre o produto, teremos que ter uma noção muito clara do produto e seu time também e seu papel será perguntar de forma a absorver e revelar quais pontos relacionados ao produto que precisa ser criado, de modo que todos que também estejam envolvidos nesse produto consigam perceber_), como para **comunicar riscos**, ou para **discutir uma possível inconsistência no produto** ou até mesmo para **compartilhar algum conhecimento**.

**Algumas dicas**: Ter precisão e assertividade ao comunicar riscos e inconsistências; Não ter medo ou receio de compartilhar seus pensamentos e dúvidas e ser maduro em dar e receber feedback.

Existem formas de colaborar com a qualidade desde as fases iniciais de um projeto, para isso, precisamos participar de cada etapa desde a conceção e influenciar as decisões sob a perspetiva de qualidade.  Como:

**- Na ideação**, revisando a viabilidade do produto (_e se há algum risco_); **no levantamento de requisitos**, revisando sua consistência e boas práticas (_e identificar defeitos_) e **na codificação**, revisando boas práticas e colaborando na escrita de testes.

Levantar riscos sob a perspetiva do usuário final (_porque a nossa mentalidade é voltada a trazer qualidade e tudo que possa gerar risco está no nosso radar e precisa ser comunicado e nesse momento tente ser assertivo_): Risco representa a possibilidade de benefício ou prejuízo em testes, prefiro pensar na possibilidade de prejuízo. Então, eu olho **para o software e listo o que pode dar muito errado, depois penso em testes capazes de mitigar esses riscos** para ter um software de maior qualidade.

Exemplo de uma lista de Riscos de um produto: - Um usuário ter acesso ao saldo ou outra informação do outro usuário; - O botão de confirmação da compra não ser identificável por usuários com problemas visuais; o serviço de notificações ficar indisponível.

A iteração deve ser colaborativa, buscando ajudá-lo a aplicar testes e mostrando ao time os impactos em não testar.

**Terceirização da qualidade** é o termo usado quando a pessoa que desenvolve deixa que toda a qualidade seja averiguada futuramente pela pessoa que testa. Atualmente, pensar dessa maneira pode trazer riscos a qualidade. Logo, ao invés de postergar o envolvimento da pessoa nesta aplicação de qualidade, precisamos ajudar o time a aplicar teste em suas atividades de codificação.

_O ideal é que a qualidade não seja terceirizada, mas seja parte da cultura, do dia a dia, da mentalidade de quem desenvolve de modo que desde o início da codificação se construa testes de maneira apropriada para se ter a confiança de que o produto que foi desenvolvido poderia inclusive ir para produção, ser entregue ao cliente por haver já qualidade testada e o ideal é ter envolvimento das pessoas relacionadas a qualidade de testes desde o início de modo a ter inclusive um pareamento. Isso é sentar ao lado do desenvolver e discutir como aplicar técnicas, recomendações e práticas de qualidade naquele determinado pedaço de código que esta sendo desenvolvido._

Procure sempre imaginar um software em camadas, a divisão mais básica é a de **FRONTEND (F)**  é o que o usuário vê, é a camada exterior, é a camada mais próxima do usuário (parte gráfica) e **BACKEND (B)**  é o que o usuário não vê (programação interna), é o que está por trás do frontend, é o que sustenta o Frontend, é o que dá os dados necessários para processar as regras de negócio e devolvem as informações para que sejam apresentadas ao usuário.

**Identificando o que testar** - Pode ocorrer a partir de duas abordagens: **empírica ou sistemática**. Na abordagem empírica, quem testa deve escolher o que testar baseando-se na sua experiência no produto atual (_é utilizar do seu conhecimento passado e prévio em produtos semelhantes para conseguir realizar testes, mas isso é limitante, pois para escolher testes, precisa ter experiências passadas)._

Já na abordagem sistemática (_vou identificar o que testar com base o uso de técnicas ou estratégias de testes que irão ajudar nas combinações que precisam ser testadas em um determinado software, você fará uso de um guia, de um passo a passo do que fazer_), quem testa se baseia em técnicas de teste que ajudam a identificar o que testar com base em fontes de informação como requisitos, código, riscos, etc.

### POC

– Proof of Concept – Prova de conceito. É uma forma de validar a viabilidade de uma ideia ou conceito. É uma demonstração prática se um sistema funciona como esperado.