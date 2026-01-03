# Editor Bitmap PRO - Expansão de Topo 🚀

Uma ferramenta web poderosa, leve e intuitiva para editar e criar fontes bitmap personalizadas. Este editor foi otimizado para displays em projetos de eletrônica, como Arduino, ESP32, STM32, LCDs Nokia 5110, OLED SSD1306 e outros.

O grande diferencial desta ferramenta é a sua lógica de **Expansão de Topo**, que permite ajustar a altura da fonte sem perder o alinhamento da base dos caracteres.



## ✨ Funcionalidades Principais

- **Gestão Multi-Fonte:** Carregue, visualize e alterne entre várias fontes dentro do mesmo arquivo de texto.
- **Lógica de Expansão de Topo:** Único editor que permite aumentar a altura da fonte adicionando espaço no topo automaticamente. Isso preserva o desenho original e mantém a linha de base (baseline) consistente.
- **Desenho Dinâmico:** Suporte a clique e arraste para desenho rápido de glifos na grade.
- **Ferramentas de Manipulação:**
  - Limpar: Reseta o glifo atual, removendo todos os pixels ativos de uma só vez. Útil para reiniciar um desenho sem precisar apagar pixel por pixel.
  - Inversão de cores: (Pixels On/Off).
  - Deslocamento vertical (Shift Up/Down): para ajuste fino de posição.
  - Espelhamento de visualização (Inv V e Inv H): para facilitar o trabalho com diferentes drivers de display.
- **Exportação Profissional:** Gere códigos compatíveis com `PROGMEM` e exporte arquivos de cabeçalho (`.h`) prontos para compilação no Arduino IDE ou PlatformIO.

## 🛠️ Formato de Dados Suportado

O editor trabalha com o formato de armazenamento por **Colunas Verticais (Vertical Column Bitmap)**:
1. O primeiro byte define o **BPC** (Bytes Per Character / Passo).
2. Cada bloco de caractere começa com a sua **Largura** individual.
3. Os bits são processados verticalmente (cada byte representa uma coluna).



## 🚀 Como Utilizar

1. **Instalação:** Não é necessária! Basta baixar o arquivo `Editor_de_Fontes_Bitmap_Pro.html` e abri-lo em qualquer navegador moderno (Chrome, Edge, Firefox).
2. **Carregar Fonte:** Cole o código C++ existente na caixa de texto e clique em **"Carregar Código"**.
3. **Edição:** Selecione o caractere na lista lateral e utilize a grade central para desenhar.
4. **Exportar:** Clique em **"Exportar .h"** para salvar o arquivo de cabeçalho com suas alterações.

## 📝 Manual do Usuário Integrado

Para facilitar o uso, o arquivo HTML possui uma seção de ajuda detalhada no rodapé, explicando cada botão e função do programa.

## 📄 Licença

Este projeto é de código aberto. Sinta-se à vontade para usar, modificar e compartilhar com a comunidade maker!

---
*Desenvolvido para facilitar a criação de interfaces em sistemas embarcados.*