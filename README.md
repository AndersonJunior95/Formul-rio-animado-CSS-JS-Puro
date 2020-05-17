# Formulário animado com JS puro e CSS Animation

## Desafios

- [x] Fazer o formulário aparecer, suavemente, quando a página abrir

- [x] Fazer os campos aparecerem da esquerda pra direita, siavozamdp a entrada e fazendo-os entrar em momentos distintos

- [x] Quando clicar em Login, Fazer o formulário sair da tela, indo para baixo

- [x] Remover formulário do html e não mostrar rolagem enquanto o formulário está saindo da tela

- [x] Adicionar um efeito diferente de timing para a saída do formulário

- [x] Fazer o formulárop dizer não-não (vibrar) caso haja campos vazios.

- [x] Criar alguns quadrados animados (que fiquem girando) e que saem de baixo da tela (fora do campo de visão) e vão para cima da tela (que saia do campo de visão também). _Detalhes_: Deve ter tamanhos diferentes, sairem em momentos diferentes, terem timing diferente, animação contínua.

## Animation

8 propriedades:

- animation-name: animationname;
- animation-duration: 2s;
- animation-delay: 3s;
- animation-fill-mode: none;
- animation-play-state: running;
- animation-timing-function: ease;
- animation-direction: reverse;
- animation-iteration-count: infinite;

@keyframes animationname {
    0% {

    }
    100% {

    }
}
podemos ter múltiplas ações no mesmo elemento

animation: slide-top 2s; bounce 1s; fade 0.2s;
