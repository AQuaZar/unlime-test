### To fill database:
 `python manage.py shell < product_reviews/fill_db.py`

via docker:

 `sudo docker compose run -T web python manage.py shell < product_reviews/fill_db.py`


### Endpoints:
 * To get product by identifier `api/product/{aisin}`
 * To create review `/api/review`