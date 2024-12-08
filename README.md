## Sobre o Projeto

Este projeto utiliza o pacote **SkiaSharp** para manipulação gráfica, escolhido por sua maior capacidade em comparação ao **GraphicsView/IDrawable**. Adicionalmente, foi integrado o **CommunityToolkit** para seguir o padrão MVVM, reduzindo códigos repetitivos e promovendo a implementação alinhada ao princípio **DRY** (Don't Repeat Yourself).

### Refatoração e Melhorias

O método `GenerateBrownianMotion` foi analisado e refatorado devido a alguns problemas identificados, como:  
- Falta de padronização nas nomenclaturas (mistura de idiomas e nomes pouco descritivos);  
- Ausência de documentação clara (comentários e sumários);  
- Isolamento do método, dificultando sua reutilização.

As principais melhorias realizadas foram:  
1. Padronização e renomeação de variáveis e métodos com nomenclaturas consistentes e descritivas.  
2. Adição de comentários explicativos e sumários para facilitar a manutenção e a compreensão do código.  
3. Reestruturação do método, movendo-o para uma classe chamada **Graphics**. Essa centralização permite organizar e reutilizar lógicas relacionadas à geração de gráficos.

### Funcionalidades

Foram implementados todos os requisitos obrigatórios e quase todos os opcionais. O requisito opcional para simulação de múltiplos resultados foi omitido, pois sua implementação poderia entrar em conflito com a funcionalidade de personalização do gráfico. 

Entretanto, várias melhorias foram adicionadas para enriquecer a experiência do usuário, incluindo:  
- **Grid** e **escala numérica** para visualização mais clara dos dados.  
- **Botão de configuração** para mostrar/ocultar opções de layout do gráfico.  
- Suporte aos modos **light** e **dark**, respeitando a preferência do usuário.

### Configurações e Personalização

Embora os inputs principais tenham sido mantidos como campos numéricos, algumas opções de layout foram configuradas com **sliders** e **steppers**, permitindo ajustes mais dinâmicos.

---

### Capturas de Tela
   
#Android

https://github.com/user-attachments/assets/446c0484-a61d-4e12-8805-01325a513add

#Windowns

https://github.com/user-attachments/assets/53d75c07-2195-4e7b-8d25-d414e3ddba3a

---

