# pulque-pagos-data

Datos sintéticos de transacciones de socios para el laboratorio Pulque Pagos.

- Ruta: `partners/<partner_id>/<YYYY-MM>.csv`
- Columnas: `transaction_id,partner_id,merchant_id,transaction_ts,amount_usd,currency,card_token,card_network,status,fraud_flag,chargeback_flag`
- Los `card_token` son cadenas aleatorias, no números de tarjeta.
- Todos los datos son ficticios.
