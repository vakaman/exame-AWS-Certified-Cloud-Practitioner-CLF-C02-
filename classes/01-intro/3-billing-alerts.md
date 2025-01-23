## Alerta de custo

* Podemos criar um alerta para que, caso algum recurso exceda um valor x, a aws notifica por e-mail, evitando gasto desnecessário, principalmente por esquecimento.
* O CloudWatch consegue monitorar o custo através do Billing.


### Ativando o Billing para o cloudWatch

* Menu
    * Conta
        * Preferências de faturamento
        * Preferências de alerta
            *   Alertas de faturamento do CloudWatch -> (Precisa estar Ativado)


* CloudWatch 
    * Todos os alarmes
        * Criar alarme
        * Seleciona as métricas
        * Neste caso vamos utilizar o faturamento total da conta
        * Selecionamos a condição de interesse >= $10 por exemplo
        * Configuramos o serviço de notificação para utilziar o SNS
        * Criamos um tópico SNS com o destino ao seu e-mail
        * Confirmamos a assinatura do seu e-mail no tópico de notificação.



