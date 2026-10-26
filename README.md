# War Maps 1.0 BETA

Jogo de conquista medieval da América do Sul, feudo por feudo. Para Windows (64 bits).

## Baixar

**[WarMaps-1.0-beta-instalador.exe](https://github.com/AinzDragons/war-maps-download/releases/latest/download/WarMaps-1.0-beta-instalador.exe)** (~50 MB)

## Instalar

1. Abra o instalador. Se aparecer "O Windows protegeu o seu computador", clique em **Mais informações > Executar assim mesmo**
   (o instalador não tem assinatura paga).
2. Responda **Sim** quando o Windows pedir permissão de administrador.
3. Deixe as 3 opções marcadas: atalho na área de trabalho, VPN ZeroTier e firewall.
4. Na tela **Rede do grupo no ZeroTier** o código já vem preenchido: só avance.
5. Avise o dono do grupo para **aprovar o seu computador** na rede (sem isso a partida não aparece).

## Jogar com os amigos

No jogo: **JOGAR COM AMIGOS > VPN / REDE LOCAL**. Deve aparecer "ZeroTier ligado: 10.77.118.x".
Um clica em **CRIAR PARTIDA** e os outros em **PROCURAR PARTIDA**.

## Segurança

- A rede do ZeroTier é **privada**: só entra quem o dono aprovar.
- O instalador cria regras no Firewall do Windows que deixam passar, vindo dessa rede, **só o War Maps** (portas UDP 24570 e 24571).
  Pastas compartilhadas, área de trabalho remota e qualquer outra coisa ficam bloqueadas.
- O desinstalador apaga essas regras. O ZeroTier sai em Configurações > Aplicativos > ZeroTier One.

O instalador traz o instalador oficial do ZeroTier One (ZeroTier, Inc., licença MPL-2.0), sem modificações.
