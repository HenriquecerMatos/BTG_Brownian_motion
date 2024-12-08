Ao ler a solicitação dei preferência ao pacote SkiaSharp pelo fato de ter maior capacidade.

Como utilizaremos o padrão MVVM também instalei o pacote CommunityToolkit para evitar código repetidos e facilitar tal implementação sem quebrar o DRY.

Ao deparar com o código GenerateBrownianMotion percebi alguns “problemas” como Falta de padronização entre nomenclaturas (nomes com pouco descritivos e variações entre pt-br e en), falta de documentação (sumário) além do método estar “solto”, por conta disso renomeei algumas variáveis com nomes descritivos, adicionei comentários e sumário para melhorar a compreensão do código e recriei o mesmo em uma classe chamada “Graphics” para que outros métodos que geram gráficos pudessem ser centralizados em um único lugar, tornando o código mais flexível e organizado.

Criei estrutura de pastas para melhor organizar e simular um ambiente de produção com maior fidelidade (embora muitas estruturas estejam faltando, fiz dessa forma para representar apenas o que há de comum entre as camadas) 

Android

https://github.com/user-attachments/assets/446c0484-a61d-4e12-8805-01325a513add

Windowns

https://github.com/user-attachments/assets/53d75c07-2195-4e7b-8d25-d414e3ddba3a



