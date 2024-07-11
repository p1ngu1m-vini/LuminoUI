# LuminoUI

LuminoUI é um arquivo simples para criação de interfaces de usuário no servidor MTA (Multi Theft Auto).

## Funcionalidades Principais

- **dxDrawButton:** Função para desenhar botões com efeitos de hover e clique.
- **dxDrawInput:** Componente para entrada de texto com suporte a foco, cursor piscante e interação do mouse.
- **dxDrawScrollableList:** Lista scrollável para seleção de itens.
- **dxDrawPercentageText:** Exibe texto com uma porcentagem animada.
- **dxDrawToggleButton:** Botão com estado ativado/inativo.
- **dxDrawCheckBox:** Checkbox para seleção com marcador.

## Requisitos

- Multi Theft Auto: Server versão 1.5.9 ou superior.

## Exemplo de Uso

```lua
-- Exemplo de uso do dxDrawButton
dxDrawButton(100, 100, 200, 50, 5, {255, 0, 0, 200}, {255, 0, 0, 255}, "Clique Aqui", 1, "default-bold", function()
    outputChatBox("Botão clicado!")
end)
