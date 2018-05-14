# online-shop
This is an online shopping site using Django framework and celery. User can add products to cart, remove them, place order and 
make payment using Paypal account. User will also get pdf invoice after placing the order.
Site also contains the coupon system.
Admin can export all the orders details to CSV. 

System Requirements:
Inorder to run the project properly you'll need the following:
1: Pycharm
2: Celery (Install celery along RabbitMQ), 
Add following packages to Pycharm:
1: Pillow(For product images)
2: django-weasyprint (For pdf invoices)
3: celery(For asynchronous tasks)
