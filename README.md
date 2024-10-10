
# Pandas Challenge 1        
Repository: python-challenge-1

## What it does

* Use a dataset from a fictional e-commerce company.
* Identify top customers, popular product categories and calculating profits.


## Overview
* Data exploration. Use of the describe function.
* Transformation. Create new column with calculations.
* Analysis.

## Coding overview
* Dictionary: menu is a dict of dict.
* Dictionary: menu_items creates a dictionary to store the menu for
              later retrieval.
* Dictionary: selected_item
* List: customer_order is a  list of dict
* Variables: long list including place_order (bool), i (int), and
            menu_category (str)

## Coding notes
* Includes: while True, for loops, if else, and match: case

## Summary of findings
*These are the top 5 clients by number of orders.
*Each customer has a unique Client ID.
*The top 5 clients are sorted by Total Profit in a descending order. For example, client_id 24741 generated $36.58 million in total profits during the year 2023.
*It is no surprise that this same client also generated the most quantity ordered, shipping price and revenues.
*The results for the four other customers are more similar, measured by the four criterias.

## Summary output

        Quantity Shipping Price ($mil)	Revenues ($mil)	Total Profit ($mil)
client_id				
24741	239,862	5.126	82.269	36.580
38378	73,667	3.429	12.907	3.272
66037	43,018	1.395	10.260	3.255
46820	75,768	1.601	9.744	2.737
33615	64,313	1.829	8.377	2.202


