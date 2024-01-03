salve seus lindos,

por falar capim, a estrutura básica, segue o ecossistema verticalizado plimm, com moeda plimm, base do cashbackplimm, que conversa com todas moedas..
Não há serviço de cobrança via API Pix sendo oferecido a 1 centavo por cobrança(exceto se a cobrança for de R$1 ou menos). Talvez você consiga convencer algum PSP a cobrar isso desse projeto específico dado seu impacto social, mas os valores típicos são bem maiores que esse. Há até vários PSPs não cobrando nada nesses primeiros meses do Pix, então essa janela pode ser usada para colocar algo no ar e depois achar uma "casa hospitaleira".

o pix ja aceita transações em centavos para rastreamento conversibilidade automática entre

plimm == eth == pix analógico == pix digital == pix chain

como anda a implementação do pixchain?

abraços
feliz ano novo \o/
2024, carpim per capita de 30 ETH para gado de esquerda centro e direita.
paz no campo.

#dezembro 2023, classe ecossistema plimm versão 1.0.5, zeh sobrinho, @poplixo

-record(banco_plimm, {nome, cripto_conta, posicao_geografica, conta_energia}).
-record(cartao_credito_carbono_debito, {numero, titular, validade, cripto_conta}).
-record(cliente_plimm, {nome, cripto_conta, posicao_geografica, conta_energia}).
-record(residuo_tecnico_plimm, {peso, consumo_energia_tonelada, cripto_conta}).
-record(garrafa_plimm, {marca, modelo, rotulo, ano, produtor, origem, qr_code, casco_plimm, peso, preco, consumo_energia_garrafa, cripto_conta}).
-record(supermercado_plimm, {nome, cripto_conta, posicao_geografica, conta_energia}).
-record(catador_plimm, {nome, cripto_conta, posicao_geografica, conta_energia}).
-record(cooperativa_catadores_plimm, {nome, cripto_conta, posicao_geografica, conta_energia}).
-record(recicladora_plimm, {nome, cripto_conta, posicao_geografica, conta_energia, consumo_energia_garrafa}).
-record(fabrica_garrafa_plimm, {nome, cripto_conta, posicao_geografica, conta_energia, consumo_energia_tonelada}).
-record(engarrafador_plimm, {nome, cripto_conta, posicao_geografica, conta_energia, consumo_energia_garrafa}).
-record(produtor_energia_plimm, {nome, cripto_conta, posicao_geografica, conta_energia, tipo_energia, eficiencia}).
-record(hidraulica_plimm, {eficiencia}).
-record(solar_plimm, {eficiencia}).
-record(eolica_plimm, {nome, cripto_conta, posicao_geografica, conta_energia, eficiencia, altura_torre}).
-record(termica_plimm, {nome, tipo_combustivel, proporcao_combustivel, eficiencia}).
-record(hibrida_plimm, {nome, tipo_combustivel1, proporcao_combustivel1, proporcao_combustivel2, eficiencia}).

%% banco_plimm
-record(banco_plimm, {nome, cripto_conta, posicao_geografica, conta_energia}).

new_banco_plimm(Nome, CriptoConta, PosicaoGeografica, ContaEnergia) ->
#banco_plimm{nome = Nome, cripto_conta = CriptoConta, posicao_geografica = PosicaoGeografica, conta_energia = ContaEnergia}.

%% cartao_credito_carbono_debito
-record(cartao_credito_carbono_debito, {numero, titular, validade, cripto_conta}).

new_cartao_credito_carbono_debito(Numero, Titular, Validade, CriptoConta) ->
#cartao_credito_carbono_debito{numero = Numero, titular = Titular, validade = Validade, cripto_conta = CriptoConta}.

%% cliente_plimm
-record(cliente_plimm, {nome, cripto_conta, posicao_geografica, conta_energia}).

new_cliente_plimm(Nome, CriptoConta, PosicaoGeografica, ContaEnergia) ->
#cliente_plimm{nome = Nome, cripto_conta = CriptoConta, posicao_geografica = PosicaoGeografica, conta_energia = ContaEnergia}.

%% residuo_tecnico_plimm
-record(residuo_tecnico_plimm, {peso, consumo_energia_tonelada, cripto_conta}).

new_residuo_tecnico_plimm(Peso, ConsumoEnergiaTonelada, CriptoConta) ->
#residuo_tecnico_plimm{peso = Peso, consumo_energia_tonelada = ConsumoEnergiaTonelada, cripto_conta = CriptoConta}.

%% garrafa_plimm
-record(garrafa_plimm, {marca, modelo, rotulo, ano, produtor, origem, qr_code, casco_plimm, peso, preco, consumo_energia_garrafa, cripto_conta}).

new_garrafa_plimm(Marca, Modelo, Rotulo, Ano, Produtor, Origem, QrCode, CascoPlimm, Peso, Preco, ConsumoEnergiaGarrafa, CriptoConta) ->
#garrafa_plimm{marca = Marca, modelo = Modelo, rotulo = Rotulo, ano = Ano, produtor = Produtor, origem = Origem, qr_code = QrCode, casco_plimm = CascoPlimm, peso = Peso, preco = Preco, consumo_energia_garrafa = ConsumoEnergiaGarrafa, cripto_conta = CriptoConta}.

