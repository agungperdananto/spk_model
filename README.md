# spk_model

## Virtualenv
install, create, activate virtual environment using virtualenv
https://medium.com/analytics-vidhya/virtual-environment-6ad5d9b6af59

## create postgresql database

## create table 
run:
```
 python main.py create_table```

## create data
run this query in your db client

```
INSERT INTO public.house (developer,lb,lt,price) VALUES
	 ('ciputra',75,80,850),
	 ('sinarmas',70,50,950),
	 ('sasmita',78,82,650),
	 ('lippo',65,50,700),
	 ('ciputra',65,70,750),
	 ('sinarmas',120,110,1500);
```

## run SAW


```
python main.py saw
```

