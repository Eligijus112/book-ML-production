# Painless guide for machine learning in production

This project houses the book about how to create, validate and put into production machine learning models in python. 

# Creating and activating the virtual environment 

Creation:
```
virtualenv book
```

Populating with needed packages:
```
pip install -r requirements.txt
```

Activating: 
```
source book/bin/activate
```

# Rendering the book 

```
jupyter-book build ML-book
```