%% supermercado_plimm
-record(supermercado_plimm, {nome, cripto_conta, posicao_geografica, conta_energia}).

new_supermercado_plimm(Nome, CriptoConta, PosicaoGeografica, ContaEnergia) ->
#supermercado_plimm{nome = Nome, cripto_conta = CriptoConta, posicao_geografica = PosicaoGeografica, conta_energia = ContaEnergia}.

%% catador_plimm
-record(catador_plimm, {nome, cripto_conta, posicao_geografica, conta_energia}).

new_catador_plimm(Nome, CriptoConta, PosicaoGeografica, ContaEnergia) ->
#catador_plimm{nome = Nome, cripto_conta = CriptoConta, posicao_geografica = PosicaoGeografica, conta_energia = ContaEnergia}.

%% cooperativa_catadores_plimm
-record(cooperativa_catadores_plimm, {nome, cripto_conta, posicao_geografica, conta_energia}).

new_cooperativa_catadores_plimm(Nome, CriptoConta, PosicaoGeografica, ContaEnergia) ->
#cooperativa_catadores_plimm{nome = Nome, cripto_conta = CriptoConta, posicao_geografica = PosicaoGeografica, conta_energia = ContaEnergia}.

%% recicladora_plimm
-record(recicladora_plimm, {nome, cripto_conta, posicao_geografica, conta_energia, consumo_energia_garrafa}).

new_recicladora_plimm(Nome, CriptoConta, PosicaoGeografica, ContaEnergia, ConsumoEnergiaGarrafa) ->
#recicladora_plimm{nome = Nome, cripto_conta = CriptoConta, posicao_geografica = PosicaoGeografica, conta_energia = ContaEnergia, consumo_energia_garrafa = ConsumoEnergiaGarrafa}.

%% fabrica_garrafa_plimm
-record(fabrica_garrafa_plimm, {nome, cripto_conta, posicao_geografica, conta_energia, consumo_energia_tonelada}).

new_fabrica_garrafa_plimm(Nome, CriptoConta, PosicaoGeografica, ContaEnergia, ConsumoEnergiaTonelada) ->
#fabrica_garrafa_plimm{nome = Nome, cripto_conta = CriptoConta, posicao_geografica = PosicaoGeografica, conta_energia = ContaEnergia, consumo_energia_tonelada = ConsumoEnergiaTonelada}.

%% engarrafador_plimm
-record(engarrafador_plimm, {nome, cripto_conta, posicao_geografica, conta_energia, consumo_energia_garrafa}).

new_engarrafador_plimm(Nome, CriptoConta, PosicaoGeografica, ContaEnergia, ConsumoEnergiaGarrafa) ->
#engarrafador_plimm{nome = Nome, cripto_conta = CriptoConta, posicao_geografica = PosicaoGeografica, conta_energia = ContaEnergia, consumo_energia_garrafa = ConsumoEnergiaGarrafa}.

%% produtor_energia_plimm
-record(produtor_energia_plimm, {nome, cripto_conta, posicao_geografica, conta_energia, tipo_energia, eficiencia}).

new_produtor_energia_plimm(Nome, CriptoConta, PosicaoGeografica, ContaEnergia, TipoEnergia, Eficiencia) ->
#produtor_energia_plimm{nome = Nome, cripto_conta = CriptoConta, posicao_geografica = PosicaoGeografica, conta_energia = ContaEnergia, tipo_energia = TipoEnergia, eficiencia = Eficiencia}.

%% hidraulica_plimm
-record(hidraulica_plimm, {eficiencia}).

new_hidraulica_plimm(Eficiencia) ->
#hidraulica_plimm{eficiencia = Eficiencia}.

%% solar_plimm
-record(solar_plimm, {eficiencia}).

new_solar_plimm(Eficiencia) ->
#solar_plimm{eficiencia = Eficiencia}.

%% eolica_plimm
-record(eolica_plimm, {nome, cripto_conta, posicao_geografica, conta_energia, eficiencia, altura_torre}).

new_eolica_plimm(Nome, CriptoConta, PosicaoGeografica, ContaEnergia, Eficiencia, AlturaTorre) ->
#eolica_plimm{nome = Nome, cripto_conta = CriptoConta, posicao_geografica = PosicaoGeografica, conta_energia = ContaEnergia, eficiencia = Eficiencia, altura_torre = AlturaTorre}.

%% termica_plimm
-record(termica_plimm, {nome, tipo_combustivel, proporcao_combustivel, eficiencia}).

new_termica_plimm(Nome, CriptoConta, PosicaoGeografica, ContaEnergia, Eficiencia) ->
#termica_plimm{nome = Nome, tipo_combustivel = CriptoConta, proporcao_combustivel = PosicaoGeografica, eficiencia = Eficiencia}.

%% hibrida_plimm
-record(hibrida_plimm, {nome, tipo_combustivel1, proporcao_combustivel1, proporcao_combustivel2, eficiencia}).

new_hibrida_plimm(Nome, CriptoConta, PosicaoGeografica, ContaEnergia, Eficiencia) ->
#hibrida_plimm{nome = Nome, tipo_combustivel1 = CriptoConta, proporcao_combustivel1 = PosicaoGeografica, proporcao_combustivel2 = ContaEnergia, eficiencia = Eficiencia}.
