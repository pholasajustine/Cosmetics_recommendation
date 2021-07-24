<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Project - Safe cosmetics recommendation : 
Amandine Gauberville & Justine PHOL-ASA 

*[Data analytics PT, Paris & 17/07/2021 - 24/07/2021]*

## Summary
- [Context](#context)
- [Content](#content)
- [Links](#links)

<a name="context"></a>

## Context
Many products declare to be safe and healthy but which ones are really free from harmful chemicals and toxins ? The list of ingredients to avoid is growing longer each year and it's hard to keep in mind each ingredient to be avoided. It's also not really convenient to have to scan the product with yuka each time you want to try a new product. This project aims to map cosmetic items based on their ingredients similarities and giving content-based filtering recommendation taking into account harmful chemicals and price. 

Can we recommend cosmetics product based on their similarities ?

<a name="content"></a>

## Content

The dataset used is from Kaggle : "Cosmetics datasets". It's been web scrapped from Sephora. It contains 1472 rows and 11 columns.
It contains product types, brands, names, ingredients, skin preference, price (in USD) and rating.
We created a list of harmful substances from the ingredients listed in UFC- Que choisir.

[Codebook](https://drive.google.com/file/d/1z4dAHoN7Y9yZXxQG5rIcwNI7_IFcJf1P/view?usp=sharing)

<a name="links"></a>

## Machine learning

For answering to our problematic, we decided to use the cosine-similarity ML model. Our model gives us 10 similar  cosmetic products from product's input content-based.

## Links

[Repository](https://github.com/pholasajustine/Cosmetics_recommendation)  

[Tableau](https://public.tableau.com/app/profile/gauberville.amandine/viz/Cosmeticsrecommendations/Cosmeticsrecommendationsstory)

[Slides](https://docs.google.com/presentation/d/1z1G23GyCdhBC_8S5znftFD8cbTcb4lxsHXiSKX_FIGk/edit?usp=sharing) 

## Skin type presentation
![img](https://silkup.com/wp-content/uploads/2020/02/Copy-of-Fruits-Information-Campaign-Poster.png)



   
