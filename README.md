# algo
pip install -r requirements.txt
ret = api.place_order(buy_or_sell='B', product_type='C',
                        exchange='NSE', tradingsymbol='NIFTY2232416500CE', 
                        quantity=1, discloseqty=0,price_type='SL-LMT', price=545.00, trigger_price=544.50,
                        retention='DAY', remarks='my_order_001')
