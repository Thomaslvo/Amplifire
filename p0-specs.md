# RoSA

Meet RoSA your robotic shopping assistant!

## Scenario

You're an entrepreneur that provides shopping services to a select clientele (i.e you're an instacart shopper). To be able to focus on your main service of shopping for your clients, you need a robot assitant to help you manage your records.

## Functionalities

- You keep a record of your clients and their shopping lists in an excel workbook, you keep a separate record of the items available in the vendors you buy products from. RoSa should be able to take the customer shopping lists and cross referemce them against items available on every vendor and create an expense report detailing the transaction.

  - The expense report should contain:

    - any items that were out of stock or not found
    - total of the shopping trip
    - Where products were bought
    - calculated value for your services \*
    - pay = 20 USD base fee + vendor tax (i.e getting their products from more than one vendor costs more)
      - vendor tax:
        - 1 vendor visited = 0
        - 2+ vendors visited = (10 + 5\*number of vendors visited)% of the shopping subtotal
          - Ex:
            - 2 vendors visited = 20% of the shopping subtotal
            - 3 vendors visited = 25% of shopping subtotal

  - Do note that the expense report should be in a .xls file categorized by customer

- You're working in tandem with the vendors, to make shopping easier for you. You have a copy of their inventory of products that you can review beforehand so you can contact the vendor to prepare the products for you to pick up. RoSA should be able to take these vendor inventory and update the stock of your copy so you have an idea of what's available after a shopping trip.

  - Note that vendors give you comission, RoSA should prioritize vendors that give you high commission\*
    - Say for example: vendor A gives you 5% of the subtotal, vendor B gives you 20% of the subtotal, RoSA should favor vendor B more.

- RoSA should compile for you the list of vendors you need to visit to pick up your orders.

- Bonus: As a good business practice, you like to inform your customers when you've finished their shopping and send an expense report of their latest trip along with a receipt for your services. RoSA should be able to fire off these emails to specific client emails. \*

---

Note: any requirement with the \* is a stretch requirement

The prize for best project gets to choose my bg, group with highest cummulative score on the project chooses my zoom filter

---